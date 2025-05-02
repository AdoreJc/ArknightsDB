# LuaVirtualViewAdapter

**Namespace:** `Torappu.UI`


## Fields

- `ILuaObject m_luaObj`

- `Context m_context`


## Methods

- `Void Dispose()`

- `Void _BindViewToLua(VirtualView, LuaLayout)`

- `Void _RebuildAllViews()`

- `Void _InsertView(Int32, Int32, Single)`

- `Void _AddView(Int32, Single)`

- `Void _RemoveView(Int32)`

- `Void _RemoveAllViews()`

- `Void _AddViewTypeDefine(Int32, LuaLayout)`

- `Context _EnsureContext()`

- `VirtualView _CreateVirtualView(Int32, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LuaVirtualViewAdapter : UIRecycleLayoutAdapter, IDisposable
{
	private ILuaObject m_luaObj; // 0x18
	private List`1 m_views; // 0x20
	private ListDict`2 m_viewTypeToPrefab; // 0x28
	private Context m_context; // 0x30
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0__BindViewToLua; // 0x10
	private static DelegateBridge __Hotfix0__RebuildAllViews; // 0x18
	private static DelegateBridge __Hotfix0__InsertView; // 0x20
	private static DelegateBridge __Hotfix0__AddView; // 0x28
	private static DelegateBridge __Hotfix0__RemoveView; // 0x30
	private static DelegateBridge __Hotfix0__RemoveAllViews; // 0x38
	private static DelegateBridge __Hotfix0__AddViewTypeDefine; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0__EnsureContext; // 0x50
	private static DelegateBridge __Hotfix0__CreateVirtualView; // 0x58


	// RVA: 0x220c75c VA: 0x759482475c
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x220c7c4 VA: 0x75948247c4
	public Void Dispose() { }
	// RVA: 0x220c870 VA: 0x7594824870
	private Void _BindViewToLua(VirtualView view, LuaLayout layout) { }
	// RVA: 0x220ca4c VA: 0x7594824a4c
	private Void _RebuildAllViews() { }
	// RVA: 0x220cb98 VA: 0x7594824b98
	private Void _InsertView(Int32 indexFrom1, Int32 viewType, Single initSize) { }
	// RVA: 0x220cedc VA: 0x7594824edc
	private Void _AddView(Int32 viewType, Single initSize) { }
	// RVA: 0x220d0a0 VA: 0x75948250a0
	private Void _RemoveView(Int32 indexFrom1) { }
	// RVA: 0x220d208 VA: 0x7594825208
	private Void _RemoveAllViews() { }
	// RVA: 0x220d324 VA: 0x7594825324
	private Void _AddViewTypeDefine(Int32 viewType, LuaLayout prefab) { }
	// RVA: 0x220d3d0 VA: 0x75948253d0
	private Void .ctor(ILuaObject luaObj) { }
	// RVA: 0x220d574 VA: 0x7594825574
	private Context _EnsureContext() { }
	// RVA: 0x220cd34 VA: 0x7594824d34
	private VirtualView _CreateVirtualView(Int32 viewType, Single initSize) { }
}
```