# ClimbTowerTrainView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _towerName`

- `Text _towerSubName`

- `Image _towerIcon`

- `Text _towerDesc`

- `TwoStateToggle _btnEnter`

- `TwoStateToggle _btnContinue`

- `GameObject _panelBtnEnter`

- `TwoStateToggle _toggleDetailText`

- `GameObject _panelAllComplete`

- `RectTransform _rectAllComplete`

- `CanvasGroup _canvasGroupBtn`

- `Boolean m_hasInited`

- `TweenWrapper m_tween`

- `TweenWrapper m_toastTween`

- `String m_cachedTower`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void OnExit()`

- `Void set_onTowerSelected(Action`1)`

- `Void set_onDetailClicked(Action`1)`

- `Void OnEmptySelected()`

- `Void _RenderFadeSwitchContents(ClimbTowerTrainViewModel)`

- `Void _PlayAllCompleteToastAnimIfNeed(Boolean)`

- `Void _RenderTowerInfo(ClimbTowerTrainViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainView : DataBinder`1, IHotfixable
{
	private const Single FADE_SWITCH_DUR; // 0x0
	private const Single FADE_RENDER_DELAY; // 0x0
	private static readonly Vector2 ALL_COMPLETE_TOAST_START_POS; // 0x0
	private static readonly Vector2 ALL_COMPLETE_TOAST_END_POS; // 0x8
	private const Single FADE_TOAST_DUR; // 0x0
	private ClimbTowerTrainItemView[] _trainTowerButtons; // 0x20
	private Text _towerName; // 0x28
	private Text _towerSubName; // 0x30
	private Image _towerIcon; // 0x38
	private Text _towerDesc; // 0x40
	private TwoStateToggle _btnEnter; // 0x48
	private TwoStateToggle _btnContinue; // 0x50
	private GameObject _panelBtnEnter; // 0x58
	private TwoStateToggle _toggleDetailText; // 0x60
	private GameObject _panelAllComplete; // 0x68
	private RectTransform _rectAllComplete; // 0x70
	private CanvasGroup _canvasGroupBtn; // 0x78
	private Boolean m_hasInited; // 0x80
	private TweenWrapper m_tween; // 0x88
	private TweenWrapper m_toastTween; // 0x90
	private String m_cachedTower; // 0x98
	private UIPage <page>k__BackingField; // 0xa0
	private Action`1 <onTowerSelected>k__BackingField; // 0xa8
	private Action`1 <onDetailClicked>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_set_page; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_get_onTowerSelected; // 0x28
	private static DelegateBridge __Hotfix0_set_onTowerSelected; // 0x30
	private static DelegateBridge __Hotfix0_get_onDetailClicked; // 0x38
	private static DelegateBridge __Hotfix0_set_onDetailClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnEmptySelected; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__RenderFadeSwitchContents; // 0x58
	private static DelegateBridge __Hotfix0__PlayAllCompleteToastAnimIfNeed; // 0x60
	private static DelegateBridge __Hotfix0__RenderTowerInfo; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private UIPage page { get; set; }
	private Action`1 onTowerSelected { get; set; }
	private Action`1 onDetailClicked { get; set; }

	// RVA: 0x2c6aef8 VA: 0x7595282ef8
	private UIPage get_page() { }
	// RVA: 0x2c6af70 VA: 0x7595282f70
	public Void set_page(UIPage value) { }
	// RVA: 0x2c6b004 VA: 0x7595283004
	public Void OnExit() { }
	// RVA: 0x2c6b0a0 VA: 0x75952830a0
	private Action`1 get_onTowerSelected() { }
	// RVA: 0x2c6b118 VA: 0x7595283118
	public Void set_onTowerSelected(Action`1 value) { }
	// RVA: 0x2c6b1ac VA: 0x75952831ac
	private Action`1 get_onDetailClicked() { }
	// RVA: 0x2c6b224 VA: 0x7595283224
	public Void set_onDetailClicked(Action`1 value) { }
	// RVA: 0x2c6b2b8 VA: 0x75952832b8
	public Void OnEmptySelected() { }
	// RVA: 0x2c6b384 VA: 0x7595283384
	public override Void OnValueChanged(ClimbTowerTrainProperty property) { }
	// RVA: 0x2c6bc9c VA: 0x7595283c9c
	private Void _RenderFadeSwitchContents(ClimbTowerTrainViewModel model) { }
	// RVA: 0x2c6b8f4 VA: 0x75952838f4
	private Void _PlayAllCompleteToastAnimIfNeed(Boolean isAllComplete) { }
	// RVA: 0x2c6bafc VA: 0x7595283afc
	private Void _RenderTowerInfo(ClimbTowerTrainViewModel model) { }
	// RVA: 0x2c6b7a0 VA: 0x75952837a0
	private Void _InitIfNot() { }
	// RVA: 0x2c6bf28 VA: 0x7595283f28
	public Void .ctor() { }
	// RVA: 0x2c6bfc8 VA: 0x7595283fc8
	private static Void .cctor() { }
}
```