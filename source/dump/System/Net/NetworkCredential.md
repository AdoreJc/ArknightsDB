# NetworkCredential

**Namespace:** `System.Net`


## Fields

- `String m_domain`

- `String m_userName`

- `SecureString m_password`


## Properties

- `String UserName`

- `String Password`

- `String Domain`


## Methods

- `String get_UserName()`

- `Void set_UserName(String)`

- `String get_Password()`

- `Void set_Password(String)`

- `String get_Domain()`

- `Void set_Domain(String)`

- `NetworkCredential GetCredential(Uri, String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class NetworkCredential : ICredentials
{
	private String m_domain; // 0x10
	private String m_userName; // 0x18
	private SecureString m_password; // 0x20

	public String UserName { get; set; }
	public String Password { get; set; }
	public String Domain { get; set; }

	// RVA: 0x642a6b8 VA: 0x7598a426b8
	public Void .ctor(String userName, String password) { }
	// RVA: 0x6429614 VA: 0x7598a41614
	public Void .ctor(String userName, String password, String domain) { }
	// RVA: 0x642a81c VA: 0x7598a4281c
	public String get_UserName() { }
	// RVA: 0x642a720 VA: 0x7598a42720
	public Void set_UserName(String value) { }
	// RVA: 0x642a824 VA: 0x7598a42824
	public String get_Password() { }
	// RVA: 0x642a78c VA: 0x7598a4278c
	public Void set_Password(String value) { }
	// RVA: 0x642a8e0 VA: 0x7598a428e0
	public String get_Domain() { }
	// RVA: 0x642a7b0 VA: 0x7598a427b0
	public Void set_Domain(String value) { }
	// RVA: 0x642a8e8 VA: 0x7598a428e8
	internal String InternalGetUserName() { }
	// RVA: 0x642a82c VA: 0x7598a4282c
	internal String InternalGetPassword() { }
	// RVA: 0x642aaa0 VA: 0x7598a42aa0
	internal String InternalGetDomain() { }
	// RVA: 0x642aaa8 VA: 0x7598a42aa8
	public NetworkCredential GetCredential(Uri uri, String authType) { }
}
```