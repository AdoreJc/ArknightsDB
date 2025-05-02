# RoguelikeClassicEndingController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeClassicEndingTopView _topViewPrefab`

- `RoguelikeClassicEndingSeedView _seedViewPrefab`

- `RectTransform _statsViewHolder`

- `RectTransform _scoreViewHolder`

- `RectTransform _topViewHolder`

- `RectTransform _seedViewHolder`

- `Image _imageBkg`

- `UIBlurFloatPanel _bpViewBlur`

- `RectTransform _bpAndGpViewContainer`

- `RoguelikeTopicEndingBpAndGpView _endingBpAndGpView`

- `String _failTitleId`

- `RoguelikeTopicEndingDataPluginBase _endingDataUtil`

- `RoguelikeClassicEndingPageViewBase m_statsView`

- `RoguelikeClassicEndingPageViewBase m_scoreView`

- `RoguelikeClassicEndingTopView m_topView`

- `RoguelikeClassicEndingSeedView m_seedView`

- `Boolean m_showLeftView`

- `Boolean m_hasShowReport`

- `Boolean m_hasAvgPlayed`

- `Boolean m_isRequested`

- `RoguelikeTopicEndingBpAndGpView m_endingBpAndGpView`

- `OuterData m_cachedOuterData`


## Methods

- `Void _RenderBasicView()`

- `Void _TriggerEndingAvgAndRecord(String)`

- `Void _ShowReport(Story)`

- `IEnumerator _ShowViewCoroutine(Boolean)`

- `IEnumerator _OpenReportCoroutine()`

- `IEnumerator _TryDismissSelfAndOpenTopicPage()`

- `Void _TryToOpenReport()`

- `Void _OnDismissBpView()`

- `Void _SendRequest(Action`1)`

- `Void _DoTrackTrigger()`

- `ViewType _GetScoreViewType(RoguelikeTopicMode)`

- `Void _EventOnStatsViewClick()`

- `Void _EventOnStatsScoreViewBackClick()`

- `Void _EventOnScoreViewBtnClick()`

- `Void _EventOnShowReportBtnClick()`

- `Void _EventOnCopySeed()`

- `Void EventBpViewDismissClick()`

- `Void <_OnDismissBpView>b__30_0()`

- `Void <_EventOnStatsViewClick>b__37_0(RoguelikeTopicGameSettleResponse)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingController : RoguelikeEndingController`1
{
	private RoguelikeClassicEndingPageViewBase[] _pageViewPrefabs; // 0x30
	private RoguelikeClassicEndingTopView _topViewPrefab; // 0x38
	private RoguelikeClassicEndingSeedView _seedViewPrefab; // 0x40
	private RectTransform _statsViewHolder; // 0x48
	private RectTransform _scoreViewHolder; // 0x50
	private RectTransform _topViewHolder; // 0x58
	private RectTransform _seedViewHolder; // 0x60
	private Image _imageBkg; // 0x68
	private UIBlurFloatPanel _bpViewBlur; // 0x70
	private RectTransform _bpAndGpViewContainer; // 0x78
	private RoguelikeTopicEndingBpAndGpView _endingBpAndGpView; // 0x80
	private String _failTitleId; // 0x88
	private RoguelikeTopicEndingDataPluginBase _endingDataUtil; // 0x90
	private RoguelikeClassicEndingPageViewBase m_statsView; // 0x98
	private RoguelikeClassicEndingPageViewBase m_scoreView; // 0xa0
	private RoguelikeClassicEndingTopView m_topView; // 0xa8
	private RoguelikeClassicEndingSeedView m_seedView; // 0xb0
	private Boolean m_showLeftView; // 0xb8
	private Boolean m_hasShowReport; // 0xb9
	private Boolean m_hasAvgPlayed; // 0xba
	private Boolean m_isRequested; // 0xbb
	private RoguelikeTopicEndingBpAndGpView m_endingBpAndGpView; // 0xc0
	private OuterData m_cachedOuterData; // 0xc8
	private static DelegateBridge __Hotfix0__RenderBasicView; // 0x0
	private static DelegateBridge __Hotfix0__TriggerEndingAvgAndRecord; // 0x8
	private static DelegateBridge __Hotfix0__ShowReport; // 0x10
	private static DelegateBridge __Hotfix0__ShowViewCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__OpenReportCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__TryDismissSelfAndOpenTopicPage; // 0x28
	private static DelegateBridge __Hotfix0__TryToOpenReport; // 0x30
	private static DelegateBridge __Hotfix0__OnDismissBpView; // 0x38
	private static DelegateBridge __Hotfix0__SendRequest; // 0x40
	private static DelegateBridge __Hotfix0__DoTrackTrigger; // 0x48
	private static DelegateBridge __Hotfix0__GetScoreViewType; // 0x50
	private static DelegateBridge __Hotfix0_ConstructViewModel; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x60
	private static DelegateBridge __Hotfix0_OnResume; // 0x68
	private static DelegateBridge __Hotfix0__EventOnStatsViewClick; // 0x70
	private static DelegateBridge __Hotfix0__EventOnStatsScoreViewBackClick; // 0x78
	private static DelegateBridge __Hotfix0__EventOnScoreViewBtnClick; // 0x80
	private static DelegateBridge __Hotfix0__EventOnShowReportBtnClick; // 0x88
	private static DelegateBridge __Hotfix0__EventOnCopySeed; // 0x90
	private static DelegateBridge __Hotfix0_EventBpViewDismissClick; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2a21ecc VA: 0x7595039ecc
	private Void _RenderBasicView() { }
	// RVA: 0x2a21ffc VA: 0x7595039ffc
	private Void _TriggerEndingAvgAndRecord(String triggerId) { }
	// RVA: 0x2a22154 VA: 0x759503a154
	private Void _ShowReport(Story story) { }
	// RVA: 0x2a2231c VA: 0x759503a31c
	private IEnumerator _ShowViewCoroutine(Boolean showLeftView) { }
	// RVA: 0x2a22270 VA: 0x759503a270
	private IEnumerator _OpenReportCoroutine() { }
	// RVA: 0x2a22434 VA: 0x759503a434
	private IEnumerator _TryDismissSelfAndOpenTopicPage() { }
	// RVA: 0x2a22508 VA: 0x759503a508
	private Void _TryToOpenReport() { }
	// RVA: 0x2a226a8 VA: 0x759503a6a8
	private Void _OnDismissBpView() { }
	// RVA: 0x2a228fc VA: 0x759503a8fc
	private Void _SendRequest(Action`1 action) { }
	// RVA: 0x2a22b24 VA: 0x759503ab24
	private Void _DoTrackTrigger() { }
	// RVA: 0x2a22c48 VA: 0x759503ac48
	private ViewType _GetScoreViewType(RoguelikeTopicMode mode) { }
	// RVA: 0x2a22ce0 VA: 0x759503ace0
	public override RoguelikeEndingViewModel ConstructViewModel(RoguelikeTopicMode mode) { }
	// RVA: 0x2a22ec0 VA: 0x759503aec0
	protected override Void OnInit() { }
	// RVA: 0x2a2356c VA: 0x759503b56c
	protected override Void OnResume() { }
	// RVA: 0x2a23700 VA: 0x759503b700
	private Void _EventOnStatsViewClick() { }
	// RVA: 0x2a23828 VA: 0x759503b828
	private Void _EventOnStatsScoreViewBackClick() { }
	// RVA: 0x2a238dc VA: 0x759503b8dc
	private Void _EventOnScoreViewBtnClick() { }
	// RVA: 0x2a23b34 VA: 0x759503bb34
	private Void _EventOnShowReportBtnClick() { }
	// RVA: 0x2a23b9c VA: 0x759503bb9c
	private Void _EventOnCopySeed() { }
	// RVA: 0x2a23cb0 VA: 0x759503bcb0
	public Void EventBpViewDismissClick() { }
	// RVA: 0x2a23d18 VA: 0x759503bd18
	public Void .ctor() { }
	// RVA: 0x2a23da8 VA: 0x759503bda8
	private Void <_OnDismissBpView>b__30_0() { }
	// RVA: 0x2a23df4 VA: 0x759503bdf4
	private Void <_EventOnStatsViewClick>b__37_0(RoguelikeTopicGameSettleResponse response) { }
	// RVA: 0x2a23ec0 VA: 0x759503bec0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```