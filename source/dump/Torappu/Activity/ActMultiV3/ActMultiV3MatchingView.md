# ActMultiV3MatchingView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CanvasGroup _rootPanel`

- `CanvasGroup _matchingPanel`

- `UIAnimationLocation _animMatchingEnter`

- `CanvasGroup _cancelPanel`

- `UIAnimationLocation _animCancelEnter`

- `CanvasGroup _timecountPanel`

- `UIAnimationLocation _animTimeoutEnter`

- `CanvasGroup _successPanel`

- `UIAnimationLocation _animSuccessEnter`

- `SimpleLayoutContent _modeList`

- `Single _panelFadeDuration`

- `Single _rootFadeDuratioin`

- `Text _textWaitSec`

- `Text _textTip`

- `Text _textSuccessDesc`

- `GameObject _partnerStudentGO`

- `GameObject _partnerCoachGO`

- `Int32 m_cacheSeqNum`

- `Tween m_tween`

- `FadeSwitchTween m_rootSwitchTween`

- `FadeSwitchTween m_matchingTween`

- `FadeSwitchTween m_cancelTween`

- `FadeSwitchTween m_timeoutTween`

- `FadeSwitchTween m_successTween`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `ModeListAdapter m_modeListAdapter`

- `ActMultiV3QuickMatchModel m_matchModel`

- `Int32 m_tipLastSec`


## Methods

- `Void _RenderSuccessView(ActMultiV3QuickMatchModel)`

- `Void _PlayMatchingAnimIfNeed(ActMultiV3QuickMatchModel)`

- `Void _RenderMatchingView(ActMultiV3QuickMatchModel)`

- `Void SetVisible(Boolean)`

- `Void _InitIfNot()`

- `FadeSwitchTween _CreateSwitchTween(CanvasGroup, Single)`

- `Void _PlayMatchingEnterAnim()`

- `Void _PlayResultAnim(ActMultiV3MatchResult)`

- `Void _OnDisablePanel()`

- `Void _OnResultShowCallback()`

- `Tween _CreateResultEnterTween(ActMultiV3MatchResult)`

- `Void EventOnBtnCancelClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchingView : DataBinder`1
{
	private CanvasGroup _rootPanel; // 0x20
	private CanvasGroup _matchingPanel; // 0x28
	private UIAnimationLocation _animMatchingEnter; // 0x30
	private CanvasGroup _cancelPanel; // 0x40
	private UIAnimationLocation _animCancelEnter; // 0x48
	private CanvasGroup _timecountPanel; // 0x58
	private UIAnimationLocation _animTimeoutEnter; // 0x60
	private CanvasGroup _successPanel; // 0x70
	private UIAnimationLocation _animSuccessEnter; // 0x78
	private SimpleLayoutContent _modeList; // 0x88
	private Single _panelFadeDuration; // 0x90
	private Single _rootFadeDuratioin; // 0x94
	private Text _textWaitSec; // 0x98
	private Text _textTip; // 0xa0
	private Text _textSuccessDesc; // 0xa8
	private GameObject _partnerStudentGO; // 0xb0
	private GameObject _partnerCoachGO; // 0xb8
	private Int32 m_cacheSeqNum; // 0xc0
	private Tween m_tween; // 0xc8
	private FadeSwitchTween m_rootSwitchTween; // 0xd0
	private FadeSwitchTween m_matchingTween; // 0xd8
	private FadeSwitchTween m_cancelTween; // 0xe0
	private FadeSwitchTween m_timeoutTween; // 0xe8
	private FadeSwitchTween m_successTween; // 0xf0
	private Boolean m_hasInited; // 0xf8
	private UIStateFinder m_stateFinder; // 0x100
	private ModeListAdapter m_modeListAdapter; // 0x110
	private ActMultiV3QuickMatchModel m_matchModel; // 0x118
	private Int32 m_tipLastSec; // 0x120
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderSuccessView; // 0x8
	private static DelegateBridge __Hotfix0__PlayMatchingAnimIfNeed; // 0x10
	private static DelegateBridge __Hotfix0__RenderMatchingView; // 0x18
	private static DelegateBridge __Hotfix0_SetVisible; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__CreateSwitchTween; // 0x30
	private static DelegateBridge __Hotfix0__PlayMatchingEnterAnim; // 0x38
	private static DelegateBridge __Hotfix0__PlayResultAnim; // 0x40
	private static DelegateBridge __Hotfix0__OnDisablePanel; // 0x48
	private static DelegateBridge __Hotfix0__OnResultShowCallback; // 0x50
	private static DelegateBridge __Hotfix0__CreateResultEnterTween; // 0x58
	private static DelegateBridge __Hotfix0_EventOnBtnCancelClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x31264a8 VA: 0x759573e4a8
	public override Void OnValueChanged(ActMultiV3QuickMatchProp property) { }
	// RVA: 0x31268c8 VA: 0x759573e8c8
	private Void _RenderSuccessView(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3126a48 VA: 0x759573ea48
	private Void _PlayMatchingAnimIfNeed(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x31266a0 VA: 0x759573e6a0
	private Void _RenderMatchingView(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3126fa8 VA: 0x759573efa8
	public Void SetVisible(Boolean isVisible) { }
	// RVA: 0x3126584 VA: 0x759573e584
	private Void _InitIfNot() { }
	// RVA: 0x31273d8 VA: 0x759573f3d8
	private FadeSwitchTween _CreateSwitchTween(CanvasGroup alphaHandler, Single duration) { }
	// RVA: 0x3126b68 VA: 0x759573eb68
	private Void _PlayMatchingEnterAnim() { }
	// RVA: 0x3126cc4 VA: 0x759573ecc4
	private Void _PlayResultAnim(ActMultiV3MatchResult matchResult) { }
	// RVA: 0x31275fc VA: 0x759573f5fc
	private Void _OnDisablePanel() { }
	// RVA: 0x3127668 VA: 0x759573f668
	private Void _OnResultShowCallback() { }
	// RVA: 0x31274c4 VA: 0x759573f4c4
	private Tween _CreateResultEnterTween(ActMultiV3MatchResult matchResult) { }
	// RVA: 0x3127764 VA: 0x759573f764
	public Void EventOnBtnCancelClick() { }
	// RVA: 0x3127808 VA: 0x759573f808
	public Void .ctor() { }
}
```