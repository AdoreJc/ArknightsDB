# BuildingShopFormulaItemView

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `UIItemCard _itemPrefab`

- `RectTransform _itemContainer`

- `Single _targetScale`

- `GameObject _panelClickSpot`

- `GameObject _panelActive`

- `GameObject _panelEmpty`

- `GameObject _panelLocked`

- `Text _textName`

- `UIBicolorText _textTime`

- `Image _iconCost`

- `Text _textPrice`

- `Text _textUnlockCond`

- `UILongPressButton _btnFormula`

- `Sprite _iconGold`

- `Sprite _iconDiamond`

- `Sprite _iconDmdShd`

- `SFormulaViewModel m_cachedFormula`

- `Boolean m_isInited`

- `UIItemCard m_targetItemCard`

- `UIItemViewModel m_targetItemModel`


## Methods

- `Void Render(SFormulaViewModel)`

- `Void _Init(SFormulaViewModel)`

- `Void _RenderActive(SFormulaViewModel)`

- `Sprite _GetSpriteByType(ItemType)`

- `Void _OnFormulaClicked()`

- `Boolean _OnFormulaLongPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopFormulaItemView : MonoBehaviour
{
	private const Int32 LARGE_ITEM_FOR_DISPLAY; // 0x0
	private UIItemCard _itemPrefab; // 0x18
	private RectTransform _itemContainer; // 0x20
	private Single _targetScale; // 0x28
	private GameObject _panelClickSpot; // 0x30
	private GameObject _panelActive; // 0x38
	private GameObject _panelEmpty; // 0x40
	private GameObject _panelLocked; // 0x48
	private Text _textName; // 0x50
	private UIBicolorText _textTime; // 0x58
	private Image _iconCost; // 0x60
	private Text _textPrice; // 0x68
	private Text _textUnlockCond; // 0x70
	private UILongPressButton _btnFormula; // 0x78
	private Sprite _iconGold; // 0x80
	private Sprite _iconDiamond; // 0x88
	private Sprite _iconDmdShd; // 0x90
	public Action`1 onFormulaClicked; // 0x98
	private SFormulaViewModel m_cachedFormula; // 0xa0
	private Boolean m_isInited; // 0xa8
	private UIItemCard m_targetItemCard; // 0xb0
	private UIItemViewModel m_targetItemModel; // 0xb8


	// RVA: 0x3dbea08 VA: 0x75963d6a08
	public Void Render(SFormulaViewModel viewModel) { }
	// RVA: 0x3dbee90 VA: 0x75963d6e90
	private Void _Init(SFormulaViewModel viewModel) { }
	// RVA: 0x3dbf06c VA: 0x75963d706c
	private Void _RenderActive(SFormulaViewModel viewModel) { }
	// RVA: 0x3dbf2e4 VA: 0x75963d72e4
	private Sprite _GetSpriteByType(ItemType itemType) { }
	// RVA: 0x3dbf310 VA: 0x75963d7310
	private Void _OnFormulaClicked() { }
	// RVA: 0x3dbf330 VA: 0x75963d7330
	private Boolean _OnFormulaLongPressed() { }
	// RVA: 0x3dbf388 VA: 0x75963d7388
	public Void .ctor() { }
}
```