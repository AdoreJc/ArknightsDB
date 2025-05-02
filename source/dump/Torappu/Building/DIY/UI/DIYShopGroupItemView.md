# DIYShopGroupItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _groupNameLabel`

- `GameObject _furnitureViewProto`

- `RectTransform _furnitureListContainer`

- `Single _marginSize`

- `DIYShopGroupItemModel m_model`


## Methods

- `Void _OnFurnitureSelected(DIYShopItemViewData, ShopFurnitureItemView)`

- `Void Setup(DIYShopGroupItemModel, Predicate`1, Comparison`1)`

- `Void Refresh()`

- `Void _UpdateLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopGroupItemView : MonoBehaviour
{
	private Text _groupNameLabel; // 0x18
	private GameObject _furnitureViewProto; // 0x20
	private RectTransform _furnitureListContainer; // 0x28
	private Single _marginSize; // 0x30
	private DIYShopGroupItemModel m_model; // 0x38
	private List`1 m_furnitureDataList; // 0x40
	private List`1 m_furnitureViewList; // 0x48


	// RVA: 0x38025dc VA: 0x7595e1a5dc
	private Void _OnFurnitureSelected(DIYShopItemViewData data, ShopFurnitureItemView view) { }
	// RVA: 0x3802600 VA: 0x7595e1a600
	public Void Setup(DIYShopGroupItemModel model, Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x38036c4 VA: 0x7595e1b6c4
	public Void Refresh() { }
	// RVA: 0x38035ac VA: 0x7595e1b5ac
	private Void _UpdateLayout() { }
	// RVA: 0x38034fc VA: 0x7595e1b4fc
	private static Int32 _GetFurnitureTotalCount(String furnitureId, IFurnitureStorage storage) { }
	// RVA: 0x3803918 VA: 0x7595e1b918
	public Void .ctor() { }
}
```