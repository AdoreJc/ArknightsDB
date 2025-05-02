# CampaignFastBattleStateBean

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String stageId`

- `CampaignStageType stageType`

- `FastCampaignConfirmViewModel confirmModel`


## Methods

- `Void LoadData(String, CampaignStageType)`

- `Void RefreshData()`

- `ConsumableInfo GetItemToCost()`

- `Boolean CheckIfCanStartBattle(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignFastBattleStateBean : IStateBean, IHotfixable
{
	public String stageId; // 0x10
	public CampaignStageType stageType; // 0x18
	public FastCampaignConfirmViewModel confirmModel; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_GetItemToCost; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfCanStartBattle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ddd5dc VA: 0x75953f55dc
	public Void LoadData(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2ddd89c VA: 0x75953f589c
	public Void RefreshData() { }
	// RVA: 0x2ddcf94 VA: 0x75953f4f94
	public ConsumableInfo GetItemToCost() { }
	// RVA: 0x2ddce88 VA: 0x75953f4e88
	public Boolean CheckIfCanStartBattle(out String alert) { }
	// RVA: 0x2ddd4b0 VA: 0x75953f54b0
	public Void .ctor() { }
}
```