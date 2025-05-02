# Main12ZoneRecordGroupViewModel

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `ZoneRewardBuffViewModel rewardBuffModel`


## Properties

- `Boolean hasStageBanned`


## Methods

- `Boolean get_hasStageBanned()`

- `Void RefreshData(ZoneRecordGroupData)`

- `String GetRewardBuffItemId()`

- `Void <>xLuaBaseProxy_LoadData(ZoneRecordGroupData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12ZoneRecordGroupViewModel : ZoneRecordGroupViewModel, IHotfixable
{
	public ZoneRewardBuffViewModel rewardBuffModel; // 0x48
	private static DelegateBridge __Hotfix0_get_hasStageBanned; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_GetRewardBuffItemId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasStageBanned { get; }

	// RVA: 0x2fd47a0 VA: 0x75955ec7a0
	public Boolean get_hasStageBanned() { }
	// RVA: 0x2fd4890 VA: 0x75955ec890
	public override Void LoadData(ZoneRecordGroupData groupData) { }
	// RVA: 0x2fd3738 VA: 0x75955eb738
	public Void RefreshData(ZoneRecordGroupData groupData) { }
	// RVA: 0x2fd4608 VA: 0x75955ec608
	public String GetRewardBuffItemId() { }
	// RVA: 0x2fd495c VA: 0x75955ec95c
	public Void .ctor() { }
	// RVA: 0x2fd4a04 VA: 0x75955eca04
	private Void <>xLuaBaseProxy_LoadData(ZoneRecordGroupData P0) { }
}
```