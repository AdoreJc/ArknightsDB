# SandboxV2DungeonReadArchiveItemModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <dayTitle>k__BackingField`

- `Int32 <day>k__BackingField`

- `Int32 <maxAp>k__BackingField`

- `Single <seasonShowAngle>k__BackingField`


## Properties

- `String dayTitle`

- `Int32 day`

- `Int32 maxAp`

- `Single seasonShowAngle`


## Methods

- `String get_dayTitle()`

- `Void set_dayTitle(String)`

- `Int32 get_day()`

- `Void set_day(Int32)`

- `Int32 get_maxAp()`

- `Void set_maxAp(Int32)`

- `Single get_seasonShowAngle()`

- `Void set_seasonShowAngle(Single)`

- `Void LoadData(Save, SandboxV2GameConst)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveItemModel : IHotfixable
{
	private String <dayTitle>k__BackingField; // 0x10
	private Int32 <day>k__BackingField; // 0x18
	private Int32 <maxAp>k__BackingField; // 0x1c
	private Single <seasonShowAngle>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_dayTitle; // 0x0
	private static DelegateBridge __Hotfix0_set_dayTitle; // 0x8
	private static DelegateBridge __Hotfix0_get_day; // 0x10
	private static DelegateBridge __Hotfix0_set_day; // 0x18
	private static DelegateBridge __Hotfix0_get_maxAp; // 0x20
	private static DelegateBridge __Hotfix0_set_maxAp; // 0x28
	private static DelegateBridge __Hotfix0_get_seasonShowAngle; // 0x30
	private static DelegateBridge __Hotfix0_set_seasonShowAngle; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String dayTitle { get; set; }
	public Int32 day { get; set; }
	public Int32 maxAp { get; set; }
	public Single seasonShowAngle { get; set; }

	// RVA: 0x252aa0c VA: 0x7594b42a0c
	public String get_dayTitle() { }
	// RVA: 0x252c9c8 VA: 0x7594b449c8
	private Void set_dayTitle(String value) { }
	// RVA: 0x252aa74 VA: 0x7594b42a74
	public Int32 get_day() { }
	// RVA: 0x252ca4c VA: 0x7594b44a4c
	private Void set_day(Int32 value) { }
	// RVA: 0x252add0 VA: 0x7594b42dd0
	public Int32 get_maxAp() { }
	// RVA: 0x252cac8 VA: 0x7594b44ac8
	private Void set_maxAp(Int32 value) { }
	// RVA: 0x252aadc VA: 0x7594b42adc
	public Single get_seasonShowAngle() { }
	// RVA: 0x252cb44 VA: 0x7594b44b44
	private Void set_seasonShowAngle(Single value) { }
	// RVA: 0x252cbc0 VA: 0x7594b44bc0
	public Void LoadData(Save saveInfo, SandboxV2GameConst gameConst) { }
	// RVA: 0x252cdd4 VA: 0x7594b44dd4
	public Void .ctor() { }
}
```