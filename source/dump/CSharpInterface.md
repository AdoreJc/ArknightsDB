# CSharpInterface

**Namespace:** ` `


## Fields

- `LuaVirtualViewAdapter m_adapter`


## Methods

- `Void DisposeFromLua()`

- `Void AddViewTypeDefine(Int32, LuaLayout)`

- `Void RebuildAllViews()`

- `Void AddView(Int32, Single)`

- `Void InsertView(Int32, Int32, Single)`

- `Void RemoveView(Int32)`

- `Void RemoveAllViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CSharpInterface : ILuaCallCSharp
{
	private LuaVirtualViewAdapter m_adapter; // 0x10


	// RVA: 0x220d814 VA: 0x7594825814
	private Void .ctor() { }
	// RVA: 0x220d81c VA: 0x759482581c
	public Void DisposeFromLua() { }
	// RVA: 0x220d834 VA: 0x7594825834
	public Void AddViewTypeDefine(Int32 viewType, LuaLayout prefab) { }
	// RVA: 0x220d84c VA: 0x759482584c
	public Void RebuildAllViews() { }
	// RVA: 0x220d864 VA: 0x7594825864
	public Void AddView(Int32 viewType, Single initSize) { }
	// RVA: 0x220d87c VA: 0x759482587c
	public Void InsertView(Int32 indexFrom1, Int32 viewType, Single initSize) { }
	// RVA: 0x220d894 VA: 0x7594825894
	public Void RemoveView(Int32 indexFrom1) { }
	// RVA: 0x220d8ac VA: 0x75948258ac
	public Void RemoveAllViews() { }
	// RVA: 0x220d8c4 VA: 0x75948258c4
	public static CSharpInterface BindAdapterToLayout(ILuaObject luaObj, UIRecycleLayoutGroup layout) { }
}
```