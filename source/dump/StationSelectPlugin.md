# StationSelectPlugin

**Namespace:** ` `


## Fields

- `IntHashSet m_inPrequeChars`


## Methods

- `Void _UpdateSelectedChars(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StationSelectPlugin : Plugin`1
{
	private List`1 m_cachedSelectedChars; // 0x20
	private HashSet`1 m_charAlreadySelectedMap; // 0x28
	private IntHashSet m_inPrequeChars; // 0x30

	public override String overrideNoCharText { get; }
	public override Boolean showCharInfoEntry { get; }
	public override BuildingStationSelectMaskPlugin cardMaskPrefab { get; }

	// RVA: 0x3d5a258 VA: 0x7596372258
	public override String get_overrideNoCharText() { }
	// RVA: 0x3d5a2a0 VA: 0x75963722a0
	public override Boolean get_showCharInfoEntry() { }
	// RVA: 0x3d5a2a8 VA: 0x75963722a8
	public override BuildingStationSelectMaskPlugin get_cardMaskPrefab() { }
	// RVA: 0x3d5a2f0 VA: 0x75963722f0
	public override Dictionary`2 LoadAllCharacters(RoomSlotModel targetRoom) { }
	// RVA: 0x3d5aa34 VA: 0x7596372a34
	public override Void OverrideCharSelect(StationCharViewModel selectChar, Action`1 selfCharSelect) { }
	// RVA: 0x3d5ad0c VA: 0x7596372d0c
	public override Void OverrideDismiss(Action selfDismiss) { }
	// RVA: 0x3d5ad2c VA: 0x7596372d2c
	public override Void OverrideSelectCanceled(Action selfCancel) { }
	// RVA: 0x3d5ad4c VA: 0x7596372d4c
	public override Void OverrideSelectConfirmed(Action selfConfirm) { }
	// RVA: 0x3d5ad6c VA: 0x7596372d6c
	public override SelectResultModel OverrideGenerateSelectedCharsForRequest(Func`1 selfSelect) { }
	// RVA: 0x3d5af08 VA: 0x7596372f08
	private Void _UpdateSelectedChars(List`1 selectedChars) { }
	// RVA: 0x3d51ab0 VA: 0x7596369ab0
	public Void .ctor() { }
}
```