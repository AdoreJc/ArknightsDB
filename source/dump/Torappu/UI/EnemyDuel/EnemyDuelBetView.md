# EnemyDuelBetView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _pnlBtnSkip`

- `GameObject _pnlWatching`

- `GameObject _pnlCountdown`

- `GameObject _pnlCountdownOut`

- `GameObject _pnlClock`

- `Scrollbar _progressBarCountdown`

- `RectTransform _rectTransformMark`

- `Text _textCountdown`

- `Text _textCountdownOut`

- `Text _textRoundCount`

- `EnemyDuelBetSideView _leftSideView`

- `EnemyDuelBetSideView _rightSideView`

- `GameObject _fxBoom`

- `Text _textDesc`

- `Text _textDescPrivate`

- `CanvasGroup _canvasClock`

- `UIAnimationLocation _animClockLoop`

- `UIAnimationLocation _animCountdownTextLoop`

- `UIAnimationLocation _animPlayerListShow`

- `UIAtlasImage _imgProgressBar`

- `Color _colorProgressBarPrivateBet`

- `GameObject _enemyDetailPnlRaycast`

- `PrefabInstHolder _topBarInstHolder`

- `StandModeTips _standModeTips`

- `GameObject _pnlBetBtnOperation`

- `GameObject _pnlBetBtnStand`

- `PnlTopOperation _pnlOperation`

- `PnlTopStand _pnlStand`

- `GameObject _pnlSword`

- `EnemyDuelBetViewModel m_cachedViewModel`

- `PrivateBetShowTween m_privateBetShowTween`

- `UISwitchTween m_playerListShowTween`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedLoadSeqNum`

- `CountDownStopWatch m_stopWatch`

- `EnemyDuelBetTopBarView m_topBarView`


## Methods

- `Void _InitIfNot()`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void _UpdateCountdown(Boolean)`

- `Void StopTickLoopTween()`

- `Void OnBtnEnemyDetailRaycastClicked()`

- `Void <_InitIfNot>b__44_0(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetView : DataBinder`1, ITimeWatcher
{
	private const Int32 MAX_BET_ROUND_COUNT; // 0x0
	private GameObject _pnlBtnSkip; // 0x20
	private GameObject _pnlWatching; // 0x28
	private GameObject _pnlCountdown; // 0x30
	private GameObject _pnlCountdownOut; // 0x38
	private GameObject _pnlClock; // 0x40
	private Scrollbar _progressBarCountdown; // 0x48
	private RectTransform _rectTransformMark; // 0x50
	private Text _textCountdown; // 0x58
	private Text _textCountdownOut; // 0x60
	private Text _textRoundCount; // 0x68
	private EnemyDuelBetSideView _leftSideView; // 0x70
	private EnemyDuelBetSideView _rightSideView; // 0x78
	private GameObject[] _spacingBet; // 0x80
	private AbstractEnemyDuelBetButton[] _betButtons; // 0x88
	private GameObject _fxBoom; // 0x90
	private Text _textDesc; // 0x98
	private Text _textDescPrivate; // 0xa0
	private CanvasGroup _canvasClock; // 0xa8
	private UIAnimationLocation _animClockLoop; // 0xb0
	private UIAnimationLocation _animCountdownTextLoop; // 0xc0
	private UIAnimationLocation _animPlayerListShow; // 0xd0
	private UIAtlasImage _imgProgressBar; // 0xe0
	private Color _colorProgressBarPrivateBet; // 0xe8
	private GameObject _enemyDetailPnlRaycast; // 0xf8
	private PrefabInstHolder _topBarInstHolder; // 0x100
	private StandModeTips _standModeTips; // 0x108
	private GameObject _pnlBetBtnOperation; // 0x110
	private GameObject _pnlBetBtnStand; // 0x118
	private PnlTopOperation _pnlOperation; // 0x120
	private PnlTopStand _pnlStand; // 0x128
	private GameObject _pnlSword; // 0x130
	private EnemyDuelBetViewModel m_cachedViewModel; // 0x138
	private PrivateBetShowTween m_privateBetShowTween; // 0x140
	private UISwitchTween m_playerListShowTween; // 0x148
	private Boolean m_inited; // 0x150
	private UIStateFinder m_stateFinder; // 0x158
	private Int32 m_cachedLoadSeqNum; // 0x168
	private CountDownStopWatch m_stopWatch; // 0x170
	private EnemyDuelBetTopBarView m_topBarView; // 0x178
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x18
	private static DelegateBridge __Hotfix0__UpdateCountdown; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_StopTickLoopTween; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnEnemyDetailRaycastClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x297fd04 VA: 0x7594f97d04
	private Void _InitIfNot() { }
	// RVA: 0x297ff38 VA: 0x7594f97f38
	private Void Start() { }
	// RVA: 0x297ffa8 VA: 0x7594f97fa8
	private Void OnDestroy() { }
	// RVA: 0x29800b0 VA: 0x7594f980b0
	public Void UpdateTime(Single timeDelta) { }
	// RVA: 0x2980130 VA: 0x7594f98130
	private Void _UpdateCountdown(Boolean isInit) { }
	// RVA: 0x2980424 VA: 0x7594f98424
	public override Void OnValueChanged(EnemyDuelBetProperty property) { }
	// RVA: 0x297d6c8 VA: 0x7594f956c8
	public Void StopTickLoopTween() { }
	// RVA: 0x29810e0 VA: 0x7594f990e0
	public Void OnBtnEnemyDetailRaycastClicked() { }
	// RVA: 0x2981194 VA: 0x7594f99194
	public Void .ctor() { }
	// RVA: 0x2981260 VA: 0x7594f99260
	private Void <_InitIfNot>b__44_0(GameObject obj) { }
}
```