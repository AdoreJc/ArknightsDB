# StageZoneCampaignGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneCampaignView _campaignView`

- `StageZoneClimbTowerView _towerView`

- `StageZoneWeeklyRecordView _recordView`

- `StageZoneWeeklyRewardProperty _weeklyRewardProp`

- `Boolean m_inited`


## Methods

- `Void _EventOnClimbTowerClicked()`

- `Void _EventOnClimbTowerRotateClicked()`

- `Void _EventOnCampaignClicked()`

- `Void _EventOnCampaignRotateStageClicked()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneCampaignGroupPanel : StageZoneGroupPanel
{
	private StageZoneCampaignView _campaignView; // 0x60
	private StageZoneClimbTowerView _towerView; // 0x68
	private StageZoneWeeklyRecordView _recordView; // 0x70
	private StageZoneWeeklyRewardProperty _weeklyRewardProp; // 0x78
	private Boolean m_inited; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__EventOnClimbTowerClicked; // 0x10
	private static DelegateBridge __Hotfix0__EventOnClimbTowerRotateClicked; // 0x18
	private static DelegateBridge __Hotfix0__EventOnCampaignClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnCampaignRotateStageClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2fb1afc VA: 0x75955c9afc
	protected override Void OnEnter() { }
	// RVA: 0x2fb1f88 VA: 0x75955c9f88
	protected override Void OnDataUpdated(ZoneGroupViewProperty prop) { }
	// RVA: 0x2fb20e0 VA: 0x75955ca0e0
	private Void _EventOnClimbTowerClicked() { }
	// RVA: 0x2fb2274 VA: 0x75955ca274
	private Void _EventOnClimbTowerRotateClicked() { }
	// RVA: 0x2fb2460 VA: 0x75955ca460
	private Void _EventOnCampaignClicked() { }
	// RVA: 0x2fb25ac VA: 0x75955ca5ac
	private Void _EventOnCampaignRotateStageClicked() { }
	// RVA: 0x2fb1c28 VA: 0x75955c9c28
	private Void _InitIfNot() { }
	// RVA: 0x2fb2808 VA: 0x75955ca808
	public Void .ctor() { }
	// RVA: 0x2fb2944 VA: 0x75955ca944
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fb2948 VA: 0x75955ca948
	private Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty P0) { }
}
```