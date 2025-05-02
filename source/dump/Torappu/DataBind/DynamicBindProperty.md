# DynamicBindProperty

**Namespace:** `Torappu.DataBind`


## Methods

- `Void Bind(TBinder)`

- `Void _BindImpl(IDataBinder)`

- `Void Unbind(TBinder)`

- `Void _UnbindImpl(IDataBinder)`

- `Void BindPlain(TPlainBinder)`

- `Void UnbindPlain(TPlainBinder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataBind
public class DynamicBindProperty`2 : BindProperty`1
{
	private static List`1 s_traverseCache; // 0x0
	private List`1 m_dynamicBinders; // 0x0


	// RVA: 0x VA: 0x0
	public Void Bind(TBinder binder) { }
	// RVA: 0x VA: 0x0
	private Void _BindImpl(IDataBinder binder) { }
	// RVA: 0x VA: 0x0
	public Void Unbind(TBinder binder) { }
	// RVA: 0x VA: 0x0
	private Void _UnbindImpl(IDataBinder binder) { }
	// RVA: 0x VA: 0x0
	public Void BindPlain(TPlainBinder binder) { }
	// RVA: 0x VA: 0x0
	public Void UnbindPlain(TPlainBinder binder) { }
	// RVA: 0x VA: 0x0
	public override Void LuaDataBinder_AddOrRemove(LuaDataBinder luaDataBinder, Boolean add) { }
	// RVA: 0x VA: 0x0
	public override Void Update(DataBindSystem system) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```