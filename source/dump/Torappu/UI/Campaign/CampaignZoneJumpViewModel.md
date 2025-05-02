# CampaignZoneJumpViewModel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignZoneMapViewModel zoneViewModel`

- `CampaignStageMapViewModel mapViewModel`

- `Boolean isNew`

- `Boolean hasRewardToGet`

- `Boolean getAllReward`


## Properties

- `CampaignStageType stageType`


## Methods

- `CampaignStageType get_stageType()`

- `Void RefreshInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneJumpViewModel
{
	public CampaignZoneMapViewModel zoneViewModel; // 0x10
	public CampaignStageMapViewModel mapViewModel; // 0x18
	public Boolean isNew; // 0x20
	public Boolean hasRewardToGet; // 0x21
	public Boolean getAllReward; // 0x22

	public CampaignStageType stageType { get; }

	// RVA: 0x2e4c84c VA: 0x759546484c
	public CampaignStageType get_stageType() { }
	// RVA: 0x2e4c868 VA: 0x7595464868
	public Void RefreshInfo() { }
	// RVA: 0x2e4c8cc VA: 0x75954648cc
	public Void .ctor() { }
}
```