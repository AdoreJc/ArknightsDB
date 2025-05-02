# CampPreviewConfigModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String stageId`

- `AutoCampConfigModel autoBattleModel`


## Methods

- `Void SetSelectStage(CampaignStageMapViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampPreviewConfigModel : IHotfixable
{
	public String stageId; // 0x10
	public AutoCampConfigModel autoBattleModel; // 0x18
	private static DelegateBridge __Hotfix0_SetSelectStage; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2dddb50 VA: 0x75953f5b50
	public Void SetSelectStage(CampaignStageMapViewModel stageModel) { }
	// RVA: 0x2dddec8 VA: 0x75953f5ec8
	public Void .ctor() { }
}
```