# LoginResponse

**Namespace:** `XDSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Boolean isAuthenticate`

- `Boolean isMinor`

- `DateTime issuedAt`

- `DateTime expiresIn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class LoginResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Boolean isAuthenticate; // 0x30
	public Boolean isMinor; // 0x31
	public DateTime issuedAt; // 0x38
	public DateTime expiresIn; // 0x40


	// RVA: 0x25897b0 VA: 0x7594ba17b0
	public Void .ctor() { }
}
```