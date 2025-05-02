# CommonTopMenu

**Namespace:** `Torappu.UI`


## Fields

- `Single TWEEN_DUR`

- `GameObject _homeHilight`

- `RectTransform _detailContainer`

- `RectTransform _detailContent`

- `CanvasGroup _detailAlphaHandler`

- `GameObject _panelBackBtn`

- `Action m_btnBackListener`

- `Boolean m_showDetail`

- `Canvas m_rootCanvas`


## Properties

- `Canvas rootCanvas`

- `GameObject backBtnGo`

- `Action onBackClick`


## Methods

- `Canvas get_rootCanvas()`

- `GameObject get_backBtnGo()`

- `Void Start()`

- `Void EventOnBtnBack()`

- `Void EventOnBtnHome()`

- `Void EventOnBlankClicked()`

- `Void _OnRouteButtonClicked(UIRouteTarget)`

- `Void _HandleRouteEvent(UIRouteTarget, Object)`

- `Void set_onBackClick(Action)`

- `Void _ToggleDetail()`

- `Void _HideDetail()`

- `Void _ShowDetailTween()`

- `Void _HideDetailTween()`

- `Void _ClearPendingTweens()`

- `Void _ResetDetailContentRect()`

- `Void <_HideDetailTween>b__28_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonTopMenu : MonoBehaviour, IHotfixable
{
	private Single TWEEN_DUR; // 0x18
	private GameObject _homeHilight; // 0x20
	private RectTransform _detailContainer; // 0x28
	private RectTransform _detailContent; // 0x30
	private CanvasGroup _detailAlphaHandler; // 0x38
	private UICommonTopMenuButton[] _routeButtons; // 0x40
	private GameObject _panelBackBtn; // 0x48
	private Action m_btnBackListener; // 0x50
	private Boolean m_showDetail; // 0x58
	private Canvas m_rootCanvas; // 0x60
	private List`1 m_playingTweens; // 0x68
	public Action`3 overrideRouteEvent; // 0x70
	public Action`2 onRouteEventHandled; // 0x78
	private static DelegateBridge __Hotfix0_get_rootCanvas; // 0x0
	private static DelegateBridge __Hotfix0_get_backBtnGo; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnBack; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnHome; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnRouteButtonClicked; // 0x30
	private static DelegateBridge __Hotfix0__HandleRouteEvent; // 0x38
	private static DelegateBridge __Hotfix0_set_onBackClick; // 0x40
	private static DelegateBridge __Hotfix0__ToggleDetail; // 0x48
	private static DelegateBridge __Hotfix0__HideDetail; // 0x50
	private static DelegateBridge __Hotfix0__ShowDetailTween; // 0x58
	private static DelegateBridge __Hotfix0__HideDetailTween; // 0x60
	private static DelegateBridge __Hotfix0__ClearPendingTweens; // 0x68
	private static DelegateBridge __Hotfix0__ResetDetailContentRect; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected Canvas rootCanvas { get; }
	public GameObject backBtnGo { get; }
	public Action onBackClick { set; }

	// RVA: 0x2218928 VA: 0x7594830928
	protected Canvas get_rootCanvas() { }
	// RVA: 0x2218a58 VA: 0x7594830a58
	public GameObject get_backBtnGo() { }
	// RVA: 0x2218ac0 VA: 0x7594830ac0
	private Void Start() { }
	// RVA: 0x2218d84 VA: 0x7594830d84
	public Void EventOnBtnBack() { }
	// RVA: 0x2218e90 VA: 0x7594830e90
	public Void EventOnBtnHome() { }
	// RVA: 0x2218f7c VA: 0x7594830f7c
	public Void EventOnBlankClicked() { }
	// RVA: 0x2218fe4 VA: 0x7594830fe4
	private Void _OnRouteButtonClicked(UIRouteTarget target) { }
	// RVA: 0x22190e4 VA: 0x75948310e4
	private Void _HandleRouteEvent(UIRouteTarget target, Object param) { }
	// RVA: 0x22191d0 VA: 0x75948311d0
	public Void set_onBackClick(Action value) { }
	// RVA: 0x2218ef8 VA: 0x7594830ef8
	private Void _ToggleDetail() { }
	// RVA: 0x2218e10 VA: 0x7594830e10
	private Void _HideDetail() { }
	// RVA: 0x2219254 VA: 0x7594831254
	private Void _ShowDetailTween() { }
	// RVA: 0x22195b0 VA: 0x75948315b0
	private Void _HideDetailTween() { }
	// RVA: 0x2219b20 VA: 0x7594831b20
	private Void _ClearPendingTweens() { }
	// RVA: 0x2219840 VA: 0x7594831840
	private Void _ResetDetailContentRect() { }
	// RVA: 0x2219c2c VA: 0x7594831c2c
	public Void .ctor() { }
	// RVA: 0x2219cfc VA: 0x7594831cfc
	private Void <_HideDetailTween>b__28_0() { }
}
```