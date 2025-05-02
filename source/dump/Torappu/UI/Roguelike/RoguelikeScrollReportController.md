# RoguelikeScrollReportController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIRecycleLayoutGroup _content`

- `ScrollRect _scrollRect`

- `Graphic _longPressBlocker`

- `CanvasGroup _contentMask`

- `CanvasGroup _panelSkip`

- `CanvasGroup _panelBack`

- `CanvasGroup _panelBackForLogMode`

- `CanvasGroup _blackLoading`

- `Graphic _scrollBlocker`

- `CanvasGroup _panelFinish`

- `Single _actPlayDelay`

- `Adapter m_adapter`

- `ActPlayer m_activePlaying`

- `RoguelikeScrollReportPlugin m_reportPlugin`

- `FadeSwitchTween m_backTween`

- `FadeSwitchTween m_skipTween`

- `FadeSwitchTween m_backLogModeTween`

- `FadeSwitchTween m_contentMaskTween`

- `FadeSwitchTween m_blackLoaingTween`

- `StringBuilder m_sharedBuilder`

- `Boolean m_isLogMode`

- `VirtualView m_titleView`


## Methods

- `Void _SetupContent(Boolean)`

- `Void _StartPlayCoroutine()`

- `IEnumerator _PlayCoroutine()`

- `IEnumerator _ReloadWithLogMode()`

- `VirtualView _CreateTitleView(Single)`

- `VirtualView _CreateEndPadding(Single)`

- `IVirtualView _CreateCastView(EndingReportDisplayItem)`

- `VirtualView _CreateReportInitView(EndingReportDisplayItem)`

- `VirtualView _CreateReportSummaryView(EndingReportDisplayItem)`

- `VirtualView _CreateReportSummaryWithDifficultyView(EndingReportDisplayItem)`

- `VirtualView _CreateReportEndFailView(EndingReportDisplayItem)`

- `VirtualView _CreateReportZoneView(EndingReportDisplayItem)`

- `VirtualView _CreateReportNodeView(EndingReportDisplayItem)`

- `VirtualView _CreateReportEndView(EndingReportDisplayItem)`

- `IVirtualView _CreateZoneOverviewView(EndingReportDisplayItem)`

- `VirtualView _CreateSimpleDescView(EndingReportDisplayItem, RoguelikeScrollReportItemView)`

- `String _ConvertDescToString(IList`1)`

- `Void _TryInjectReportPlugin(String)`

- `Void _InjectViewModelPlugin()`

- `FadeSwitchTween _GetBackTween()`

- `FadeSwitchTween _GetSkipTween()`

- `FadeSwitchTween _GetBackLogModeTween()`

- `FadeSwitchTween _GetContentMaskTween()`

- `FadeSwitchTween _GetBlackLoadingTween()`

- `Boolean _CheckIfPlaying()`

- `Boolean _CheckIfSkipValid()`

- `Boolean _CheckIfBackValid()`

- `Boolean _CheckIfBackForLogModeAvail()`

- `Void _UpdateButtonStatus()`

- `Single _TryGetScreenHeight()`

- `Void _AddDetailViewsToList(IList`1)`

- `Void EventOnBackClicked()`

- `Void EventOnSkipClicked()`

- `Void EventOnLongPressing()`

- `Void EventOnLongPressCanceled()`

- `Void EventOnBackTop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeScrollReportController : RoguelikeReportController`1
{
	private UIRecycleLayoutGroup _content; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private Graphic _longPressBlocker; // 0x40
	private CanvasGroup _contentMask; // 0x48
	private CanvasGroup _panelSkip; // 0x50
	private CanvasGroup _panelBack; // 0x58
	private CanvasGroup _panelBackForLogMode; // 0x60
	private CanvasGroup _blackLoading; // 0x68
	private Graphic _scrollBlocker; // 0x70
	private CanvasGroup _panelFinish; // 0x78
	private Single _actPlayDelay; // 0x80
	private const Single CONTENT_FADE_DUR; // 0x0
	private const Single FINISH_FADE_DUR; // 0x0
	private Adapter m_adapter; // 0x88
	private ActPlayer m_activePlaying; // 0x90
	private RoguelikeScrollReportPlugin m_reportPlugin; // 0x98
	private FadeSwitchTween m_backTween; // 0xa0
	private FadeSwitchTween m_skipTween; // 0xa8
	private FadeSwitchTween m_backLogModeTween; // 0xb0
	private FadeSwitchTween m_contentMaskTween; // 0xb8
	private FadeSwitchTween m_blackLoaingTween; // 0xc0
	private StringBuilder m_sharedBuilder; // 0xc8
	private Boolean m_isLogMode; // 0xd0
	private VirtualView m_titleView; // 0xd8
	private List`1 m_detailList; // 0xe0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__SetupContent; // 0x8
	private static DelegateBridge __Hotfix0__CreateViewList; // 0x10
	private static DelegateBridge __Hotfix0__StartPlayCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__PlayCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__ReloadWithLogMode; // 0x28
	private static DelegateBridge __Hotfix0__CreateTitleView; // 0x30
	private static DelegateBridge __Hotfix0__CreateEndPadding; // 0x38
	private static DelegateBridge __Hotfix0__CreateCastView; // 0x40
	private static DelegateBridge __Hotfix0__CreateReportInitView; // 0x48
	private static DelegateBridge __Hotfix0__CreateReportSummaryView; // 0x50
	private static DelegateBridge __Hotfix0__CreateReportSummaryWithDifficultyView; // 0x58
	private static DelegateBridge __Hotfix0__CreateReportEndFailView; // 0x60
	private static DelegateBridge __Hotfix0__CreateReportZoneView; // 0x68
	private static DelegateBridge __Hotfix0__CreateReportNodeView; // 0x70
	private static DelegateBridge __Hotfix0__CreateReportEndView; // 0x78
	private static DelegateBridge __Hotfix0__CreateZoneOverviewView; // 0x80
	private static DelegateBridge __Hotfix0__CreateSimpleDescView; // 0x88
	private static DelegateBridge __Hotfix0__ConvertDescToString; // 0x90
	private static DelegateBridge __Hotfix0__TryInjectReportPlugin; // 0x98
	private static DelegateBridge __Hotfix0__InjectViewModelPlugin; // 0xa0
	private static DelegateBridge __Hotfix0__GetBackTween; // 0xa8
	private static DelegateBridge __Hotfix0__GetSkipTween; // 0xb0
	private static DelegateBridge __Hotfix0__GetBackLogModeTween; // 0xb8
	private static DelegateBridge __Hotfix0__GetContentMaskTween; // 0xc0
	private static DelegateBridge __Hotfix0__GetBlackLoadingTween; // 0xc8
	private static DelegateBridge __Hotfix0__CheckIfPlaying; // 0xd0
	private static DelegateBridge __Hotfix0__CheckIfSkipValid; // 0xd8
	private static DelegateBridge __Hotfix0__CheckIfBackValid; // 0xe0
	private static DelegateBridge __Hotfix0__CheckIfBackForLogModeAvail; // 0xe8
	private static DelegateBridge __Hotfix0__UpdateButtonStatus; // 0xf0
	private static DelegateBridge __Hotfix0__TryGetScreenHeight; // 0xf8
	private static DelegateBridge __Hotfix0__AddDetailViewsToList; // 0x100
	private static DelegateBridge __Hotfix0_OnClosePage; // 0x108
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x110
	private static DelegateBridge __Hotfix0_EventOnSkipClicked; // 0x118
	private static DelegateBridge __Hotfix0_EventOnLongPressing; // 0x120
	private static DelegateBridge __Hotfix0_EventOnLongPressCanceled; // 0x128
	private static DelegateBridge __Hotfix0_EventOnBackTop; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138


	// RVA: 0x2a824dc VA: 0x759509a4dc
	protected override Void OnInit() { }
	// RVA: 0x2a82cc8 VA: 0x759509acc8
	private Void _SetupContent(Boolean playMode) { }
	// RVA: 0x2a82f44 VA: 0x759509af44
	private IList`1 _CreateViewList(Boolean isPlayMode) { }
	// RVA: 0x2a82dcc VA: 0x759509adcc
	private Void _StartPlayCoroutine() { }
	// RVA: 0x2a83b08 VA: 0x759509bb08
	private IEnumerator _PlayCoroutine() { }
	// RVA: 0x2a83bdc VA: 0x759509bbdc
	private IEnumerator _ReloadWithLogMode() { }
	// RVA: 0x2a83458 VA: 0x759509b458
	private VirtualView _CreateTitleView(Single screenHeight) { }
	// RVA: 0x2a839bc VA: 0x759509b9bc
	private VirtualView _CreateEndPadding(Single screenHeight) { }
	// RVA: 0x2a8404c VA: 0x759509c04c
	private IVirtualView _CreateCastView(EndingReportDisplayItem item) { }
	// RVA: 0x2a84130 VA: 0x759509c130
	private VirtualView _CreateReportInitView(EndingReportDisplayItem item) { }
	// RVA: 0x2a84380 VA: 0x759509c380
	private VirtualView _CreateReportSummaryView(EndingReportDisplayItem item) { }
	// RVA: 0x2a844ac VA: 0x759509c4ac
	private VirtualView _CreateReportSummaryWithDifficultyView(EndingReportDisplayItem item) { }
	// RVA: 0x2a845d8 VA: 0x759509c5d8
	private VirtualView _CreateReportEndFailView(EndingReportDisplayItem item) { }
	// RVA: 0x2a84704 VA: 0x759509c704
	private VirtualView _CreateReportZoneView(EndingReportDisplayItem item) { }
	// RVA: 0x2a84d40 VA: 0x759509cd40
	private VirtualView _CreateReportNodeView(EndingReportDisplayItem item) { }
	// RVA: 0x2a851cc VA: 0x759509d1cc
	private VirtualView _CreateReportEndView(EndingReportDisplayItem item) { }
	// RVA: 0x2a854ec VA: 0x759509d4ec
	private IVirtualView _CreateZoneOverviewView(EndingReportDisplayItem item) { }
	// RVA: 0x2a8425c VA: 0x759509c25c
	private VirtualView _CreateSimpleDescView(EndingReportDisplayItem item, RoguelikeScrollReportItemView prefab) { }
	// RVA: 0x2a84ac8 VA: 0x759509cac8
	private String _ConvertDescToString(IList`1 strList) { }
	// RVA: 0x2a826c0 VA: 0x759509a6c0
	private Void _TryInjectReportPlugin(String topicId) { }
	// RVA: 0x2a82858 VA: 0x759509a858
	private Void _InjectViewModelPlugin() { }
	// RVA: 0x2a85778 VA: 0x759509d778
	private FadeSwitchTween _GetBackTween() { }
	// RVA: 0x2a85854 VA: 0x759509d854
	private FadeSwitchTween _GetSkipTween() { }
	// RVA: 0x2a85930 VA: 0x759509d930
	private FadeSwitchTween _GetBackLogModeTween() { }
	// RVA: 0x2a85a0c VA: 0x759509da0c
	private FadeSwitchTween _GetContentMaskTween() { }
	// RVA: 0x2a82be8 VA: 0x759509abe8
	private FadeSwitchTween _GetBlackLoadingTween() { }
	// RVA: 0x2a85ae8 VA: 0x759509dae8
	private Boolean _CheckIfPlaying() { }
	// RVA: 0x2a85b58 VA: 0x759509db58
	private Boolean _CheckIfSkipValid() { }
	// RVA: 0x2a85bc8 VA: 0x759509dbc8
	private Boolean _CheckIfBackValid() { }
	// RVA: 0x2a85c48 VA: 0x759509dc48
	private Boolean _CheckIfBackForLogModeAvail() { }
	// RVA: 0x2a82e74 VA: 0x759509ae74
	private Void _UpdateButtonStatus() { }
	// RVA: 0x2a83298 VA: 0x759509b298
	private Single _TryGetScreenHeight() { }
	// RVA: 0x2a8370c VA: 0x759509b70c
	private Void _AddDetailViewsToList(IList`1 outList) { }
	// RVA: 0x2a85cc8 VA: 0x759509dcc8
	protected override Void OnClosePage() { }
	// RVA: 0x2a85e64 VA: 0x759509de64
	public Void EventOnBackClicked() { }
	// RVA: 0x2a85ef4 VA: 0x759509def4
	public Void EventOnSkipClicked() { }
	// RVA: 0x2a85fe4 VA: 0x759509dfe4
	public Void EventOnLongPressing() { }
	// RVA: 0x2a860e4 VA: 0x759509e0e4
	public Void EventOnLongPressCanceled() { }
	// RVA: 0x2a86160 VA: 0x759509e160
	public Void EventOnBackTop() { }
	// RVA: 0x2a86208 VA: 0x759509e208
	public Void .ctor() { }
}
```