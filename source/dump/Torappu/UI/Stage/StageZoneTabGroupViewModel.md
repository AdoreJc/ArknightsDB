# StageZoneTabGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneTabViewModel homeTab`

- `StageZoneTabViewModel weeklyTab`

- `StageZoneTabViewModel campaignTab`

- `StageZoneTabViewModel mixStoryTab`

- `StageSeasonTabViewModel crisisTab`

- `StagePermModeTabViewModel permModeTab`

- `Boolean isBlack`


## Methods

- `Void LoadData(StageStateBean)`

- `Void ReloadCrisisTab()`

- `Void ReloadCampaignTab()`

- `Void UpdateStatus(ZoneViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneTabGroupViewModel : IHotfixable
{
	public StageZoneTabViewModel homeTab; // 0x10
	public StageZoneTabViewModel weeklyTab; // 0x18
	public StageZoneTabViewModel campaignTab; // 0x20
	public StageZoneTabViewModel mixStoryTab; // 0x28
	public StageSeasonTabViewModel crisisTab; // 0x30
	public StagePermModeTabViewModel permModeTab; // 0x38
	public Boolean isBlack; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadSeasonTab; // 0x8
	private static DelegateBridge __Hotfix0__LoadCampaignTab; // 0x10
	private static DelegateBridge __Hotfix0__LoadPermModeTab; // 0x18
	private static DelegateBridge __Hotfix0__LoadMixStoryTab; // 0x20
	private static DelegateBridge __Hotfix0_ReloadCrisisTab; // 0x28
	private static DelegateBridge __Hotfix0_ReloadCampaignTab; // 0x30
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2fbcca0 VA: 0x75955d4ca0
	public Void LoadData(StageStateBean stageStateBean) { }
	// RVA: 0x2fbddc4 VA: 0x75955d5dc4
	private static StageSeasonTabViewModel _LoadSeasonTab() { }
	// RVA: 0x2fbdcf0 VA: 0x75955d5cf0
	private static StageCampaignTabViewModel _LoadCampaignTab() { }
	// RVA: 0x2fbdf58 VA: 0x75955d5f58
	private static StagePermModeTabViewModel _LoadPermModeTab() { }
	// RVA: 0x2fbdb4c VA: 0x75955d5b4c
	private static StageZoneTabViewModel _LoadMixStoryTab(StageStateBean stageStateBean) { }
	// RVA: 0x2fbe058 VA: 0x75955d6058
	public Void ReloadCrisisTab() { }
	// RVA: 0x2fbe0cc VA: 0x75955d60cc
	public Void ReloadCampaignTab() { }
	// RVA: 0x2fbd168 VA: 0x75955d5168
	public Void UpdateStatus(ZoneViewProperty selectedZoneProp) { }
	// RVA: 0x2fbd938 VA: 0x75955d5938
	public Void .ctor() { }
}
```