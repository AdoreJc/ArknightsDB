# UserLoginBySmsResponse

**Namespace:** `HGSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Boolean isAuthenticate`

- `Boolean isMinor`

- `Boolean needAuthenticate`

- `Int64 issuedAt`

- `Int64 expiresIn`

- `Boolean isLatestUserAgreement`

- `JObject captcha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class UserLoginBySmsResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Boolean isAuthenticate; // 0x30
	public Boolean isMinor; // 0x31
	public Boolean needAuthenticate; // 0x32
	public Int64 issuedAt; // 0x38
	public Int64 expiresIn; // 0x40
	public Boolean isLatestUserAgreement; // 0x48
	public JObject captcha; // 0x50


	// RVA: 0x2f2a838 VA: 0x7595542838
	public Void .ctor() { }
}
```