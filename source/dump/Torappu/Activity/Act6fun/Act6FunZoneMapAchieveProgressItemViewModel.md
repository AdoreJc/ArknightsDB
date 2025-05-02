# Act6FunZoneMapAchieveProgressItemViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Single <progress>k__BackingField`

- `Int32 <maxCount>k__BackingField`


## Properties

- `Single progress`

- `Int32 maxCount`


## Methods

- `Single get_progress()`

- `Void set_progress(Single)`

- `Int32 get_maxCount()`

- `Void set_maxCount(Int32)`

- `Void LoadData(Int32)`

- `Void RefreshData(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchieveProgressItemViewModel : IHotfixable
{
	private Single <progress>k__BackingField; // 0x10
	private Int32 <maxCount>k__BackingField; // 0x14
	private static DelegateBridge __Hotfix0_get_progress; // 0x0
	private static DelegateBridge __Hotfix0_set_progress; // 0x8
	private static DelegateBridge __Hotfix0_get_maxCount; // 0x10
	private static DelegateBridge __Hotfix0_set_maxCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Single progress { get; set; }
	public Int32 maxCount { get; set; }

	// RVA: 0x31b1e54 VA: 0x75957c9e54
	public Single get_progress() { }
	// RVA: 0x31b1ebc VA: 0x75957c9ebc
	private Void set_progress(Single value) { }
	// RVA: 0x31b1f38 VA: 0x75957c9f38
	public Int32 get_maxCount() { }
	// RVA: 0x31b1fa0 VA: 0x75957c9fa0
	private Void set_maxCount(Int32 value) { }
	// RVA: 0x31b201c VA: 0x75957ca01c
	public Void LoadData(Int32 maxCnt) { }
	// RVA: 0x31b209c VA: 0x75957ca09c
	public Void RefreshData(Single itemProgress) { }
	// RVA: 0x31b212c VA: 0x75957ca12c
	public Void .ctor() { }
}
```