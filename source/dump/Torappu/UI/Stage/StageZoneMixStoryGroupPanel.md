# StageZoneMixStoryGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageMixStoryBackgroundView _backgroundView`

- `Image _focusedStorylineAbbrImage`

- `Text _focusedStorylineNameText`

- `GameObject _focusLastVisitedPanel`

- `StageMixStoryLocationLayoutGroup _locationRecycleGroup`

- `UIWrappedScrollRect _locationScrollRect`

- `UILayoutDimensionListener _locationContentDimensionListener`

- `UIRecycleVerticalLayoutGroup _storylineRecycleGroup`

- `UIWrappedScrollRect _storylineScrollRect`

- `UILayoutDimensionListener _storylineContentDimensionListener`

- `Single _storylineFocusPosition`

- `Transform _storylineItemTrackPointHolder`

- `Transform _storylineItemFocusEffectHolder`

- `GameObject _storylineItemFocusEffect`

- `RectTransform _storylineItemRect`

- `RectTransform _storylineItemRootRect`

- `Single _storylineItemMoveDuration`

- `Ease _storylineItemMoveEase`

- `UIAnimationLocation _storylinesSelectAnimation`

- `UIAnimationLocation _locationsSwitchAnimation`

- `GameObject _tutorialStorylineItemPanel`

- `GameObject _tutorialLocationGroupPanel`

- `GameObject _tutorialSelectStorylineButton`

- `GameObject _tutorialOverallButton`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `StageMixStoryRecycleList m_locationRecycleList`

- `StageMixStoryRecycleList m_storylineRecycleList`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `StageMixStoryActView m_actView`

- `StageMixStoryActOtherLineView m_otherLineView`

- `StageMixStoryMainlineSplitView m_splitView`

- `StageMixStoryStorylineView m_storylineView`

- `StageMixStoryStorylineItemSyncHandler m_storylineItemSyncHandler`

- `Tween m_storylineItemMoveTween`

- `AnimationSwitchTween m_selectStorylineSwitchTween`

- `AnimationSwitchTween m_selectLocationSwitchTween`

- `GameObject m_storylineItemTrackPoint`

- `Boolean m_focusStorylineRequired`

- `Int32 m_dataSequence`

- `StageStorylineViewModel m_cachedFocusedStoryline`

- `StageStorylineStorySetLocationViewModel m_cachedFocusedLocation`

- `Boolean m_isLastVisitedStoryline`

- `String m_lastVisitedStorySetId`

- `String m_cachedAbbrIconId`

- `String m_skipFocusedStorySetId`

- `Boolean m_skipLayoutFocus`

- `Single m_tempFocusPosition`

- `GameObject m_firstVisibleStorySet`

- `VirtualView m_selectedVirtualView`

- `Boolean m_waitForStableViews`

- `Coroutine m_signalCoroutine`


## Properties

- `String skipFocusedStorySetId`


## Methods

- `Void set_skipFocusedStorySetId(String)`

- `Void _Tutorial_WaitToTriggerSignalIfNeed()`

- `IEnumerator _Tutorial_WaitToTriggerSignalCoroutine()`

- `Void _Tutorial_FocusSelectStorylineIfNeed()`

- `Void _Tutorial_RegisterStorylineVirtualViewAndTriggerSignal(VirtualView)`

- `Void _Tutorial_TriggerSelectStorylineSwitchEnd()`

- `Void OnOpenOverallEvent()`

- `Void OnSwitchStorylineSelection(Boolean)`

- `Void OnFocusLastVisitedStorySetEvent()`

- `Void _InitIfNot()`

- `Void _UpdateStorylines(MixStoryZoneGroupViewModel, Boolean)`

- `Void _UpdateLocations(MixStoryZoneGroupViewModel, Boolean)`

- `Void _GenerateStorylineViews(List`1)`

- `Void _GenerateLocationViews(StageStorylineViewModel)`

- `Void _RenderFocusedStorylineItem(MixStoryZoneGroupViewModel)`

- `Void _ReactOnStorylineSelectSwitch(Boolean)`

- `Single _GetStorylineNormalizedPosition(StageStorylineViewModel, out)`

- `Single _GetFocusedStorySetNormalizedPosition()`

- `Void _UpdateLastVisitedState(MixStoryZoneGroupViewModel)`

- `Void _OnItemLayoutStart()`

- `Void _OnItemLayout(IVirtualView, Single, Single)`

- `Void _OnItemLayoutEnd()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneMixStoryGroupPanel : StageZoneGroupPanel
{
	private StageMixStoryBackgroundView _backgroundView; // 0x60
	private Image _focusedStorylineAbbrImage; // 0x68
	private Text _focusedStorylineNameText; // 0x70
	private GameObject _focusLastVisitedPanel; // 0x78
	private StageMixStoryLocationLayoutGroup _locationRecycleGroup; // 0x80
	private UIWrappedScrollRect _locationScrollRect; // 0x88
	private UILayoutDimensionListener _locationContentDimensionListener; // 0x90
	private UIRecycleVerticalLayoutGroup _storylineRecycleGroup; // 0x98
	private UIWrappedScrollRect _storylineScrollRect; // 0xa0
	private UILayoutDimensionListener _storylineContentDimensionListener; // 0xa8
	private Single _storylineFocusPosition; // 0xb0
	private Transform _storylineItemTrackPointHolder; // 0xb8
	private Transform _storylineItemFocusEffectHolder; // 0xc0
	private GameObject _storylineItemFocusEffect; // 0xc8
	private RectTransform _storylineItemRect; // 0xd0
	private RectTransform _storylineItemRootRect; // 0xd8
	private Single _storylineItemMoveDuration; // 0xe0
	private Ease _storylineItemMoveEase; // 0xe4
	private UIAnimationLocation _storylinesSelectAnimation; // 0xe8
	private UIAnimationLocation _locationsSwitchAnimation; // 0xf8
	private List`1 _overallLockedObjects; // 0x108
	private List`1 _overallUnlockObjects; // 0x110
	private GameObject _tutorialStorylineItemPanel; // 0x118
	private GameObject _tutorialLocationGroupPanel; // 0x120
	private GameObject _tutorialSelectStorylineButton; // 0x128
	private GameObject _tutorialOverallButton; // 0x130
	private UIPageFinder m_pageFinder; // 0x138
	private UIStateFinder m_stateFinder; // 0x148
	private StageMixStoryRecycleList m_locationRecycleList; // 0x158
	private StageMixStoryRecycleList m_storylineRecycleList; // 0x160
	private Boolean m_hasInited; // 0x168
	private ILoadAsset m_iLoadAsset; // 0x170
	private StageMixStoryActView m_actView; // 0x178
	private StageMixStoryActOtherLineView m_otherLineView; // 0x180
	private StageMixStoryMainlineSplitView m_splitView; // 0x188
	private StageMixStoryStorylineView m_storylineView; // 0x190
	private StageMixStoryStorylineItemSyncHandler m_storylineItemSyncHandler; // 0x198
	private Tween m_storylineItemMoveTween; // 0x1a0
	private AnimationSwitchTween m_selectStorylineSwitchTween; // 0x1a8
	private AnimationSwitchTween m_selectLocationSwitchTween; // 0x1b0
	private GameObject m_storylineItemTrackPoint; // 0x1b8
	private Boolean m_focusStorylineRequired; // 0x1c0
	private Int32 m_dataSequence; // 0x1c4
	private List`1 m_locationViews; // 0x1c8
	private List`1 m_storylineViews; // 0x1d0
	private StageStorylineViewModel m_cachedFocusedStoryline; // 0x1d8
	private StageStorylineStorySetLocationViewModel m_cachedFocusedLocation; // 0x1e0
	private Boolean m_isLastVisitedStoryline; // 0x1e8
	private String m_lastVisitedStorySetId; // 0x1f0
	private String m_cachedAbbrIconId; // 0x1f8
	private String m_skipFocusedStorySetId; // 0x200
	private Boolean m_skipLayoutFocus; // 0x208
	private Single m_tempFocusPosition; // 0x20c
	private GameObject m_firstVisibleStorySet; // 0x210
	private VirtualView m_selectedVirtualView; // 0x218
	private Boolean m_waitForStableViews; // 0x220
	private Coroutine m_signalCoroutine; // 0x228
	private static DelegateBridge __Hotfix0_set_skipFocusedStorySetId; // 0x0
	private static DelegateBridge __Hotfix0__Tutorial_WaitToTriggerSignalIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__Tutorial_WaitToTriggerSignalCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__Tutorial_FocusSelectStorylineIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__Tutorial_RegisterStorylineVirtualViewAndTriggerSignal; // 0x20
	private static DelegateBridge __Hotfix0__Tutorial_TriggerSelectStorylineSwitchEnd; // 0x28
	private static DelegateBridge __Hotfix0_OnOpenOverallEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnSwitchStorylineSelection; // 0x38
	private static DelegateBridge __Hotfix0_OnFocusLastVisitedStorySetEvent; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__UpdateStorylines; // 0x60
	private static DelegateBridge __Hotfix0__UpdateLocations; // 0x68
	private static DelegateBridge __Hotfix0__GenerateStorylineViews; // 0x70
	private static DelegateBridge __Hotfix0__GenerateLocationViews; // 0x78
	private static DelegateBridge __Hotfix0__RenderFocusedStorylineItem; // 0x80
	private static DelegateBridge __Hotfix0__ReactOnStorylineSelectSwitch; // 0x88
	private static DelegateBridge __Hotfix0__GetStorylineNormalizedPosition; // 0x90
	private static DelegateBridge __Hotfix0__GetFocusedStorySetNormalizedPosition; // 0x98
	private static DelegateBridge __Hotfix0__UpdateLastVisitedState; // 0xa0
	private static DelegateBridge __Hotfix0__OnItemLayoutStart; // 0xa8
	private static DelegateBridge __Hotfix0__OnItemLayout; // 0xb0
	private static DelegateBridge __Hotfix0__OnItemLayoutEnd; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public String skipFocusedStorySetId { set; }

	// RVA: 0x2fb8370 VA: 0x75955d0370
	public Void set_skipFocusedStorySetId(String value) { }
	// RVA: 0x2fb83f4 VA: 0x75955d03f4
	private Void _Tutorial_WaitToTriggerSignalIfNeed() { }
	// RVA: 0x2fb85bc VA: 0x75955d05bc
	private IEnumerator _Tutorial_WaitToTriggerSignalCoroutine() { }
	// RVA: 0x2fb8690 VA: 0x75955d0690
	private Void _Tutorial_FocusSelectStorylineIfNeed() { }
	// RVA: 0x2fb8aac VA: 0x75955d0aac
	private Void _Tutorial_RegisterStorylineVirtualViewAndTriggerSignal(VirtualView virtualView) { }
	// RVA: 0x2fb8c6c VA: 0x75955d0c6c
	private Void _Tutorial_TriggerSelectStorylineSwitchEnd() { }
	// RVA: 0x2fb8d10 VA: 0x75955d0d10
	public Void OnOpenOverallEvent() { }
	// RVA: 0x2fb8d88 VA: 0x75955d0d88
	public Void OnSwitchStorylineSelection(Boolean on) { }
	// RVA: 0x2fb9144 VA: 0x75955d1144
	public Void OnFocusLastVisitedStorySetEvent() { }
	// RVA: 0x2fb9264 VA: 0x75955d1264
	protected override Void OnEnter() { }
	// RVA: 0x2fb9b94 VA: 0x75955d1b94
	protected override Void OnDataUpdated(ZoneGroupViewProperty prop) { }
	// RVA: 0x2fb94d4 VA: 0x75955d14d4
	private Void _InitIfNot() { }
	// RVA: 0x2fb9d14 VA: 0x75955d1d14
	private Void _UpdateStorylines(MixStoryZoneGroupViewModel model, Boolean dataRefreshed) { }
	// RVA: 0x2fb9e7c VA: 0x75955d1e7c
	private Void _UpdateLocations(MixStoryZoneGroupViewModel model, Boolean dataRefreshed) { }
	// RVA: 0x2fba3f0 VA: 0x75955d23f0
	private Void _GenerateStorylineViews(List`1 storylines) { }
	// RVA: 0x2fba8f4 VA: 0x75955d28f4
	private Void _GenerateLocationViews(StageStorylineViewModel lineViewModel) { }
	// RVA: 0x2fba08c VA: 0x75955d208c
	private Void _RenderFocusedStorylineItem(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fb8ea4 VA: 0x75955d0ea4
	private Void _ReactOnStorylineSelectSwitch(Boolean on) { }
	// RVA: 0x2fba60c VA: 0x75955d260c
	private Single _GetStorylineNormalizedPosition(StageStorylineViewModel storyline, out VirtualView focusedVirtualView) { }
	// RVA: 0x2fbae9c VA: 0x75955d2e9c
	private Single _GetFocusedStorySetNormalizedPosition() { }
	// RVA: 0x2fba2b8 VA: 0x75955d22b8
	private Void _UpdateLastVisitedState(MixStoryZoneGroupViewModel model) { }
	// RVA: 0x2fbb100 VA: 0x75955d3100
	private Void _OnItemLayoutStart() { }
	// RVA: 0x2fbb22c VA: 0x75955d322c
	private Void _OnItemLayout(IVirtualView view, Single pos, Single size) { }
	// RVA: 0x2fbb528 VA: 0x75955d3528
	private Void _OnItemLayoutEnd() { }
	// RVA: 0x2fbb590 VA: 0x75955d3590
	public Void .ctor() { }
	// RVA: 0x2fbb6fc VA: 0x75955d36fc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fbb700 VA: 0x75955d3700
	private Void <>xLuaBaseProxy_OnDataUpdated(ZoneGroupViewProperty P0) { }
}
```