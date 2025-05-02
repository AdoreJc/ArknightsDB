# NewsItemView

**Namespace:** ` `


## Fields

- `GameObject _root`

- `UIAtlasImage _newsImage`

- `RectTransform _itemViewHolder`

- `RL02ReportNewsView m_closure`

- `RL02ReportNewsItemViewBase m_itemView`


## Methods

- `Void Init(RL02ReportNewsView)`

- `SpriteRenderData _GetNewsImage(NewsType)`

- `Void _RenderItemView(NewsItemModel)`

- `Void Render(NewsItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NewsItemView : IHotfixable
{
	private GameObject _root; // 0x10
	private UIAtlasImage _newsImage; // 0x18
	private RectTransform _itemViewHolder; // 0x20
	private RL02ReportNewsView m_closure; // 0x28
	private RL02ReportNewsItemViewBase m_itemView; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__GetNewsImage; // 0x8
	private static DelegateBridge __Hotfix0__RenderItemView; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b660ec VA: 0x759517e0ec
	public Void Init(RL02ReportNewsView closure) { }
	// RVA: 0x2b6657c VA: 0x759517e57c
	private SpriteRenderData _GetNewsImage(NewsType newsType) { }
	// RVA: 0x2b66674 VA: 0x759517e674
	private Void _RenderItemView(NewsItemModel itemModel) { }
	// RVA: 0x2b66388 VA: 0x759517e388
	public Void Render(NewsItemModel itemModel) { }
	// RVA: 0x2b66858 VA: 0x759517e858
	public Void .ctor() { }
}
```