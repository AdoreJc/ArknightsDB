# Act24sideEatView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIAnimationLocation _animPanelSwitch`

- `Act24sideEatMealItem _prefabMealItem`

- `WelcomePanel _pnlWelcome`

- `DetailPanel _pnlDetail`

- `CanvasGroup _canvasTips`

- `Text _textTips`

- `Single _canvasTipsSwitchDuration`

- `Boolean m_inited`

- `UISwitchTween m_panelSwitchTween`

- `UISwitchTween m_panelTipSwitchTween`

- `Int32 m_cachedSequenceNum`

- `Int64 m_cachedNextRefreshTs`

- `Boolean m_cachedShowNextRefreshTs`

- `UIStateFinder m_finder`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateCountdownText()`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void OnBtnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEatView : DataBinder`1, ITimeWatcher
{
	private UIAnimationLocation _animPanelSwitch; // 0x20
	private RectTransform[] _mealItemHolders; // 0x30
	private Act24sideEatMealItem _prefabMealItem; // 0x38
	private WelcomePanel _pnlWelcome; // 0x40
	private DetailPanel _pnlDetail; // 0x48
	private CanvasGroup _canvasTips; // 0x50
	private Text _textTips; // 0x58
	private Single _canvasTipsSwitchDuration; // 0x60
	private Boolean m_inited; // 0x64
	private UISwitchTween m_panelSwitchTween; // 0x68
	private UISwitchTween m_panelTipSwitchTween; // 0x70
	private List`1 m_mealItems; // 0x78
	private Int32 m_cachedSequenceNum; // 0x80
	private Int64 m_cachedNextRefreshTs; // 0x88
	private Boolean m_cachedShowNextRefreshTs; // 0x90
	private UIStateFinder m_finder; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__UpdateCountdownText; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnConfirmClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x329a06c VA: 0x75958b206c
	private Void _InitIfNot() { }
	// RVA: 0x329a360 VA: 0x75958b2360
	private Void _UpdateCountdownText() { }
	// RVA: 0x329a570 VA: 0x75958b2570
	private Void Start() { }
	// RVA: 0x329a5e0 VA: 0x75958b25e0
	private Void OnDestroy() { }
	// RVA: 0x329a650 VA: 0x75958b2650
	public override Void OnValueChanged(Act24sideEatProperty property) { }
	// RVA: 0x329ac8c VA: 0x75958b2c8c
	public Void UpdateTime(Single timeDelta) { }
	// RVA: 0x329ad08 VA: 0x75958b2d08
	public Void OnBtnConfirmClicked() { }
	// RVA: 0x329adbc VA: 0x75958b2dbc
	public Void .ctor() { }
}
```