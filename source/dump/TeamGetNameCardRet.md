# TeamGetNameCardRet

**Namespace:** ` `


## Fields

- `String <nameCardJson>k__BackingField`


## Properties

- `String nameCardJson`


## Methods

- `String get_nameCardJson()`

- `Void set_nameCardJson(String)`

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamGetNameCardRet : Protocol
{
	public const Int32 ID; // 0x0
	private String <nameCardJson>k__BackingField; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_nameCardJson; // 0x8
	private static DelegateBridge __Hotfix0_set_nameCardJson; // 0x10
	private static DelegateBridge __Hotfix0_OnRead; // 0x18

	public String nameCardJson { get; set; }

	// RVA: 0x359eda0 VA: 0x7595bb6da0
	public Void .ctor() { }
	// RVA: 0x359ee14 VA: 0x7595bb6e14
	public String get_nameCardJson() { }
	// RVA: 0x359ee7c VA: 0x7595bb6e7c
	private Void set_nameCardJson(String value) { }
	// RVA: 0x359ef00 VA: 0x7595bb6f00
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359eff8 VA: 0x7595bb6ff8
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```