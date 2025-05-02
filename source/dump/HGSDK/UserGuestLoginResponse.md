# UserGuestLoginResponse

**Namespace:** `HGSDK`


## Fields

- `Int32 result`

- `String message`

- `String uid`

- `Int32 role`

- `String token`

- `Int64 issueAt`

- `Int64 expiresIn`

- `Boolean isLatestUserAgreement`

- `String captchaTips`

- `JObject captcha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class UserGuestLoginResponse
{
	public Int32 result; // 0x10
	public String message; // 0x18
	public String uid; // 0x20
	public Int32 role; // 0x28
	public String token; // 0x30
	public Int64 issueAt; // 0x38
	public Int64 expiresIn; // 0x40
	public Boolean isLatestUserAgreement; // 0x48
	public String captchaTips; // 0x50
	public JObject captcha; // 0x58


	// RVA: 0x2f2a810 VA: 0x7595542810
	public Void .ctor() { }
}
```