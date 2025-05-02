# CampaignStageMapViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Boolean isAvail`

- `String id`

- `Boolean isClosed`

- `Boolean isUnlocked`

- `CampaignStageType stageType`

- `Stage stageInfo`

- `CampaignStateViewModel stateViewModel`

- `CampaignData campaignData`

- `Int64 endTime`


## Methods

- `Void RefreshData()`

- `Void LoadData(String, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignStageMapViewModel : IHotfixable
{
	public Boolean isAvail; // 0x10
	public String id; // 0x18
	public Boolean isClosed; // 0x20
	public Boolean isUnlocked; // 0x21
	public CampaignStageType stageType; // 0x24
	public Stage stageInfo; // 0x28
	public CampaignStateViewModel stateViewModel; // 0x30
	public CampaignData campaignData; // 0x38
	public Int64 endTime; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ddf55c VA: 0x75953f755c
	public Void RefreshData() { }
	// RVA: 0x2ddfba8 VA: 0x75953f7ba8
	public Void LoadData(String stageId, Int64 inputEndTime) { }
	// RVA: 0x2ddfb38 VA: 0x75953f7b38
	public Void .ctor() { }
}
```