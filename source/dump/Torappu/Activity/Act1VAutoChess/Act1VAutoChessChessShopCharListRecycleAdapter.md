# Act1VAutoChessChessShopCharListRecycleAdapter

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopBaseCharListView m_closure`


## Methods

- `Void RebuildList(Act1VAutoChessChessShopLevelCharGroupListViewModel, IDragHandler)`

- `Act1VAutoChessChessShopLevelCharGroupItemView GetGroupItemView(Int32)`

- `GameObject GetLevelLastIndexCharItemCardView(Int32)`

- `Act1VAutoChessChessShopLevelCharItemCardView GetGroupItemCharCardItemView(Int32, Int32)`

- `Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupListViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopCharListRecycleAdapter : UIRecycleLayoutAdapter
{
	private Act1VAutoChessChessShopBaseCharListView m_closure; // 0x18
	private List`1 m_views; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10
	private static DelegateBridge __Hotfix0_GetGroupItemView; // 0x18
	private static DelegateBridge __Hotfix0_GetLevelLastIndexCharItemCardView; // 0x20
	private static DelegateBridge __Hotfix0_GetGroupItemCharCardItemView; // 0x28
	private static DelegateBridge __Hotfix0_TryRefreshCharCardViewsInfos; // 0x30
	private static DelegateBridge __Hotfix0_GetCharCardBounds; // 0x38


	// RVA: 0x3318020 VA: 0x7595930020
	public Void .ctor(Act1VAutoChessChessShopBaseCharListView closure) { }
	// RVA: 0x3318108 VA: 0x7595930108
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x33182a8 VA: 0x75959302a8
	public Void RebuildList(Act1VAutoChessChessShopLevelCharGroupListViewModel viewModel, IDragHandler dragHandler) { }
	// RVA: 0x331864c VA: 0x759593064c
	public Act1VAutoChessChessShopLevelCharGroupItemView GetGroupItemView(Int32 shopLevel) { }
	// RVA: 0x33188cc VA: 0x75959308cc
	public GameObject GetLevelLastIndexCharItemCardView(Int32 shopLevel) { }
	// RVA: 0x3318adc VA: 0x7595930adc
	public Act1VAutoChessChessShopLevelCharItemCardView GetGroupItemCharCardItemView(Int32 shopLevel, Int32 charCardPosition) { }
	// RVA: 0x3318d14 VA: 0x7595930d14
	public Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupListViewModel viewModel) { }
	// RVA: 0x3317558 VA: 0x759592f558
	public KeyValuePair`2 GetCharCardBounds(Int32 viewIndex, String chessId) { }
}
```