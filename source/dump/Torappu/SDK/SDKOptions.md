# SDKOptions

**Namespace:** `Torappu.SDK`


## Fields

- `Mode mode`

- `U8Options u8Options`

- `Configuration dev`

- `Configuration staging`

- `Configuration production`

- `Configuration business`


## Properties

- `Configuration currentConfig`


## Methods

- `Configuration get_currentConfig()`

- `Configuration _GetConfigurationByMode(Mode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKOptions : SingletonScriptableObject`1
{
	public Mode mode; // 0x18
	public U8Options u8Options; // 0x20
	public Configuration dev; // 0x28
	public Configuration staging; // 0x30
	public Configuration production; // 0x38
	public Configuration business; // 0x40

	public Configuration currentConfig { get; }
	public static Configuration configuration { get; }

	// RVA: 0x357d938 VA: 0x7595b95938
	public Configuration get_currentConfig() { }
	// RVA: 0x357d9b4 VA: 0x7595b959b4
	public static Configuration get_configuration() { }
	// RVA: 0x357d978 VA: 0x7595b95978
	private Configuration _GetConfigurationByMode(Mode mode) { }
	// RVA: 0x357da3c VA: 0x7595b95a3c
	public Void .ctor() { }
}
```