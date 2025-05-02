# CrisisV2RuneDetailSlotView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `ScrollRect _scrollRect`

- `RectTransform _viewPort`

- `Rect _padding`

- `Single _spacing`

- `Single _downPadding`

- `CrisisV2RuneSelectInfoSingleItemView _itemViewPrefab`

- `CrisisV2RuneSelectInfoSingleTitleView _titleViewPrefab`

- `Single _showHideDuration`

- `Single _moveDuration`

- `UILayoutDimensionListener _listener`

- `Boolean m_isInited`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `Options m_layoutOption`

- `CrisisV2MapModel m_model`

- `Int32 m_cachedFocusSeq`


## Methods

- `Boolean ShowSlotView(CrisisV2MapModel)`

- `Void _InitIfNot()`

- `Void _OnRuneDetailListChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneDetailSlotView : UICustomAdapterLayout`2
{
	private ScrollRect _scrollRect; // 0x78
	private RectTransform _viewPort; // 0x80
	private Rect _padding; // 0x88
	private Single _spacing; // 0x98
	private Single _downPadding; // 0x9c
	private CrisisV2RuneSelectInfoSingleItemView _itemViewPrefab; // 0xa0
	private CrisisV2RuneSelectInfoSingleTitleView _titleViewPrefab; // 0xa8
	private Single _showHideDuration; // 0xb0
	private Single _moveDuration; // 0xb4
	private UILayoutDimensionListener _listener; // 0xb8
	private Boolean m_isInited; // 0xc0
	private InnerLayouter m_layouter; // 0xc8
	private InnerAdapter m_adapter; // 0xd0
	private Options m_layoutOption; // 0xd8
	private CrisisV2MapModel m_model; // 0xf0
	private Int32 m_cachedFocusSeq; // 0xf8
	private static DelegateBridge __Hotfix0_ShowSlotView; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnRuneDetailListChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2c0fe24 VA: 0x7595227e24
	public Boolean ShowSlotView(CrisisV2MapModel model) { }
	// RVA: 0x2c0ff64 VA: 0x7595227f64
	private Void _InitIfNot() { }
	// RVA: 0x2c102e0 VA: 0x75952282e0
	private Void _OnRuneDetailListChanged() { }
	// RVA: 0x2c103a4 VA: 0x75952283a4
	public Void .ctor() { }
}
```