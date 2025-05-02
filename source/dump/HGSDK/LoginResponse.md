# LoginResponse

**Namespace:** `HGSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Boolean isAuthenticate`

- `Boolean isMinor`

- `Boolean needAuthenticate`

- `DateTime issuedAt`

- `DateTime expiresIn`

- `Boolean isLatestUserAgreement`

- `JObject captcha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class LoginResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Boolean isAuthenticate; // 0x30
	public Boolean isMinor; // 0x31
	public Boolean needAuthenticate; // 0x32
	public DateTime issuedAt; // 0x38
	public DateTime expiresIn; // 0x40
	public Boolean isLatestUserAgreement; // 0x48
	public JObject captcha; // 0x50


	// RVA: 0x2f2a7c8 VA: 0x75955427c8
	public Void .ctor() { }
}
```