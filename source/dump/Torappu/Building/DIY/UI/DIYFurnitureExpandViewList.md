# DIYFurnitureExpandViewList

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `RectTransform _panelBackGround`

- `RectTransform _panelExpandBackGroundMask`

- `DIYFurniturePanelSort _sortPanel`

- `DIYViewListGroup _viewListGroup`

- `DIYViewListGroup _viewListThemeGroup`

- `Boolean m_isInit`

- `ExpandSwitchTween m_expandSwitchTween`

- `DIYViewListGroup m_currViewListGroup`

- `UIExpandListState m_cachedExpandListState`

- `DIYViewListThemeState m_cachedThemeState`

- `DIYListViewState <bindState>k__BackingField`


## Properties

- `DIYListViewState bindState`


## Methods

- `DIYListViewState get_bindState()`

- `Void set_bindState(DIYListViewState)`

- `Void _InitIfNot()`

- `Void OnEnter()`

- `Void OnSortMethodClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureExpandViewList : DataBinder`1
{
	private const Int32 BKG_HEIGHT_NORMAL; // 0x0
	private const Int32 BKG_HEIGHT_EXPAND; // 0x0
	private const Single EXPAND_DURATION; // 0x0
	private RectTransform _panelBackGround; // 0x20
	private RectTransform _panelExpandBackGroundMask; // 0x28
	private DIYFurniturePanelSort _sortPanel; // 0x30
	private DIYViewListGroup _viewListGroup; // 0x38
	private DIYViewListGroup _viewListThemeGroup; // 0x40
	private Boolean m_isInit; // 0x48
	private ExpandSwitchTween m_expandSwitchTween; // 0x50
	private DIYViewListGroup m_currViewListGroup; // 0x58
	private UIExpandListState m_cachedExpandListState; // 0x60
	private DIYViewListThemeState m_cachedThemeState; // 0x64
	public Func`2 OnButtonPressed; // 0x68
	public Func`2 OnInfoPressed; // 0x70
	private DIYListViewState <bindState>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_bindState; // 0x0
	private static DelegateBridge __Hotfix0_set_bindState; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnSortMethodClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public DIYListViewState bindState { get; set; }

	// RVA: 0x3818e4c VA: 0x7595e30e4c
	public DIYListViewState get_bindState() { }
	// RVA: 0x3818eb4 VA: 0x7595e30eb4
	public Void set_bindState(DIYListViewState value) { }
	// RVA: 0x3818f38 VA: 0x7595e30f38
	private Void _InitIfNot() { }
	// RVA: 0x38190ac VA: 0x7595e310ac
	public Void OnEnter() { }
	// RVA: 0x3819420 VA: 0x7595e31420
	public override Void OnValueChanged(DIYViewListProperty property) { }
	// RVA: 0x3819ae0 VA: 0x7595e31ae0
	public Void OnSortMethodClicked() { }
	// RVA: 0x3819c00 VA: 0x7595e31c00
	public Void .ctor() { }
}
```