# DIYVerticalListView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `UIRecycleVerticalLayoutGroup _layout`

- `RectTransform _viewport`

- `RectTransform _content`

- `ScrollRect _scrollRect`

- `DIYFurnitureRowView _rowPrefab`

- `DIYFurnitureTitleView _titlePrefab`


## Methods

- `Void _RenderWithoutTitle(DIYViewListData, DIYViewListThemeState)`

- `Void _RenderWithGroupTitle(DIYViewListData, DIYViewListData)`

- `Void _RenderWithFuncTitle(DIYViewListData, DIYViewListData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYVerticalListView : DIYListView
{
	private const Int32 LIST_VIEW_COLUMN_COUNT; // 0x0
	private const Int32 FOCUS_POS_OFFSET; // 0x0
	private UIRecycleVerticalLayoutGroup _layout; // 0x30
	private RectTransform _viewport; // 0x38
	private RectTransform _content; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private DIYFurnitureRowView _rowPrefab; // 0x50
	private DIYFurnitureTitleView _titlePrefab; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderWithoutTitle; // 0x8
	private static DelegateBridge __Hotfix0__RenderWithGroupTitle; // 0x10
	private static DelegateBridge __Hotfix0__RenderWithFuncTitle; // 0x18
	private static DelegateBridge __Hotfix0_GetCurrIndex; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x382948c VA: 0x7595e4148c
	public override Void Render(DIYViewListData data, DIYViewListData funcData, DIYViewDataOptions options) { }
	// RVA: 0x3829d34 VA: 0x7595e41d34
	private Void _RenderWithoutTitle(DIYViewListData data, DIYViewListThemeState themeState) { }
	// RVA: 0x38296f0 VA: 0x7595e416f0
	private Void _RenderWithGroupTitle(DIYViewListData data, DIYViewListData funcData) { }
	// RVA: 0x38299a4 VA: 0x7595e419a4
	private Void _RenderWithFuncTitle(DIYViewListData data, DIYViewListData funcData) { }
	// RVA: 0x3829e38 VA: 0x7595e41e38
	public override Int32 GetCurrIndex() { }
	// RVA: 0x382a15c VA: 0x7595e4215c
	public Void .ctor() { }
}
```