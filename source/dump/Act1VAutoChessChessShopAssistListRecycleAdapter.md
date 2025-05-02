# Act1VAutoChessChessShopAssistListRecycleAdapter

**Namespace:** ` `


## Fields

- `Act1VAutoChessChessShopQuickAssistView m_closure`


## Methods

- `Void RebuildList(Act1VAutoChessChessShopQuickAssistViewModel)`

- `Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopQuickAssistViewModel)`

- `Void _RefreshCacheDict(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Act1VAutoChessChessShopAssistListRecycleAdapter : UIRecycleLayoutAdapter
{
	private Act1VAutoChessChessShopQuickAssistView m_closure; // 0x18
	private List`1 m_views; // 0x20
	private ListDict`2 m_cachedDict; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge __Hotfix0_RebuildList; // 0x10
	private static DelegateBridge __Hotfix0_TryRefreshCharCardViewsInfos; // 0x18
	private static DelegateBridge __Hotfix0__RefreshCacheDict; // 0x20


	// RVA: 0x3320f10 VA: 0x7595938f10
	public Void .ctor(Act1VAutoChessChessShopQuickAssistView closure) { }
	// RVA: 0x33215c4 VA: 0x75959395c4
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x332041c VA: 0x759593841c
	public Void RebuildList(Act1VAutoChessChessShopQuickAssistViewModel viewModel) { }
	// RVA: 0x3320818 VA: 0x7595938818
	public Void TryRefreshCharCardViewsInfos(Act1VAutoChessChessShopQuickAssistViewModel viewModel) { }
	// RVA: 0x33217c4 VA: 0x75959397c4
	private Void _RefreshCacheDict(List`1 viewModelList) { }
}
```