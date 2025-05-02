# StageZoneGroupPanelHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneMixStoryGroupPanel _mixStoryGroup`

- `StageZoneWeeklyGroupPanel _weeklyGroup`

- `StageZoneHomeMainGroupPanel _homeGroup`

- `StageZoneCampaignGroupPanel _campaignGroup`

- `StageZonePermModeGroupPanel _permModeGroup`

- `StageZoneCrisisV2GroupPanel _crisisV2Group`


## Properties

- `StageZoneWeeklyGroupPanel weeklyGroupPrefab`

- `StageZoneHomeMainGroupPanel homeGroupPrefab`

- `StageZoneCampaignGroupPanel campaignGroupPrefab`

- `StageZoneMixStoryGroupPanel mixStoryGroupPrefab`

- `StageZonePermModeGroupPanel permModeGroupPrefab`

- `StageZoneCrisisV2GroupPanel crisisV2GroupPanel`


## Methods

- `StageZoneWeeklyGroupPanel get_weeklyGroupPrefab()`

- `StageZoneHomeMainGroupPanel get_homeGroupPrefab()`

- `StageZoneCampaignGroupPanel get_campaignGroupPrefab()`

- `StageZoneMixStoryGroupPanel get_mixStoryGroupPrefab()`

- `StageZonePermModeGroupPanel get_permModeGroupPrefab()`

- `StageZoneCrisisV2GroupPanel get_crisisV2GroupPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneGroupPanelHolder : MonoBehaviour, IHotfixable
{
	private StageZoneMixStoryGroupPanel _mixStoryGroup; // 0x18
	private StageZoneWeeklyGroupPanel _weeklyGroup; // 0x20
	private StageZoneHomeMainGroupPanel _homeGroup; // 0x28
	private StageZoneCampaignGroupPanel _campaignGroup; // 0x30
	private StageZonePermModeGroupPanel _permModeGroup; // 0x38
	private StageZoneCrisisV2GroupPanel _crisisV2Group; // 0x40
	private static DelegateBridge __Hotfix0_get_weeklyGroupPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_homeGroupPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_campaignGroupPrefab; // 0x10
	private static DelegateBridge __Hotfix0_get_mixStoryGroupPrefab; // 0x18
	private static DelegateBridge __Hotfix0_get_permModeGroupPrefab; // 0x20
	private static DelegateBridge __Hotfix0_get_crisisV2GroupPanel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public StageZoneWeeklyGroupPanel weeklyGroupPrefab { get; }
	public StageZoneHomeMainGroupPanel homeGroupPrefab { get; }
	public StageZoneCampaignGroupPanel campaignGroupPrefab { get; }
	public StageZoneMixStoryGroupPanel mixStoryGroupPrefab { get; }
	public StageZonePermModeGroupPanel permModeGroupPrefab { get; }
	public StageZoneCrisisV2GroupPanel crisisV2GroupPanel { get; }

	// RVA: 0x2fad2f0 VA: 0x75955c52f0
	public StageZoneWeeklyGroupPanel get_weeklyGroupPrefab() { }
	// RVA: 0x2fad358 VA: 0x75955c5358
	public StageZoneHomeMainGroupPanel get_homeGroupPrefab() { }
	// RVA: 0x2fad3c0 VA: 0x75955c53c0
	public StageZoneCampaignGroupPanel get_campaignGroupPrefab() { }
	// RVA: 0x2fad428 VA: 0x75955c5428
	public StageZoneMixStoryGroupPanel get_mixStoryGroupPrefab() { }
	// RVA: 0x2fad490 VA: 0x75955c5490
	public StageZonePermModeGroupPanel get_permModeGroupPrefab() { }
	// RVA: 0x2fad4f8 VA: 0x75955c54f8
	public StageZoneCrisisV2GroupPanel get_crisisV2GroupPanel() { }
	// RVA: 0x2fad560 VA: 0x75955c5560
	public Void .ctor() { }
}
```