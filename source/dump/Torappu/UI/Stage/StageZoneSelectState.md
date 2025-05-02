# StageZoneSelectState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageStateBean _stateBean`

- `StageZoneSelectBackground _background`

- `Transform _container`

- `StageZoneWeeklyGroupPanel m_weeklyGroup`

- `StageZoneHomeMainGroupPanel m_homeGroup`

- `StageZoneCampaignGroupPanel m_campaignGroup`

- `StageZoneMixStoryGroupPanel m_mixStoryGroup`

- `StageZonePermModeGroupPanel m_permModeGroup`

- `StageZoneCrisisV2GroupPanel m_crisisV2Group`

- `Boolean m_isInited`

- `MixStoryGroupViewProperty m_mixStoryGroupViewProperty`


## Methods

- `Void _InitedIfNot()`

- `T _InitZoneGroupPanel(T, Transform, List`1)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnMixStorySelectZone(String, String)`

- `Void _JumpToZone(String, String)`

- `Void _OnMixStorySelectRetro(String)`

- `Void _OnMixStoryFocusStorySet(String)`

- `Void _OnMixStoryFocusStoryline(String)`

- `Void _OnMixStoryFoldStorylines()`

- `Void _OnRoguelikeClicked()`

- `Void _OnRoguelikeEntryClicked()`

- `Void _OnSandboxClicked()`

- `Void _OnZoneSelected(ZoneGroupViewModel, ZoneViewModel)`

- `Void _SelectZone(String)`

- `Void _SetActEntryEffectEnable(Boolean)`

- `Void _Tutorial_TriggerRetroTutorialIfNeed()`

- `IEnumerator <>n__0()`

- `Void <get_cacheHandler>b__32_1(StateRuntime)`

- `IEnumerator <>xLuaBaseProxy_OnPreload()`

- `Void <>xLuaBaseProxy_OnResume()`

- `ITransAction <>xLuaBaseProxy_PickDynamicTransAction(State, TransitionType)`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneSelectState : StageTabBaseState, IValueMsgReceiver
{
	private const Single ZONE_GROUP_ANIM_DUR; // 0x0
	public const Int32 ON_ROGUELIKE_CLICKED; // 0x0
	public const Int32 ON_ROGUELIKE_ENTRY_CLICKED; // 0x0
	public const Int32 ON_SANDBOX_CLICKED; // 0x0
	public const Int32 ON_MIX_STORY_SELECT_ZONE; // 0x0
	public const Int32 ON_MIX_STORY_SELECT_RETRO; // 0x0
	public const Int32 ON_MIX_STORY_FOCUS_STORY_SET; // 0x0
	public const Int32 ON_MIX_STORY_FOCUS_STORYLINE; // 0x0
	public const Int32 ON_MIX_STORY_FOLD_STORYLINES; // 0x0
	private StageStateBean _stateBean; // 0x58
	private StageZoneSelectBackground _background; // 0x60
	private Transform _container; // 0x68
	private StageZoneWeeklyGroupPanel m_weeklyGroup; // 0x70
	private StageZoneHomeMainGroupPanel m_homeGroup; // 0x78
	private StageZoneCampaignGroupPanel m_campaignGroup; // 0x80
	private StageZoneMixStoryGroupPanel m_mixStoryGroup; // 0x88
	private StageZonePermModeGroupPanel m_permModeGroup; // 0x90
	private StageZoneCrisisV2GroupPanel m_crisisV2Group; // 0x98
	private List`1 m_zoneGroupPanels; // 0xa0
	private Boolean m_isInited; // 0xa8
	private MixStoryGroupViewProperty m_mixStoryGroupViewProperty; // 0xb0
	private StateCacheHandler`1 m_cacheHandler; // 0xb8
	private static DelegateBridge __Hotfix0__InitedIfNot; // 0x0
	private static DelegateBridge __Hotfix0__InitZoneGroupPanel; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnPreload; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_PickDynamicTransAction; // 0x28
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnMixStorySelectZone; // 0x40
	private static DelegateBridge __Hotfix0__JumpToZone; // 0x48
	private static DelegateBridge __Hotfix0__OnMixStorySelectRetro; // 0x50
	private static DelegateBridge __Hotfix0__OnMixStoryFocusStorySet; // 0x58
	private static DelegateBridge __Hotfix0__OnMixStoryFocusStoryline; // 0x60
	private static DelegateBridge __Hotfix0__OnMixStoryFoldStorylines; // 0x68
	private static DelegateBridge __Hotfix0__OnRoguelikeClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnRoguelikeEntryClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnSandboxClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnZoneSelected; // 0x88
	private static DelegateBridge __Hotfix0__SelectZone; // 0x90
	private static DelegateBridge __Hotfix0__SetActEntryEffectEnable; // 0x98
	private static DelegateBridge __Hotfix0__Tutorial_TriggerRetroTutorialIfNeed; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x2f700e0 VA: 0x75955880e0
	private Void _InitedIfNot() { }
	// RVA: 0x VA: 0x0
	private T _InitZoneGroupPanel(T prefab, Transform container, List`1 collector) { }
	// RVA: 0x2f70464 VA: 0x7595588464
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f704cc VA: 0x75955884cc
	protected override IEnumerator OnPreload() { }
	// RVA: 0x2f705a0 VA: 0x75955885a0
	protected override Void OnResume() { }
	// RVA: 0x2f706f0 VA: 0x75955886f0
	public override ITransAction PickDynamicTransAction(State otherState, TransitionType transType) { }
	// RVA: 0x2f708a8 VA: 0x75955888a8
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x2f70a98 VA: 0x7595588a98
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f712cc VA: 0x75955892cc
	private Void _OnMixStorySelectZone(String storySetId, String zoneId) { }
	// RVA: 0x2f71b00 VA: 0x7595589b00
	private Void _JumpToZone(String storySetId, String zoneId) { }
	// RVA: 0x2f71590 VA: 0x7595589590
	private Void _OnMixStorySelectRetro(String storySetId) { }
	// RVA: 0x2f71800 VA: 0x7595589800
	private Void _OnMixStoryFocusStorySet(String storySetId) { }
	// RVA: 0x2f7191c VA: 0x759558991c
	private Void _OnMixStoryFocusStoryline(String storylineId) { }
	// RVA: 0x2f71a38 VA: 0x7595589a38
	private Void _OnMixStoryFoldStorylines() { }
	// RVA: 0x2f70c94 VA: 0x7595588c94
	private Void _OnRoguelikeClicked() { }
	// RVA: 0x2f70e8c VA: 0x7595588e8c
	private Void _OnRoguelikeEntryClicked() { }
	// RVA: 0x2f71060 VA: 0x7595589060
	private Void _OnSandboxClicked() { }
	// RVA: 0x2f71edc VA: 0x7595589edc
	private Void _OnZoneSelected(ZoneGroupViewModel zoneGroup, ZoneViewModel zoneModel) { }
	// RVA: 0x2f71f88 VA: 0x7595589f88
	private Void _SelectZone(String zoneId) { }
	// RVA: 0x2f72148 VA: 0x759558a148
	private Void _SetActEntryEffectEnable(Boolean enable) { }
	// RVA: 0x2f71e20 VA: 0x7595589e20
	private Void _Tutorial_TriggerRetroTutorialIfNeed() { }
	// RVA: 0x2f72280 VA: 0x759558a280
	public Void .ctor() { }
	// RVA: 0x2f72340 VA: 0x759558a340
	private IEnumerator <>n__0() { }
	// RVA: 0x2f72348 VA: 0x759558a348
	private Void <get_cacheHandler>b__32_1(StateRuntime runtime) { }
	// RVA: 0x2f72470 VA: 0x759558a470
	private IEnumerator <>xLuaBaseProxy_OnPreload() { }
	// RVA: 0x2f72478 VA: 0x759558a478
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2f7247c VA: 0x759558a47c
	private ITransAction <>xLuaBaseProxy_PickDynamicTransAction(State P0, TransitionType P1) { }
	// RVA: 0x2f72484 VA: 0x759558a484
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
}
```