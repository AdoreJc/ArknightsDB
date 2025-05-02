# StageMixStoryOverallView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIWrappedScrollRect _layoutScroll`

- `UIRecycleVerticalLayoutGroup _layoutGroup`

- `UILayoutDimensionListener _layoutDimensionListener`

- `Single _focusPositionFix`

- `StageMixStoryOverallGroupHeadComp _headCompPrefab`

- `StageMixStoryOverallGroupRowComp _rowCompPrefab`

- `CanvasGroup _switchGroup`

- `Single _switchHalfDuration`

- `UIAnimationLocation _sortModeSwitchAnimation`

- `Single _featureFadeHalfDuration`

- `UIStateFinder m_finder`

- `OverallViewStatus status`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Tween m_scrollPosTween`

- `AnimationSwitchTween m_sortModeSwitch`

- `Tween m_displayFeatureSwitch`

- `StageMixStoryOverallItemStateHandler m_itemStateHandler`

- `MixStoryZoneGroupViewModel m_cachedModel`

- `Int32 m_currentDataSequence`

- `Int32 m_storylineDataSequence`

- `Int32 m_releaseYearDataSequence`

- `OverallSortMode m_displayingSortMode`


## Properties

- `StageMixStoryOverallItemStateHandler itemStateHandler`


## Methods

- `StageMixStoryOverallItemStateHandler get_itemStateHandler()`

- `Void OnSwitchSortModeEvent()`

- `Void OnSwitchDisplayFeatureToDefault()`

- `Void OnSwitchDisplayFeatureToCoreReward()`

- `Void OnSwitchDisplayFeatureToStageProgress()`

- `Void _InitIfNot()`

- `Void _UpdateWithFade()`

- `Void _UpdateView()`

- `Void _UpdateStorylineViewsIfNeed()`

- `Void _UpdateReleaseYearViewsIfNeed()`

- `Void _AddStorySetsForVirtualView(List`1, List`1)`

- `Void _AppendRowVirtualView(List`1, out)`

- `Void _FocusStorySetIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallView : DataBinder`1
{
	private UIWrappedScrollRect _layoutScroll; // 0x20
	private UIRecycleVerticalLayoutGroup _layoutGroup; // 0x28
	private UILayoutDimensionListener _layoutDimensionListener; // 0x30
	private Single _focusPositionFix; // 0x38
	private StageMixStoryOverallGroupHeadComp _headCompPrefab; // 0x40
	private StageMixStoryOverallGroupRowComp _rowCompPrefab; // 0x48
	private CanvasGroup _switchGroup; // 0x50
	private Single _switchHalfDuration; // 0x58
	private List`1 _featureSwitches; // 0x60
	private UIAnimationLocation _sortModeSwitchAnimation; // 0x68
	private Single _featureFadeHalfDuration; // 0x78
	private UIStateFinder m_finder; // 0x80
	public OverallViewStatus status; // 0x90
	private Boolean m_hasInited; // 0xa8
	private Adapter m_adapter; // 0xb0
	private Tween m_scrollPosTween; // 0xb8
	private AnimationSwitchTween m_sortModeSwitch; // 0xc0
	private Tween m_displayFeatureSwitch; // 0xc8
	private StageMixStoryOverallItemStateHandler m_itemStateHandler; // 0xd0
	private readonly List`1 m_storylineViews; // 0xd8
	private readonly ListDict`2 m_releaseYearListDict; // 0xe0
	private readonly List`1 m_releaseYearViews; // 0xe8
	private MixStoryZoneGroupViewModel m_cachedModel; // 0xf0
	private Int32 m_currentDataSequence; // 0xf8
	private Int32 m_storylineDataSequence; // 0xfc
	private Int32 m_releaseYearDataSequence; // 0x100
	private OverallSortMode m_displayingSortMode; // 0x104
	private static DelegateBridge __Hotfix0_get_itemStateHandler; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnSwitchSortModeEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnSwitchDisplayFeatureToDefault; // 0x18
	private static DelegateBridge __Hotfix0_OnSwitchDisplayFeatureToCoreReward; // 0x20
	private static DelegateBridge __Hotfix0_OnSwitchDisplayFeatureToStageProgress; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__UpdateWithFade; // 0x38
	private static DelegateBridge __Hotfix0__UpdateView; // 0x40
	private static DelegateBridge __Hotfix0__UpdateStorylineViewsIfNeed; // 0x48
	private static DelegateBridge __Hotfix0__UpdateReleaseYearViewsIfNeed; // 0x50
	private static DelegateBridge __Hotfix0__SortReleaseYearList; // 0x58
	private static DelegateBridge __Hotfix0__SortStorySetWithinYear; // 0x60
	private static DelegateBridge __Hotfix0__AddStorySetsForVirtualView; // 0x68
	private static DelegateBridge __Hotfix0__AppendRowVirtualView; // 0x70
	private static DelegateBridge __Hotfix0__FocusStorySetIfNeed; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public StageMixStoryOverallItemStateHandler itemStateHandler { get; }

	// RVA: 0x2ffb238 VA: 0x7595613238
	public StageMixStoryOverallItemStateHandler get_itemStateHandler() { }
	// RVA: 0x2ffc220 VA: 0x7595614220
	public override Void OnValueChanged(ZoneGroupViewProperty property) { }
	// RVA: 0x2ffce5c VA: 0x7595614e5c
	public Void OnSwitchSortModeEvent() { }
	// RVA: 0x2ffcf10 VA: 0x7595614f10
	public Void OnSwitchDisplayFeatureToDefault() { }
	// RVA: 0x2ffd01c VA: 0x759561501c
	public Void OnSwitchDisplayFeatureToCoreReward() { }
	// RVA: 0x2ffd128 VA: 0x7595615128
	public Void OnSwitchDisplayFeatureToStageProgress() { }
	// RVA: 0x2ffc45c VA: 0x759561445c
	private Void _InitIfNot() { }
	// RVA: 0x2ffc698 VA: 0x7595614698
	private Void _UpdateWithFade() { }
	// RVA: 0x2ffc5c0 VA: 0x75956145c0
	private Void _UpdateView() { }
	// RVA: 0x2ffd2c8 VA: 0x75956152c8
	private Void _UpdateStorylineViewsIfNeed() { }
	// RVA: 0x2ffd658 VA: 0x7595615658
	private Void _UpdateReleaseYearViewsIfNeed() { }
	// RVA: 0x2ffe288 VA: 0x7595616288
	private static Int32 _SortReleaseYearList(KeyValuePair`2 x, KeyValuePair`2 y) { }
	// RVA: 0x2ffe338 VA: 0x7595616338
	private static Int32 _SortStorySetWithinYear(StageStorylineStorySetViewModel x, StageStorylineStorySetViewModel y) { }
	// RVA: 0x2ffde94 VA: 0x7595615e94
	private Void _AddStorySetsForVirtualView(List`1 target, List`1 storySets) { }
	// RVA: 0x2ffe410 VA: 0x7595616410
	private Void _AppendRowVirtualView(List`1 target, out List`1 list) { }
	// RVA: 0x2ffc900 VA: 0x7595614900
	private Void _FocusStorySetIfNeed() { }
	// RVA: 0x2ffe5dc VA: 0x75956165dc
	public Void .ctor() { }
}
```