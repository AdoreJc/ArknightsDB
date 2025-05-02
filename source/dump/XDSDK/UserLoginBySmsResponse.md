# UserLoginBySmsResponse

**Namespace:** `XDSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Boolean isAuthenticate`

- `Boolean isMinor`

- `Int64 issuedAt`

- `Int64 expiresIn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class UserLoginBySmsResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Boolean isAuthenticate; // 0x30
	public Boolean isMinor; // 0x31
	public Int64 issuedAt; // 0x38
	public Int64 expiresIn; // 0x40


	// RVA: 0x2589800 VA: 0x7594ba1800
	public Void .ctor() { }
}
```