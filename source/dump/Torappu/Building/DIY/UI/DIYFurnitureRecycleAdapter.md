# DIYFurnitureRecycleAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFurnitureRowView m_prefab`

- `Int32 m_countPerRow`

- `Single m_rowHeight`

- `DIYViewListThemeState m_themeState`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureRecycleAdapter : UIRecycleLayoutAdapter
{
	private DIYFurnitureRowView m_prefab; // 0x18
	private Int32 m_countPerRow; // 0x20
	private Single m_rowHeight; // 0x24
	private DIYViewListThemeState m_themeState; // 0x28
	private List`1 m_viewDatas; // 0x30
	public Func`2 OnButtonSelected; // 0x38
	public Func`2 OnButtonInfo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8


	// RVA: 0x381beec VA: 0x7595e33eec
	public Void .ctor(List`1 viewDatas, DIYFurnitureRowView prefab, DIYViewListThemeState themeState) { }
	// RVA: 0x381c000 VA: 0x7595e34000
	public override IList`1 GenerateViewsForRebuild() { }
}
```