# RL04AlchemyFragmentListRowItemView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Single _preferSize`

- `SimpleLayoutContent _layoutContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Int32 m_cacheIndex`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(RL04AlchemyFragmentListRowItemVirtualViewStruct)`

- `Void TryUpdateSelectStatus(RL04AlchemyFragmentListItemRowViewModel, List`1, Int32)`

- `Void _InitIfNot()`

- `Void _RefreshAdapter(List`1)`

- `Void _OnItemClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyFragmentListRowItemView : MonoBehaviour, IHotfixable
{
	private Single _preferSize; // 0x18
	private SimpleLayoutContent _layoutContent; // 0x20
	private Boolean m_hasInited; // 0x28
	private Adapter m_adapter; // 0x30
	private Int32 m_cacheIndex; // 0x38
	private ListDict`2 m_fragmentInstSelectStateCacheDict; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private UIPageFinder m_pageFinder; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TryUpdateSelectStatus; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RefreshAdapter; // 0x18
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b07e48 VA: 0x759511fe48
	public Void Render(RL04AlchemyFragmentListRowItemVirtualViewStruct viewStruct) { }
	// RVA: 0x2b0816c VA: 0x759512016c
	public Void TryUpdateSelectStatus(RL04AlchemyFragmentListItemRowViewModel rowViewModel, List`1 selectedFragmentInstIdList, Int32 viewIndex) { }
	// RVA: 0x2b07f00 VA: 0x759511ff00
	private Void _InitIfNot() { }
	// RVA: 0x2b07fd0 VA: 0x759511ffd0
	private Void _RefreshAdapter(List`1 itemNormalViewList) { }
	// RVA: 0x2b084a8 VA: 0x75951204a8
	private Void _OnItemClick(String instId) { }
	// RVA: 0x2b085a4 VA: 0x75951205a4
	public Void .ctor() { }
}
```