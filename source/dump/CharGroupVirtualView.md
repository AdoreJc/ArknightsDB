# CharGroupVirtualView

**Namespace:** ` `


## Fields

- `CharGroupViewParams m_param`


## Methods

- `Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupItemViewModel, Int32)`

- `Int32 GetGroupLevel()`

- `Act1VAutoChessChessShopLevelCharGroupItemView GetGroupItemView()`

- `Act1VAutoChessChessShopLevelCharItemCardView GetGroupItemCharCardItemView(Int32)`

- `GameObject GetLevelLastIndexCharItemCardView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CharGroupVirtualView : VirtualView`1
{
	private CharGroupViewParams m_param; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x8
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x10
	private static DelegateBridge __Hotfix0_OnViewAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnViewDetached; // 0x20
	private static DelegateBridge __Hotfix0_GetCharChessCardBounds; // 0x28
	private static DelegateBridge __Hotfix0_TryRefreshCharCardViewsInfos; // 0x30
	private static DelegateBridge __Hotfix0_GetGroupLevel; // 0x38
	private static DelegateBridge __Hotfix0_GetGroupItemView; // 0x40
	private static DelegateBridge __Hotfix0_GetGroupItemCharCardItemView; // 0x48
	private static DelegateBridge __Hotfix0_GetLevelLastIndexCharItemCardView; // 0x50


	// RVA: 0x331859c VA: 0x759593059c
	public Void .ctor(CharGroupViewParams param) { }
	// RVA: 0x3319174 VA: 0x7595931174
	public override GameObject GetPrefab() { }
	// RVA: 0x33191e8 VA: 0x75959311e8
	public override Single GetPreferSize() { }
	// RVA: 0x3319400 VA: 0x7595931400
	protected override Void OnViewAttached() { }
	// RVA: 0x33195c4 VA: 0x75959315c4
	protected override Void OnViewDetached() { }
	// RVA: 0x3318fa4 VA: 0x7595930fa4
	public KeyValuePair`2 GetCharChessCardBounds(String chessId) { }
	// RVA: 0x3318e98 VA: 0x7595930e98
	public Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopLevelCharGroupItemViewModel groupItemViewModel, Int32 viewIndex) { }
	// RVA: 0x3318774 VA: 0x7595930774
	public Int32 GetGroupLevel() { }
	// RVA: 0x33187f0 VA: 0x75959307f0
	public Act1VAutoChessChessShopLevelCharGroupItemView GetGroupItemView() { }
	// RVA: 0x3318c10 VA: 0x7595930c10
	public Act1VAutoChessChessShopLevelCharItemCardView GetGroupItemCharCardItemView(Int32 charCardPosition) { }
	// RVA: 0x33189f4 VA: 0x75959309f4
	public GameObject GetLevelLastIndexCharItemCardView() { }
}
```