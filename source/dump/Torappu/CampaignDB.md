# CampaignDB

**Namespace:** `Torappu`


## Methods

- `Boolean BattleOnly_TryGetCampaign(String, out)`

- `Boolean SDCOnly_TryGetCampaign(String, out)`

- `Boolean SDCOnly_TryGetCampaignGroup(String, out)`

- `CampaignData GetCampaignData(String)`

- `CampaignZoneData GetZoneData(String)`

- `CampaignRegionData GetRegionData(String)`

- `CampaignRotateOpenTimeData GetRotateGroup(String)`

- `CampaignRotateOpenTimeData GetPreviousRotateGroup(String)`

- `CampaignTrainingOpenTimeData GetTrainingGroup(String)`

- `CampaignTrainingAllOpenTimeData GetTrainingAllOpenGroup(String)`

- `Boolean TryGetNextTrainingGroupOrAllOpenGroup(CampaignTrainingOpenTimeData, out, out)`

- `Boolean TryGetNextTrainingGroup(CampaignTrainingAllOpenTimeData, out)`

- `Int64 CalcTrainingGroupEndTs(CampaignTrainingOpenTimeData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CampaignDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_BattleOnly_TryGetCampaign; // 0x0
	private static DelegateBridge __Hotfix0_SDCOnly_TryGetCampaign; // 0x8
	private static DelegateBridge __Hotfix0_SDCOnly_TryGetCampaignGroup; // 0x10
	private static DelegateBridge __Hotfix0_GetCampaignData; // 0x18
	private static DelegateBridge __Hotfix0_GetZoneData; // 0x20
	private static DelegateBridge __Hotfix0_GetRegionData; // 0x28
	private static DelegateBridge __Hotfix0_GetRotateGroup; // 0x30
	private static DelegateBridge __Hotfix0_GetPreviousRotateGroup; // 0x38
	private static DelegateBridge __Hotfix0_GetTrainingGroup; // 0x40
	private static DelegateBridge __Hotfix0_GetTrainingAllOpenGroup; // 0x48
	private static DelegateBridge __Hotfix0_TryGetNextTrainingGroupOrAllOpenGroup; // 0x50
	private static DelegateBridge __Hotfix0_TryGetNextTrainingGroup; // 0x58
	private static DelegateBridge __Hotfix0_CalcTrainingGroupEndTs; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x31e8958 VA: 0x7595800958
	public Boolean BattleOnly_TryGetCampaign(String stageId, out CampaignData campaignData) { }
	// RVA: 0x31e8a24 VA: 0x7595800a24
	public Boolean SDCOnly_TryGetCampaign(String stageId, out CampaignData campaignData) { }
	// RVA: 0x31e8af0 VA: 0x7595800af0
	public Boolean SDCOnly_TryGetCampaignGroup(String campGroupId, out CampaignGroupData campGroupData) { }
	// RVA: 0x31e8bbc VA: 0x7595800bbc
	public CampaignData GetCampaignData(String stageId) { }
	// RVA: 0x31e8ca8 VA: 0x7595800ca8
	public CampaignZoneData GetZoneData(String zoneId) { }
	// RVA: 0x31e8d94 VA: 0x7595800d94
	public CampaignRegionData GetRegionData(String regionId) { }
	// RVA: 0x31e8e80 VA: 0x7595800e80
	public CampaignRotateOpenTimeData GetRotateGroup(String groupId) { }
	// RVA: 0x31e8fbc VA: 0x7595800fbc
	public CampaignRotateOpenTimeData GetPreviousRotateGroup(String curGroupId) { }
	// RVA: 0x31e9108 VA: 0x7595801108
	public CampaignTrainingOpenTimeData GetTrainingGroup(String groupId) { }
	// RVA: 0x31e9244 VA: 0x7595801244
	public CampaignTrainingAllOpenTimeData GetTrainingAllOpenGroup(String groupId) { }
	// RVA: 0x31e9380 VA: 0x7595801380
	public Boolean TryGetNextTrainingGroupOrAllOpenGroup(CampaignTrainingOpenTimeData curTrainingGroup, out CampaignTrainingOpenTimeData nextTrainingGroup, out CampaignTrainingAllOpenTimeData nextAllOpenGroup) { }
	// RVA: 0x31e95b8 VA: 0x75958015b8
	public Boolean TryGetNextTrainingGroup(CampaignTrainingAllOpenTimeData curAllOpenGroup, out CampaignTrainingOpenTimeData nextTrainingGroup) { }
	// RVA: 0x31e9724 VA: 0x7595801724
	public Int64 CalcTrainingGroupEndTs(CampaignTrainingOpenTimeData curTrainingGroup) { }
	// RVA: 0x31e97e8 VA: 0x75958017e8
	public Void .ctor() { }
}
```