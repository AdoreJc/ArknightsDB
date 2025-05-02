# Main10ZoneRecordGroupViewModel

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main10`


## Fields

- `StageDiffGroup <selectedDiffGroup>k__BackingField`


## Properties

- `StageDiffGroup selectedDiffGroup`


## Methods

- `StageDiffGroup get_selectedDiffGroup()`

- `Void set_selectedDiffGroup(StageDiffGroup)`

- `Void RefreshData(ZoneRecordGroupData)`

- `RecordRewardInfo GetCurrentRewardInfo()`

- `ZoneRecordRewardViewModel GetRewardViewModel(StageDiffGroup)`

- `Void <>xLuaBaseProxy_LoadData(ZoneRecordGroupData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main10
public class Main10ZoneRecordGroupViewModel : ZoneRecordGroupViewModel
{
	private StageDiffGroup <selectedDiffGroup>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_selectedDiffGroup; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedDiffGroup; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshData; // 0x18
	private static DelegateBridge __Hotfix0_GetCurrentRewardInfo; // 0x20
	private static DelegateBridge __Hotfix0_GetRewardViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public StageDiffGroup selectedDiffGroup { get; set; }

	// RVA: 0x2fe0258 VA: 0x75955f8258
	public StageDiffGroup get_selectedDiffGroup() { }
	// RVA: 0x2fdecf0 VA: 0x75955f6cf0
	public Void set_selectedDiffGroup(StageDiffGroup value) { }
	// RVA: 0x2fe02c0 VA: 0x75955f82c0
	public override Void LoadData(ZoneRecordGroupData groupData) { }
	// RVA: 0x2fde2ac VA: 0x75955f62ac
	public Void RefreshData(ZoneRecordGroupData groupData) { }
	// RVA: 0x2fe00b0 VA: 0x75955f80b0
	public RecordRewardInfo GetCurrentRewardInfo() { }
	// RVA: 0x2fe0358 VA: 0x75955f8358
	public ZoneRecordRewardViewModel GetRewardViewModel(StageDiffGroup diff) { }
	// RVA: 0x2fe0454 VA: 0x75955f8454
	public Void .ctor() { }
	// RVA: 0x2fe04c4 VA: 0x75955f84c4
	private Void <>xLuaBaseProxy_LoadData(ZoneRecordGroupData P0) { }
}
```