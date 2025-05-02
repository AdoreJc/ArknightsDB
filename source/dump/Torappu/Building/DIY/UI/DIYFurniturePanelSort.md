# DIYFurniturePanelSort

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `SimpleLayoutContent _pnlList`

- `GameObject _pnlBkg`

- `DIYListViewState <bindState>k__BackingField`

- `DIYSortMethodViewModel m_cachedModel`

- `ShowSwitchTween m_switchTween`

- `Adapter m_listAdapter`

- `Boolean m_hasInited`

- `Boolean m_isShow`

- `Boolean m_isExpand`


## Properties

- `DIYListViewState bindState`


## Methods

- `DIYListViewState get_bindState()`

- `Void set_bindState(DIYListViewState)`

- `Void _InitIfNot()`

- `Void _ResetPositionBeforeShow()`

- `Void SetExpandListState(Boolean)`

- `Void SetShow(Boolean, Boolean)`

- `Void Toggle()`

- `Void EventOnClicked(DiySortType, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurniturePanelSort : DataBinder`1
{
	private static Vector2 FLOAT_PANEL_PIVOT_NORMAL; // 0x0
	private static Vector2 FLOAT_PANEL_PIVOT_EXPAND; // 0x8
	private static Vector2 FLOAT_PANEL_ANCHORED_POS_NORMAL; // 0x10
	private static Vector2 FLOAT_PANEL_ANCHORED_POS_EXPAND; // 0x18
	private const Single SHOW_DURATION; // 0x0
	private const Int32 SHOW_OFFSET_Y; // 0x0
	private SimpleLayoutContent _pnlList; // 0x20
	private GameObject _pnlBkg; // 0x28
	private DIYListViewState <bindState>k__BackingField; // 0x30
	private DIYSortMethodViewModel m_cachedModel; // 0x38
	private ShowSwitchTween m_switchTween; // 0x40
	private Adapter m_listAdapter; // 0x48
	private Boolean m_hasInited; // 0x50
	private Boolean m_isShow; // 0x51
	private Boolean m_isExpand; // 0x52
	private static DelegateBridge __Hotfix0_get_bindState; // 0x20
	private static DelegateBridge __Hotfix0_set_bindState; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__ResetPositionBeforeShow; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0_SetExpandListState; // 0x48
	private static DelegateBridge __Hotfix0_SetShow; // 0x50
	private static DelegateBridge __Hotfix0_Toggle; // 0x58
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public DIYListViewState bindState { get; set; }

	// RVA: 0x381a570 VA: 0x7595e32570
	public DIYListViewState get_bindState() { }
	// RVA: 0x38191cc VA: 0x7595e311cc
	public Void set_bindState(DIYListViewState value) { }
	// RVA: 0x381a5e8 VA: 0x7595e325e8
	private Void _InitIfNot() { }
	// RVA: 0x381a878 VA: 0x7595e32878
	private Void _ResetPositionBeforeShow() { }
	// RVA: 0x381a9ec VA: 0x7595e329ec
	public override Void OnValueChanged(DIYSortMethodViewProperty property) { }
	// RVA: 0x3819f88 VA: 0x7595e31f88
	public Void SetExpandListState(Boolean isExpand) { }
	// RVA: 0x3819348 VA: 0x7595e31348
	public Void SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x3819b78 VA: 0x7595e31b78
	public Void Toggle() { }
	// RVA: 0x381aac8 VA: 0x7595e32ac8
	public Void EventOnClicked(DiySortType diyUIType, Int32 index) { }
	// RVA: 0x381abcc VA: 0x7595e32bcc
	public Void .ctor() { }
	// RVA: 0x381ac6c VA: 0x7595e32c6c
	private static Void .cctor() { }
}
```