# UserRegisterResponse

**Namespace:** `XDSDK`


## Fields

- `Int32 result`

- `String uid`

- `Int32 role`

- `String token`

- `Int64 issuedAt`

- `Int64 expiresIn`

- `String errMsg`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class UserRegisterResponse
{
	public Int32 result; // 0x10
	public String uid; // 0x18
	public Int32 role; // 0x20
	public String token; // 0x28
	public Int64 issuedAt; // 0x30
	public Int64 expiresIn; // 0x38
	public String errMsg; // 0x40


	// RVA: 0x25897f8 VA: 0x7594ba17f8
	public Void .ctor() { }
}
```