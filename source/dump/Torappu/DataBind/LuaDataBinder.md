# LuaDataBinder

**Namespace:** `Torappu.DataBind`


## Fields

- `ILuaCallback m_luaCallback`


## Methods

- `Void BindToProperty(IBindProperty)`

- `Void Dispose()`

- `Void OnValueChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataBind
public class LuaDataBinder : IDataBinder, ILuaCallCSharp, IDisposable
{
	private ILuaCallback m_luaCallback; // 0x10
	private ListSet`1 m_bindedProps; // 0x18


	// RVA: 0x356e6d8 VA: 0x7595b866d8
	public Void .ctor(ILuaCallback luaInst) { }
	// RVA: 0x356e77c VA: 0x7595b8677c
	public Void BindToProperty(IBindProperty prop) { }
	// RVA: 0x356e858 VA: 0x7595b86858
	public Void Dispose() { }
	// RVA: 0x356ebb0 VA: 0x7595b86bb0
	public Void OnValueChanged(Object property) { }
}
```