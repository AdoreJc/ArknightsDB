# DIYFurnitureRowView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Transform _container`

- `DIYRecycleElementView _prefab`

- `ElementType m_elementType`

- `Boolean m_needEmptyItem`


## Methods

- `Void OnInit(List`1, DIYViewListThemeState, Boolean)`

- `Void _UpdateItemView(List`1, Boolean)`

- `Void _AppendNewItemView(List`1, Int32, Int32, Boolean)`

- `Void _FillWithEmptyView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureRowView : DIYFurnitureVerticalListElementView
{
	private const Int32 LIST_VIEW_COLUMN_COUNT; // 0x0
	private Transform _container; // 0x20
	private DIYRecycleElementView _prefab; // 0x28
	private List`1 m_furnitureItemViews; // 0x30
	private ElementType m_elementType; // 0x38
	private Boolean m_needEmptyItem; // 0x3c
	public Func`2 furnitureSelected; // 0x40
	public Func`2 infoButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__UpdateItemView; // 0x8
	private static DelegateBridge __Hotfix0__AppendNewItemView; // 0x10
	private static DelegateBridge __Hotfix0__FillWithEmptyView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x381bb68 VA: 0x7595e33b68
	public Void OnInit(List`1 itemViewDatas, DIYViewListThemeState themeState, Boolean firstRow) { }
	// RVA: 0x381c27c VA: 0x7595e3427c
	private Void _UpdateItemView(List`1 itemViewDatas, Boolean firstRow) { }
	// RVA: 0x381c448 VA: 0x7595e34448
	private Void _AppendNewItemView(List`1 itemViewDatas, Int32 begin, Int32 count, Boolean firstRow) { }
	// RVA: 0x381c640 VA: 0x7595e34640
	private Void _FillWithEmptyView() { }
	// RVA: 0x381cb80 VA: 0x7595e34b80
	public Void .ctor() { }
}
```