# UserRegisterResponse

**Namespace:** `HGSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Int64 issuedAt`

- `Int64 expiresIn`

- `String errMsg`

- `Boolean needAuthenticate`

- `Boolean isLatestUserAgreement`

- `JObject captcha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class UserRegisterResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Int64 issuedAt; // 0x30
	public Int64 expiresIn; // 0x38
	public String errMsg; // 0x40
	public Boolean needAuthenticate; // 0x48
	public Boolean isLatestUserAgreement; // 0x49
	public JObject captcha; // 0x50


	// RVA: 0x2f2a828 VA: 0x7595542828
	public Void .ctor() { }
}
```