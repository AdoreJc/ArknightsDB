# PagerAdapter

**Namespace:** ` `


## Fields

- `ActMultiV3TitlePagerView m_closure`

- `Int32 m_focusPageIndex`

- `Int32 m_cachedLoadSeqNum`


## Methods

- `Void RebuildListIfNeeded(ActMultiV3ManualTitleListModel)`

- `Void NotifyFocusPage(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PagerAdapter : UIRecycleLayoutAdapter
{
	private ActMultiV3TitlePagerView m_closure; // 0x18
	private List`1 m_cells; // 0x20
	private Int32 m_focusPageIndex; // 0x28
	private Int32 m_cachedLoadSeqNum; // 0x2c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RebuildListIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0_NotifyFocusPage; // 0x10
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x18


	// RVA: 0x311ea00 VA: 0x7595736a00
	public Void .ctor(ActMultiV3TitlePagerView closure) { }
	// RVA: 0x311e2d8 VA: 0x75957362d8
	public Void RebuildListIfNeeded(ActMultiV3ManualTitleListModel model) { }
	// RVA: 0x311e62c VA: 0x759573662c
	public Void NotifyFocusPage(Int32 pageIdx) { }
	// RVA: 0x311ee3c VA: 0x7595736e3c
	public override IList`1 GenerateViewsForRebuild() { }
}
```