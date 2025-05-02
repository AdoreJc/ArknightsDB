# DIYFurnitureTitleRecycleAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFurnitureRowView m_prefab`

- `DIYFurnitureTitleView m_titlePrefab`

- `Int32 m_countPerRow`

- `Single m_rowHeight`

- `DIYViewListThemeState m_themeState`


## Methods

- `Void _BuildVirtualRowViews(List`1, ref, ref)`

- `Void _BuildVirtualTitleRowView(String, List`1, ref, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureTitleRecycleAdapter : UIRecycleLayoutAdapter
{
	private DIYFurnitureRowView m_prefab; // 0x18
	private DIYFurnitureTitleView m_titlePrefab; // 0x20
	private Int32 m_countPerRow; // 0x28
	private Single m_rowHeight; // 0x2c
	private List`1 m_viewDatas; // 0x30
	private DIYViewListThemeState m_themeState; // 0x38
	public Func`2 OnButtonSelected; // 0x40
	public Func`2 OnButtonInfo; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__BuildVirtualRowViews; // 0x8
	private static DelegateBridge __Hotfix0__BuildVirtualTitleRowView; // 0x10
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x18


	// RVA: 0x381f0ec VA: 0x7595e370ec
	public Void .ctor(List`1 viewDatas, DIYFurnitureRowView prefab, DIYFurnitureTitleView titlePrefab, DIYViewListThemeState themeState) { }
	// RVA: 0x381f220 VA: 0x7595e37220
	private Void _BuildVirtualRowViews(List`1 viewDatas, ref Int32 startIndex, ref List`1 virtualViews) { }
	// RVA: 0x381f474 VA: 0x7595e37474
	private Void _BuildVirtualTitleRowView(String text, List`1 viewDatas, ref Int32 startIndex, ref List`1 virtualViews) { }
	// RVA: 0x381f69c VA: 0x7595e3769c
	public override IList`1 GenerateViewsForRebuild() { }
}
```