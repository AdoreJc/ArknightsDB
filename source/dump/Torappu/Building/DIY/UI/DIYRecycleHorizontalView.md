# DIYRecycleHorizontalView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYRecycleElementView _prefab`

- `DIYRecycleElementView _emptyPrefab`

- `UIRecycleHorizonLayoutGroup _layout`

- `ScrollRect _scrollRect`

- `RectTransform _viewport`

- `RectTransform _content`

- `DIYRecycleHorizontalAdapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot(DIYViewListData, DIYViewListData)`

- `Void _FocusToIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYRecycleHorizontalView : DIYListView
{
	private DIYRecycleElementView _prefab; // 0x30
	private DIYRecycleElementView _emptyPrefab; // 0x38
	private UIRecycleHorizonLayoutGroup _layout; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private RectTransform _viewport; // 0x50
	private RectTransform _content; // 0x58
	private DIYRecycleHorizontalAdapter m_adapter; // 0x60
	private Boolean m_hasInited; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrIndex; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__FocusToIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x382c604 VA: 0x7595e44604
	public override Void Render(DIYViewListData data, DIYViewListData funcData, DIYViewDataOptions options) { }
	// RVA: 0x382cb68 VA: 0x7595e44b68
	public override Int32 GetCurrIndex() { }
	// RVA: 0x382c888 VA: 0x7595e44888
	private Void _InitIfNot(DIYViewListData data, DIYViewListData funcData) { }
	// RVA: 0x382c9f0 VA: 0x7595e449f0
	private Void _FocusToIndex(Int32 index) { }
	// RVA: 0x382ce84 VA: 0x7595e44e84
	public Void .ctor() { }
}
```