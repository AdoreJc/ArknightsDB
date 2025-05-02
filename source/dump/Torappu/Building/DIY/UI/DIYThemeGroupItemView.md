# DIYThemeGroupItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _groupNameLabel`

- `GameObject _furnitureViewProto`

- `RectTransform _furnitureListContainer`

- `Single _marginSize`

- `DIYThemeGroupItemModel m_model`


## Methods

- `Boolean _OnFurnitureSelected(DIYItemViewData)`

- `Void _OnFurnitureSelected(DIYItemViewData, FurnitureItemView)`

- `Void _OnInfoButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void Setup(IFurnitureDataProvider, IDIYRoomModifierDataProvider, IFurnitureProvider, IDIYRoomModifierProvider, DIYThemeGroupItemModel, Action`1)`

- `Void _UpdateLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYThemeGroupItemView : MonoBehaviour
{
	private Text _groupNameLabel; // 0x18
	private GameObject _furnitureViewProto; // 0x20
	private RectTransform _furnitureListContainer; // 0x28
	private Single _marginSize; // 0x30
	private DIYThemeGroupItemModel m_model; // 0x38
	private List`1 m_furnitureViewList; // 0x40
	private Action`1 m_infoCallback; // 0x48


	// RVA: 0x380d878 VA: 0x7595e25878
	private Boolean _OnFurnitureSelected(DIYItemViewData data) { }
	// RVA: 0x380d8cc VA: 0x7595e258cc
	private Void _OnFurnitureSelected(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x380d920 VA: 0x7595e25920
	private Void _OnInfoButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x380d93c VA: 0x7595e2593c
	public Void Setup(IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider, IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider, DIYThemeGroupItemModel model, Action`1 infoCallback) { }
	// RVA: 0x380e74c VA: 0x7595e2674c
	private Void _UpdateLayout() { }
	// RVA: 0x380e69c VA: 0x7595e2669c
	private static Int32 _GetFurnitureTotalCount(String furnitureId, IFurnitureStorage storage) { }
	// RVA: 0x380e864 VA: 0x7595e26864
	public Void .ctor() { }
}
```