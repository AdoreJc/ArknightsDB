# ActivityTopBarHolder

**Namespace:** `Torappu.UI.Home`


## Fields

- `UIStringEvent _clickEvent`

- `ActivityTopBarView _actViewPrefab`

- `RectTransform _actScrollView`

- `Transform _actViewContainer`

- `TwoStateToggle _actExpandToggleBottom`

- `TwoStateToggle _actExpandToggleSide`

- `UICommonTrackPoint _actExpandTrackPoint`

- `CanvasGroup _expandGroup`

- `UIAnimationLocation _expandSideAnimLocation`

- `UIAnimationLocation _collapseSideAnimLocation`

- `Single _verticalExpandItemShowDelay`

- `Single _verticalExpandBtnShowBaseDuration`

- `Boolean m_isInited`

- `Boolean m_showCollapsedAct`

- `Int32 m_unfinishedActCount`

- `Int32 m_finishedActCount`

- `Single m_viewHeight`

- `Single m_firstViewWidth`

- `TrackPointViewProperty m_expandRedPoint`

- `ExpandSwitchTween m_switchTween`

- `Tween m_bottomExpandBtnTween`

- `Int32 m_showActCount`

- `Coroutine m_bottomExpandBtnCoroutine`

- `Int32 m_playingExpandItemNum`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1, List`1)`

- `Void ExpandSide(Boolean)`

- `Void ExpandBottom(Boolean)`

- `Void _OnActClicked(String)`

- `Void _OnSwitchTweenEnd()`

- `Void _OnSwitchTweenStart()`

- `Void OnDisable()`

- `Void _UpdateEntryViews(List`1, List`1)`

- `Void _RecomputeConfigList(List`1, List`1)`

- `Void _LoadConfigsFromActList(List`1, Boolean, Int32, ref)`

- `Void _RebuildEntryListIfNeeded(List`1, List`1)`

- `Boolean _DiffEntryConfigLists(List`1, List`1)`

- `Void _SetProperPrefabs()`

- `ActivityTopBarView _TryLoadProperPrefab(String, Int32)`

- `Void _RenderActivities(Boolean)`

- `Void _RenderActivitiesDirectly(List`1, Int32, Int32, Boolean, ref)`

- `IEnumerator _RenderActivitiesCoroutine(List`1, Int32, Int32, Boolean, Int32)`

- `Void _RenderExpandBtns(Boolean, Boolean)`

- `Void _SetExpandBtnsPos(Boolean, Int32)`

- `Single _CalculateHeight(Int32)`

- `ActShowType _JudgeShowType(EntryConfig, out)`

- `Void _ClearVerticalExpandAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class ActivityTopBarHolder : PageComponent
{
	private const Int32 MAX_SHOW_ACT; // 0x0
	private UIStringEvent _clickEvent; // 0x20
	private ActivityTopBarView _actViewPrefab; // 0x28
	private RectTransform _actScrollView; // 0x30
	private Transform _actViewContainer; // 0x38
	private TwoStateToggle _actExpandToggleBottom; // 0x40
	private TwoStateToggle _actExpandToggleSide; // 0x48
	private UICommonTrackPoint _actExpandTrackPoint; // 0x50
	private CanvasGroup _expandGroup; // 0x58
	private UIAnimationLocation _expandSideAnimLocation; // 0x60
	private UIAnimationLocation _collapseSideAnimLocation; // 0x70
	private Single _verticalExpandItemShowDelay; // 0x80
	private Single _verticalExpandBtnShowBaseDuration; // 0x84
	private Boolean m_isInited; // 0x88
	private Boolean m_showCollapsedAct; // 0x89
	private Int32 m_unfinishedActCount; // 0x8c
	private Int32 m_finishedActCount; // 0x90
	private Single m_viewHeight; // 0x94
	private Single m_firstViewWidth; // 0x98
	private List`1 m_oldConfigList; // 0xa0
	private List`1 m_newConfigList; // 0xa8
	private List`1 m_entryList; // 0xb0
	private TrackPointViewProperty m_expandRedPoint; // 0xb8
	private ExpandSwitchTween m_switchTween; // 0xc0
	private Tween m_bottomExpandBtnTween; // 0xc8
	private Int32 m_showActCount; // 0xd0
	private Coroutine m_bottomExpandBtnCoroutine; // 0xd8
	private Int32 m_playingExpandItemNum; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_ExpandSide; // 0x10
	private static DelegateBridge __Hotfix0_ExpandBottom; // 0x18
	private static DelegateBridge __Hotfix0__OnActClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnSwitchTweenEnd; // 0x28
	private static DelegateBridge __Hotfix0__OnSwitchTweenStart; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge __Hotfix0__UpdateEntryViews; // 0x40
	private static DelegateBridge __Hotfix0__RecomputeConfigList; // 0x48
	private static DelegateBridge __Hotfix0__LoadConfigsFromActList; // 0x50
	private static DelegateBridge __Hotfix0__RebuildEntryListIfNeeded; // 0x58
	private static DelegateBridge __Hotfix0__DiffEntryConfigLists; // 0x60
	private static DelegateBridge __Hotfix0__SetProperPrefabs; // 0x68
	private static DelegateBridge __Hotfix0__TryLoadProperPrefab; // 0x70
	private static DelegateBridge __Hotfix0__RenderActivities; // 0x78
	private static DelegateBridge __Hotfix0__RenderActivitiesDirectly; // 0x80
	private static DelegateBridge __Hotfix0__RenderActivitiesCoroutine; // 0x88
	private static DelegateBridge __Hotfix0__RenderExpandBtns; // 0x90
	private static DelegateBridge __Hotfix0__SetExpandBtnsPos; // 0x98
	private static DelegateBridge __Hotfix0__CalculateHeight; // 0xa0
	private static DelegateBridge __Hotfix0__JudgeShowType; // 0xa8
	private static DelegateBridge __Hotfix0__ClearVerticalExpandAnim; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8


	// RVA: 0x2821720 VA: 0x7594e39720
	private Void _InitIfNot() { }
	// RVA: 0x28218c0 VA: 0x7594e398c0
	public Void Render(List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x28219ec VA: 0x7594e399ec
	public Void ExpandSide(Boolean expand) { }
	// RVA: 0x2821a80 VA: 0x7594e39a80
	public Void ExpandBottom(Boolean expand) { }
	// RVA: 0x2821fac VA: 0x7594e39fac
	private Void _OnActClicked(String actId) { }
	// RVA: 0x2822064 VA: 0x7594e3a064
	private Void _OnSwitchTweenEnd() { }
	// RVA: 0x28220d8 VA: 0x7594e3a0d8
	private Void _OnSwitchTweenStart() { }
	// RVA: 0x2822148 VA: 0x7594e3a148
	private Void OnDisable() { }
	// RVA: 0x2821954 VA: 0x7594e39954
	private Void _UpdateEntryViews(List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x2822764 VA: 0x7594e3a764
	private Void _RecomputeConfigList(List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x2822854 VA: 0x7594e3a854
	private Void _LoadConfigsFromActList(List`1 actList, Boolean isFinished, Int32 offset, ref Int32 cnt) { }
	// RVA: 0x28222a8 VA: 0x7594e3a2a8
	private Void _RebuildEntryListIfNeeded(List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x2822d84 VA: 0x7594e3ad84
	private Boolean _DiffEntryConfigLists(List`1 unfinishedActs, List`1 finishedActs) { }
	// RVA: 0x2822b64 VA: 0x7594e3ab64
	private Void _SetProperPrefabs() { }
	// RVA: 0x2823144 VA: 0x7594e3b144
	private ActivityTopBarView _TryLoadProperPrefab(String actId, Int32 entryCount) { }
	// RVA: 0x2821b08 VA: 0x7594e39b08
	private Void _RenderActivities(Boolean fastMode) { }
	// RVA: 0x2823470 VA: 0x7594e3b470
	private Void _RenderActivitiesDirectly(List`1 showTypeList, Int32 startI, Int32 endI, Boolean fastMode, ref Int32 showTypeI) { }
	// RVA: 0x28236a4 VA: 0x7594e3b6a4
	private IEnumerator _RenderActivitiesCoroutine(List`1 showTypeList, Int32 startI, Int32 endI, Boolean fastMode, Int32 showTypeI) { }
	// RVA: 0x28237bc VA: 0x7594e3b7bc
	private Void _RenderExpandBtns(Boolean hasCollapsibleAct, Boolean hasUnfinishedAct) { }
	// RVA: 0x28238a4 VA: 0x7594e3b8a4
	private Void _SetExpandBtnsPos(Boolean fastMode, Int32 newShowCount) { }
	// RVA: 0x2823e64 VA: 0x7594e3be64
	private Single _CalculateHeight(Int32 activeCount) { }
	// RVA: 0x28232c8 VA: 0x7594e3b2c8
	private ActShowType _JudgeShowType(EntryConfig config, out Boolean inCollapsedList) { }
	// RVA: 0x28221b0 VA: 0x7594e3a1b0
	private Void _ClearVerticalExpandAnim() { }
	// RVA: 0x2824084 VA: 0x7594e3c084
	public Void .ctor() { }
}
```