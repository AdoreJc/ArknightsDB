# CampaignZoneMapViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String id`

- `String name`

- `String zoneTemplateId`


## Properties

- `Boolean hasStage`


## Methods

- `Boolean get_hasStage()`

- `Void RefreshInfo()`

- `Void LoadData(String, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneMapViewModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public String zoneTemplateId; // 0x20
	public List`1 stageModels; // 0x28
	private static DelegateBridge __Hotfix0_get_hasStage; // 0x0
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean hasStage { get; }

	// RVA: 0x2ddf410 VA: 0x75953f7410
	public Boolean get_hasStage() { }
	// RVA: 0x2ddf49c VA: 0x75953f749c
	public Void RefreshInfo() { }
	// RVA: 0x2ddf644 VA: 0x75953f7644
	public Void LoadData(String zoneId, Dictionary`2 endTimeList) { }
	// RVA: 0x2ddfe3c VA: 0x75953f7e3c
	public Void .ctor() { }
}
```