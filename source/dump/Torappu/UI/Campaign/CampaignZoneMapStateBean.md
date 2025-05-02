# CampaignZoneMapStateBean

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String zoneId`

- `CampaignZoneMapViewModel zoneViewModel`

- `CampaignZoneJumpViewModel jumpViewModel`

- `CampaignSelectStageViewProperty property`


## Methods

- `CampaignStageMapViewModel GetSelectedStage()`

- `Boolean CheckIfAutoBattle()`

- `Boolean CheckIfFastBattle()`

- `Void RefreshCampaignZoneData(String)`

- `Void SetSelectedStage(String)`

- `Boolean CheckIfToTriggerFastBattleGuide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public String zoneId; // 0x18
	public CampaignZoneMapViewModel zoneViewModel; // 0x20
	public CampaignZoneJumpViewModel jumpViewModel; // 0x28
	public CampaignSelectStageViewProperty property; // 0x30
	private static DelegateBridge __Hotfix0_GetSelectedStage; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfAutoBattle; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfFastBattle; // 0x10
	private static DelegateBridge __Hotfix0_RefreshCampaignZoneData; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectedStage; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfToTriggerFastBattleGuide; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2e50d58 VA: 0x7595468d58
	public CampaignStageMapViewModel GetSelectedStage() { }
	// RVA: 0x2e51208 VA: 0x7595469208
	public Boolean CheckIfAutoBattle() { }
	// RVA: 0x2e5011c VA: 0x759546811c
	public Boolean CheckIfFastBattle() { }
	// RVA: 0x2e51fd0 VA: 0x7595469fd0
	public Void RefreshCampaignZoneData(String zoneId) { }
	// RVA: 0x2e50b90 VA: 0x7595468b90
	public Void SetSelectedStage(String stageId) { }
	// RVA: 0x2e51850 VA: 0x7595469850
	public Boolean CheckIfToTriggerFastBattleGuide() { }
	// RVA: 0x2e525ec VA: 0x759546a5ec
	public Void .ctor() { }
}
```