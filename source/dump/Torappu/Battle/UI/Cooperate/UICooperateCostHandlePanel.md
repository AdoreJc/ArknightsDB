# UICooperateCostHandlePanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Button _requestButton`

- `CanvasGroup _requestButtonWindow`

- `CanvasGroup _requestWaitImage`

- `CanvasGroup _requestResponse`

- `CanvasGroup _costShowWindow`

- `CanvasGroup _waitShowWindow`

- `CanvasGroup _waitRejectWindow`

- `CanvasGroup _waitIgnoreWindow`

- `CanvasGroup _forbidWindow`

- `Slider _requestWaitSlider`

- `Slider _requestResponseSlider`

- `Text _requestCnt`

- `Text _addCost`

- `Text _waitTime`

- `Graphic _responseMask`

- `Graphic _pauseMask`

- `Graphic _rejectMask`

- `AnimationWrapper _costAcceptWrapper`

- `AnimationWrapper _costResponseWrapper`

- `CostState m_state`

- `Boolean m_isPlayerCostMax`

- `Boolean isPlayerDie`

- `Int32 m_costIgnoredTime`

- `FP m_costCDTime`


## Properties

- `AnimationWrapper costResponseWrapper`

- `AnimationWrapper costAcceptWrapper`

- `Button requestButton`

- `CanvasGroup requestButtonWindow`

- `CanvasGroup requestWaitImage`

- `CanvasGroup requestResponse`

- `CanvasGroup costShowWindow`

- `CanvasGroup waitShowWindow`

- `CanvasGroup waitRejectWindow`

- `CanvasGroup waitIgnoreWindow`

- `CanvasGroup forbidWindow`

- `Slider requestWaitSlider`

- `Slider requestResponseSlider`

- `Text requestCnt`

- `Text addCost`

- `Text waitTime`

- `Graphic responseMask`

- `Graphic pauseMask`

- `Graphic rejectMask`


## Methods

- `AnimationWrapper get_costResponseWrapper()`

- `AnimationWrapper get_costAcceptWrapper()`

- `Button get_requestButton()`

- `CanvasGroup get_requestButtonWindow()`

- `CanvasGroup get_requestWaitImage()`

- `CanvasGroup get_requestResponse()`

- `CanvasGroup get_costShowWindow()`

- `CanvasGroup get_waitShowWindow()`

- `CanvasGroup get_waitRejectWindow()`

- `CanvasGroup get_waitIgnoreWindow()`

- `CanvasGroup get_forbidWindow()`

- `Slider get_requestWaitSlider()`

- `Slider get_requestResponseSlider()`

- `Text get_requestCnt()`

- `Text get_addCost()`

- `Text get_waitTime()`

- `Graphic get_responseMask()`

- `Graphic get_pauseMask()`

- `Graphic get_rejectMask()`

- `Void InitPanel()`

- `Boolean CanRequestCost()`

- `Void OnReceiveCostRequest(Object)`

- `Void _SwitchToState(CostState, FP)`

- `Void _RegisterState(CostState, CostPanelState)`

- `Void OnFixUpdate(FP)`

- `Void OnUpdate()`

- `Void OnCostRequestButtonClicked()`

- `Void OnCostAcceptButtonClicked()`

- `Void OnCostRejectButtonClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateCostHandlePanel : MonoBehaviour, IHotfixable
{
	private static readonly FP COST_REQUEST_WAIT; // 0x0
	private static readonly FP RESULT_SHOW_WAIT; // 0x8
	private static readonly FP COST_CD_SHORT; // 0x10
	private static readonly FP COST_CD_LONG; // 0x18
	private const Single STATE_TWEEN_TIME; // 0x0
	private const String COST_AUDIO; // 0x0
	private const String ANIM_ACCEPT; // 0x0
	private const String ANIM_RESPONSE; // 0x0
	private Button _requestButton; // 0x18
	private CanvasGroup _requestButtonWindow; // 0x20
	private CanvasGroup _requestWaitImage; // 0x28
	private CanvasGroup _requestResponse; // 0x30
	private CanvasGroup _costShowWindow; // 0x38
	private CanvasGroup _waitShowWindow; // 0x40
	private CanvasGroup _waitRejectWindow; // 0x48
	private CanvasGroup _waitIgnoreWindow; // 0x50
	private CanvasGroup _forbidWindow; // 0x58
	private Slider _requestWaitSlider; // 0x60
	private Slider _requestResponseSlider; // 0x68
	private Text _requestCnt; // 0x70
	private Text _addCost; // 0x78
	private Text _waitTime; // 0x80
	private Graphic _responseMask; // 0x88
	private Graphic _pauseMask; // 0x90
	private Graphic _rejectMask; // 0x98
	private AnimationWrapper _costAcceptWrapper; // 0xa0
	private AnimationWrapper _costResponseWrapper; // 0xa8
	private CostState m_state; // 0xb0
	private Boolean m_isPlayerCostMax; // 0xb4
	public Boolean isPlayerDie; // 0xb5
	private Int32 m_costIgnoredTime; // 0xb8
	private FP m_costCDTime; // 0xc0
	private Dictionary`2 m_states; // 0xc8
	private static DelegateBridge __Hotfix0_get_costResponseWrapper; // 0x20
	private static DelegateBridge __Hotfix0_get_costAcceptWrapper; // 0x28
	private static DelegateBridge __Hotfix0_get_requestButton; // 0x30
	private static DelegateBridge __Hotfix0_get_requestButtonWindow; // 0x38
	private static DelegateBridge __Hotfix0_get_requestWaitImage; // 0x40
	private static DelegateBridge __Hotfix0_get_requestResponse; // 0x48
	private static DelegateBridge __Hotfix0_get_costShowWindow; // 0x50
	private static DelegateBridge __Hotfix0_get_waitShowWindow; // 0x58
	private static DelegateBridge __Hotfix0_get_waitRejectWindow; // 0x60
	private static DelegateBridge __Hotfix0_get_waitIgnoreWindow; // 0x68
	private static DelegateBridge __Hotfix0_get_forbidWindow; // 0x70
	private static DelegateBridge __Hotfix0_get_requestWaitSlider; // 0x78
	private static DelegateBridge __Hotfix0_get_requestResponseSlider; // 0x80
	private static DelegateBridge __Hotfix0_get_requestCnt; // 0x88
	private static DelegateBridge __Hotfix0_get_addCost; // 0x90
	private static DelegateBridge __Hotfix0_get_waitTime; // 0x98
	private static DelegateBridge __Hotfix0_get_responseMask; // 0xa0
	private static DelegateBridge __Hotfix0_get_pauseMask; // 0xa8
	private static DelegateBridge __Hotfix0_get_rejectMask; // 0xb0
	private static DelegateBridge __Hotfix0_InitPanel; // 0xb8
	private static DelegateBridge __Hotfix0_CanRequestCost; // 0xc0
	private static DelegateBridge __Hotfix0_OnReceiveCostRequest; // 0xc8
	private static DelegateBridge __Hotfix0__SwitchToState; // 0xd0
	private static DelegateBridge __Hotfix0__RegisterState; // 0xd8
	private static DelegateBridge __Hotfix0_OnFixUpdate; // 0xe0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0xe8
	private static DelegateBridge __Hotfix0_OnCostRequestButtonClicked; // 0xf0
	private static DelegateBridge __Hotfix0_OnCostAcceptButtonClicked; // 0xf8
	private static DelegateBridge __Hotfix0_OnCostRejectButtonClicked; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public AnimationWrapper costResponseWrapper { get; }
	public AnimationWrapper costAcceptWrapper { get; }
	public Button requestButton { get; }
	public CanvasGroup requestButtonWindow { get; }
	public CanvasGroup requestWaitImage { get; }
	public CanvasGroup requestResponse { get; }
	public CanvasGroup costShowWindow { get; }
	public CanvasGroup waitShowWindow { get; }
	public CanvasGroup waitRejectWindow { get; }
	public CanvasGroup waitIgnoreWindow { get; }
	public CanvasGroup forbidWindow { get; }
	public Slider requestWaitSlider { get; }
	public Slider requestResponseSlider { get; }
	public Text requestCnt { get; }
	public Text addCost { get; }
	public Text waitTime { get; }
	public Graphic responseMask { get; }
	public Graphic pauseMask { get; }
	public Graphic rejectMask { get; }

	// RVA: 0x20ca2b0 VA: 0x75946e22b0
	public AnimationWrapper get_costResponseWrapper() { }
	// RVA: 0x20ca328 VA: 0x75946e2328
	public AnimationWrapper get_costAcceptWrapper() { }
	// RVA: 0x20ca3a0 VA: 0x75946e23a0
	public Button get_requestButton() { }
	// RVA: 0x20ca418 VA: 0x75946e2418
	public CanvasGroup get_requestButtonWindow() { }
	// RVA: 0x20ca490 VA: 0x75946e2490
	public CanvasGroup get_requestWaitImage() { }
	// RVA: 0x20ca508 VA: 0x75946e2508
	public CanvasGroup get_requestResponse() { }
	// RVA: 0x20ca580 VA: 0x75946e2580
	public CanvasGroup get_costShowWindow() { }
	// RVA: 0x20ca5f8 VA: 0x75946e25f8
	public CanvasGroup get_waitShowWindow() { }
	// RVA: 0x20ca670 VA: 0x75946e2670
	public CanvasGroup get_waitRejectWindow() { }
	// RVA: 0x20ca6e8 VA: 0x75946e26e8
	public CanvasGroup get_waitIgnoreWindow() { }
	// RVA: 0x20ca760 VA: 0x75946e2760
	public CanvasGroup get_forbidWindow() { }
	// RVA: 0x20ca7d8 VA: 0x75946e27d8
	public Slider get_requestWaitSlider() { }
	// RVA: 0x20ca850 VA: 0x75946e2850
	public Slider get_requestResponseSlider() { }
	// RVA: 0x20ca8c8 VA: 0x75946e28c8
	public Text get_requestCnt() { }
	// RVA: 0x20ca940 VA: 0x75946e2940
	public Text get_addCost() { }
	// RVA: 0x20ca9b8 VA: 0x75946e29b8
	public Text get_waitTime() { }
	// RVA: 0x20caa30 VA: 0x75946e2a30
	public Graphic get_responseMask() { }
	// RVA: 0x20caaa8 VA: 0x75946e2aa8
	public Graphic get_pauseMask() { }
	// RVA: 0x20cab20 VA: 0x75946e2b20
	public Graphic get_rejectMask() { }
	// RVA: 0x20cab98 VA: 0x75946e2b98
	public Void InitPanel() { }
	// RVA: 0x20cb0d0 VA: 0x75946e30d0
	public Boolean CanRequestCost() { }
	// RVA: 0x20cb150 VA: 0x75946e3150
	public Void OnReceiveCostRequest(Object arg) { }
	// RVA: 0x20cb2e4 VA: 0x75946e32e4
	public Void _SwitchToState(CostState state, FP data) { }
	// RVA: 0x20cae44 VA: 0x75946e2e44
	private Void _RegisterState(CostState state, CostPanelState stateNode) { }
	// RVA: 0x20cb3fc VA: 0x75946e33fc
	public Void OnFixUpdate(FP deltaTime) { }
	// RVA: 0x20cb6f8 VA: 0x75946e36f8
	public Void OnUpdate() { }
	// RVA: 0x20cb888 VA: 0x75946e3888
	public Void OnCostRequestButtonClicked() { }
	// RVA: 0x20cb9ec VA: 0x75946e39ec
	public Void OnCostAcceptButtonClicked() { }
	// RVA: 0x20cbb6c VA: 0x75946e3b6c
	public Void OnCostRejectButtonClicked() { }
	// RVA: 0x20cbcec VA: 0x75946e3cec
	public Void .ctor() { }
	// RVA: 0x20cbdc0 VA: 0x75946e3dc0
	private static Void .cctor() { }
}
```