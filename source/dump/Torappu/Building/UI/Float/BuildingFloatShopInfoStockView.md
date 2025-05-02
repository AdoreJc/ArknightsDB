# BuildingFloatShopInfoStockView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelLocked`

- `GameObject _panelActive`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `FillProgressBar _progress`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `Boolean m_isInited`

- `Int32 m_secsPerItem`


## Properties

- `Single outputProgress`


## Methods

- `Void Render(ShopStockInfoViewModel)`

- `Void set_outputProgress(Single)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatShopInfoStockView : MonoBehaviour
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelActive; // 0x28
	private RectTransform _itemContainer; // 0x30
	private Single _itemScale; // 0x38
	private FillProgressBar _progress; // 0x40
	private UIItemCard m_itemCard; // 0x48
	private UIItemViewModel m_itemModel; // 0x50
	private Boolean m_isInited; // 0x58
	private Int32 m_secsPerItem; // 0x5c

	public Single outputProgress { set; }

	// RVA: 0x3e2e430 VA: 0x7596446430
	public Void Render(ShopStockInfoViewModel viewModel) { }
	// RVA: 0x3e2e678 VA: 0x7596446678
	public Void set_outputProgress(Single value) { }
	// RVA: 0x3e2e524 VA: 0x7596446524
	private Void _InitIfNot() { }
	// RVA: 0x3e2e694 VA: 0x7596446694
	public Void .ctor() { }
}
```