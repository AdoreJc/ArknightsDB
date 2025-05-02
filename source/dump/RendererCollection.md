# RendererCollection

**Namespace:** ` `


## Fields

- `ScreenEffectHolder m_holder`

- `Boolean m_isInited`

- `UIRendererSortingInfoStorage m_sortingInfo`

- `UIPage m_registeredPage`


## Methods

- `Void InitSortingInfo(SortingInfo)`

- `Void AdjustToTargetLayer(SortingInfo)`

- `Void RestoreLayers()`

- `Void Dispose()`

- `Void _InitCacheIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RendererCollection : IPageUIRenderer, IHotfixable, IDisposable
{
	private ScreenEffectHolder m_holder; // 0x10
	private Boolean m_isInited; // 0x18
	private UIRendererSortingInfoStorage m_sortingInfo; // 0x20
	private UIPage m_registeredPage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitSortingInfo; // 0x8
	private static DelegateBridge __Hotfix0_AdjustToTargetLayer; // 0x10
	private static DelegateBridge __Hotfix0_RestoreLayers; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20
	private static DelegateBridge __Hotfix0__InitCacheIfNot; // 0x28


	// RVA: 0x341f60c VA: 0x7595a3760c
	public Void .ctor(UIPage page, ScreenEffectHolder holder) { }
	// RVA: 0x341fc90 VA: 0x7595a37c90
	public Void InitSortingInfo(SortingInfo sortingInfo) { }
	// RVA: 0x341feb0 VA: 0x7595a37eb0
	public Void AdjustToTargetLayer(SortingInfo sortingInfo) { }
	// RVA: 0x341ff64 VA: 0x7595a37f64
	public Void RestoreLayers() { }
	// RVA: 0x341f8f4 VA: 0x7595a378f4
	public Void Dispose() { }
	// RVA: 0x341fd44 VA: 0x7595a37d44
	private Void _InitCacheIfNot() { }
}
```