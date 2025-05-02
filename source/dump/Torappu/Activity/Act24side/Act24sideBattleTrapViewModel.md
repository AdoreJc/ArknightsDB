# Act24sideBattleTrapViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <actId>k__BackingField`

- `Int32 <toolMaxCanTakeCount>k__BackingField`


## Properties

- `String actId`

- `Int32 toolMaxCanTakeCount`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Int32 get_toolMaxCanTakeCount()`

- `Void set_toolMaxCanTakeCount(Int32)`

- `Void LoadData(String)`

- `Void UpdateData()`

- `Int32 GetTempSelectCount()`

- `Boolean IsAllTrapLock()`

- `Act24sideBattleTrapItemViewModel GetTrapItemViewModelById(String)`

- `Void ConsumeAllNewUnlockTrack()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private Int32 <toolMaxCanTakeCount>k__BackingField; // 0x18
	public List`1 trapItemViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_toolMaxCanTakeCount; // 0x10
	private static DelegateBridge __Hotfix0_set_toolMaxCanTakeCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateData; // 0x28
	private static DelegateBridge __Hotfix0_GetTempSelectCount; // 0x30
	private static DelegateBridge __Hotfix0_GetTempSelectTrapIdList; // 0x38
	private static DelegateBridge __Hotfix0_IsAllTrapLock; // 0x40
	private static DelegateBridge __Hotfix0_GetTrapItemViewModelById; // 0x48
	private static DelegateBridge __Hotfix0_ConsumeAllNewUnlockTrack; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String actId { get; set; }
	public Int32 toolMaxCanTakeCount { get; set; }

	// RVA: 0x3295efc VA: 0x75958adefc
	public String get_actId() { }
	// RVA: 0x3297f40 VA: 0x75958aff40
	private Void set_actId(String value) { }
	// RVA: 0x3296d48 VA: 0x75958aed48
	public Int32 get_toolMaxCanTakeCount() { }
	// RVA: 0x3297fc4 VA: 0x75958affc4
	private Void set_toolMaxCanTakeCount(Int32 value) { }
	// RVA: 0x3295780 VA: 0x75958ad780
	public Void LoadData(String activityId) { }
	// RVA: 0x32959c8 VA: 0x75958ad9c8
	public Void UpdateData() { }
	// RVA: 0x3296c50 VA: 0x75958aec50
	public Int32 GetTempSelectCount() { }
	// RVA: 0x3295f64 VA: 0x75958adf64
	public List`1 GetTempSelectTrapIdList() { }
	// RVA: 0x329691c VA: 0x75958ae91c
	public Boolean IsAllTrapLock() { }
	// RVA: 0x3296a10 VA: 0x75958aea10
	public Act24sideBattleTrapItemViewModel GetTrapItemViewModelById(String trapId) { }
	// RVA: 0x3296200 VA: 0x75958ae200
	public Void ConsumeAllNewUnlockTrack() { }
	// RVA: 0x3298040 VA: 0x75958b0040
	public Void .ctor() { }
}
```