# SandboxV2WeatherData

**Namespace:** `Torappu`


## Fields

- `String weatherId`

- `String name`

- `Int32 weatherLevel`

- `SandboxV2WeatherType weatherType`

- `String weatherTypeName`

- `String weatherIconId`

- `String functionDesc`

- `String description`

- `String buffId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2WeatherData
{
	public String weatherId; // 0x10
	public String name; // 0x18
	public Int32 weatherLevel; // 0x20
	public SandboxV2WeatherType weatherType; // 0x24
	public String weatherTypeName; // 0x28
	public String weatherIconId; // 0x30
	public String functionDesc; // 0x38
	public String description; // 0x40
	public String buffId; // 0x48


	// RVA: 0x34b25f8 VA: 0x7595aca5f8
	public Void .ctor() { }
}
```