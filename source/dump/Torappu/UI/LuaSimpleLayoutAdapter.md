# LuaSimpleLayoutAdapter

**Namespace:** `Torappu.UI`


## Fields

- `ILuaSimpleLayoutAdapter m_impl`


## Methods

- `Void _DisposeImpl()`

- `Void DisposeFromLua()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LuaSimpleLayoutAdapter : SimpleLayoutAdapter, IHotfixable
{
	private ILuaSimpleLayoutAdapter m_impl; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0__DisposeImpl; // 0x18
	private static DelegateBridge __Hotfix0_DisposeFromLua; // 0x20
	private static DelegateBridge __Hotfix0_BindAdapterToLayout; // 0x28

	public override Int32 count { get; }

	// RVA: 0x223eab4 VA: 0x7594856ab4
	private Void .ctor(ILuaSimpleLayoutAdapter impl) { }
	// RVA: 0x223ec08 VA: 0x7594856c08
	public override Int32 get_count() { }
	// RVA: 0x223ecec VA: 0x7594856cec
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x223effc VA: 0x7594856ffc
	private Void _DisposeImpl() { }
	// RVA: 0x223f06c VA: 0x759485706c
	public Void DisposeFromLua() { }
	// RVA: 0x223f0d4 VA: 0x75948570d4
	public static LuaSimpleLayoutAdapter BindAdapterToLayout(ILuaSimpleLayoutAdapter luaAdapter, SimpleLayoutContent layout) { }
}
```