# PreQueueSelectPlugin

**Namespace:** ` `


## Fields

- `IntHashSet m_inPrequeChars`


## Methods

- `Boolean _CheckWillDormLockCharMove(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PreQueueSelectPlugin : Plugin`1
{
	private IntHashSet m_inPrequeChars; // 0x20

	public override String overrideNoCharText { get; }
	public override Boolean showCharInfoEntry { get; }
	public override BuildingStationSelectMaskPlugin cardMaskPrefab { get; }

	// RVA: 0x3d5b658 VA: 0x7596373658
	public override String get_overrideNoCharText() { }
	// RVA: 0x3d5b6a0 VA: 0x75963736a0
	public override Boolean get_showCharInfoEntry() { }
	// RVA: 0x3d5b6a8 VA: 0x75963736a8
	public override BuildingStationSelectMaskPlugin get_cardMaskPrefab() { }
	// RVA: 0x3d5b6f0 VA: 0x75963736f0
	public override Dictionary`2 LoadAllCharacters(RoomSlotModel targetRoom) { }
	// RVA: 0x3d5bd88 VA: 0x7596373d88
	public override Void OverrideCharSelect(StationCharViewModel selectChar, Action`1 selfCharSelect) { }
	// RVA: 0x3d5c060 VA: 0x7596374060
	public override Void OverrideDismiss(Action selfDismiss) { }
	// RVA: 0x3d5c080 VA: 0x7596374080
	public override Void OverrideSelectCanceled(Action selfCancel) { }
	// RVA: 0x3d5c0a0 VA: 0x75963740a0
	public override Void OverrideSelectConfirmed(Action selfConfirm) { }
	// RVA: 0x3d5c34c VA: 0x759637434c
	private Boolean _CheckWillDormLockCharMove(List`1 selectedChars) { }
	// RVA: 0x3d5c528 VA: 0x7596374528
	public override SelectResultModel OverrideGenerateSelectedCharsForRequest(Func`1 selfSelect) { }
	// RVA: 0x3d51ea0 VA: 0x7596369ea0
	public Void .ctor() { }
}
```