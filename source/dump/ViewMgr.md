# ViewMgr

**Namespace:** ` `


## Fields

- `UIRecycleLayoutGroup m_closure`


## Methods

- `Void RebuildAll(UIRecycleLayoutAdapter)`

- `Void DetachView(IVirtualView, GameObject)`

- `Void AttachView(IVirtualView)`

- `IVirtualView GetView(Int32)`

- `Int32 GetViewCount()`

- `Boolean InsertView(Int32, IVirtualView)`

- `Boolean AddView(IVirtualView)`

- `Boolean RemoveView(IVirtualView)`

- `Void NotifyViewSizeChanged(IVirtualView)`

- `Void NotifyAllViewSizeChanged()`

- `Void NotifyRebuild()`

- `Single GetElementPosByIndex(Int32)`

- `ViewPool _EnsureViewPool(IVirtualView)`

- `Void _NotifyLayoutChanged(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class ViewMgr : IHotfixable, IViewHandler
{
	private UIRecycleLayoutGroup m_closure; // 0x10
	private ListDict`2 m_viewPools; // 0x18
	private List`1 m_views; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RebuildAll; // 0x8
	private static DelegateBridge __Hotfix0_GetViews; // 0x10
	private static DelegateBridge __Hotfix0_DetachView; // 0x18
	private static DelegateBridge __Hotfix0_AttachView; // 0x20
	private static DelegateBridge __Hotfix0_GetView; // 0x28
	private static DelegateBridge __Hotfix0_GetViewCount; // 0x30
	private static DelegateBridge __Hotfix0_InsertView; // 0x38
	private static DelegateBridge __Hotfix0_AddView; // 0x40
	private static DelegateBridge __Hotfix0_RemoveView; // 0x48
	private static DelegateBridge __Hotfix0_NotifyViewSizeChanged; // 0x50
	private static DelegateBridge __Hotfix0_NotifyAllViewSizeChanged; // 0x58
	private static DelegateBridge __Hotfix0_NotifyRebuild; // 0x60
	private static DelegateBridge __Hotfix0_GetElementPosByIndex; // 0x68
	private static DelegateBridge __Hotfix0__EnsureViewPool; // 0x70
	private static DelegateBridge __Hotfix0__NotifyLayoutChanged; // 0x78


	// RVA: 0x221018c VA: 0x759482818c
	public Void .ctor(UIRecycleLayoutGroup closure) { }
	// RVA: 0x2210f10 VA: 0x7594828f10
	public Void RebuildAll(UIRecycleLayoutAdapter adapter) { }
	// RVA: 0x2210c94 VA: 0x7594828c94
	public IList`1 GetViews() { }
	// RVA: 0x2210cfc VA: 0x7594828cfc
	public Void DetachView(IVirtualView view, GameObject curView) { }
	// RVA: 0x2210e08 VA: 0x7594828e08
	public Void AttachView(IVirtualView view) { }
	// RVA: 0x2211f98 VA: 0x7594829f98
	public IVirtualView GetView(Int32 index) { }
	// RVA: 0x2212994 VA: 0x759482a994
	public Int32 GetViewCount() { }
	// RVA: 0x2212a14 VA: 0x759482aa14
	public Boolean InsertView(Int32 index, IVirtualView view) { }
	// RVA: 0x2212ac0 VA: 0x759482aac0
	public Boolean AddView(IVirtualView view) { }
	// RVA: 0x2212b78 VA: 0x759482ab78
	public Boolean RemoveView(IVirtualView view) { }
	// RVA: 0x2212c18 VA: 0x759482ac18
	public Void NotifyViewSizeChanged(IVirtualView view) { }
	// RVA: 0x2212cb4 VA: 0x759482acb4
	public Void NotifyAllViewSizeChanged() { }
	// RVA: 0x2212d28 VA: 0x759482ad28
	public Void NotifyRebuild() { }
	// RVA: 0x220fdb0 VA: 0x7594827db0
	public Single GetElementPosByIndex(Int32 index) { }
	// RVA: 0x22126e4 VA: 0x759482a6e4
	private ViewPool _EnsureViewPool(IVirtualView view) { }
	// RVA: 0x2212d98 VA: 0x759482ad98
	private Void _NotifyLayoutChanged(Int32 fromIndex) { }
}
```