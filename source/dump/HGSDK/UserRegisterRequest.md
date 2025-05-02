# UserRegisterRequest

**Namespace:** `HGSDK`


## Fields

- `String account`

- `String password`

- `String smsCode`

- `PlatformKey platform`

- `String deviceId`

- `String captcha`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class UserRegisterRequest
{
	public String account; // 0x10
	public String password; // 0x18
	public String smsCode; // 0x20
	public PlatformKey platform; // 0x28
	public String deviceId; // 0x30
	public String captcha; // 0x38


	// RVA: 0x2f210f4 VA: 0x75955390f4
	public Void .ctor() { }
}
```