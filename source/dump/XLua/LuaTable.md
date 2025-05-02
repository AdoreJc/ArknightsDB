# LuaTable

**Namespace:** `XLua`


## Properties

- `Object Item`

- `Object Item`

- `Int32 Length`


## Methods

- `Void Get(TKey, out)`

- `Boolean ContainsKey(TKey)`

- `Void Set(TKey, TValue)`

- `T GetInPath(String)`

- `Void SetInPath(String, T)`

- `Object get_Item(String)`

- `Void set_Item(String, Object)`

- `Object get_Item(Object)`

- `Void set_Item(Object, Object)`

- `Void ForEach(Action`2)`

- `Int32 get_Length()`

- `IEnumerable GetKeys()`

- `T Get(Object)`

- `TValue Get(TKey)`

- `TValue Get(String)`

- `Void SetMetaTable(LuaTable)`

- `T Cast()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class LuaTable : LuaBase
{

	public Object Item { get; set; }
	public Object Item { get; set; }
	public Int32 Length { get; }

	// RVA: 0x3edcdf0 VA: 0x75964f4df0
	public Void .ctor(Int32 reference, LuaEnv luaenv) { }
	// RVA: 0x VA: 0x0
	public Void Get(TKey key, out TValue value) { }
	// RVA: 0x VA: 0x0
	public Boolean ContainsKey(TKey key) { }
	// RVA: 0x VA: 0x0
	public Void Set(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public T GetInPath(String path) { }
	// RVA: 0x VA: 0x0
	public Void SetInPath(String path, T val) { }
	// RVA: 0x3edce28 VA: 0x75964f4e28
	public Object get_Item(String field) { }
	// RVA: 0x3edce80 VA: 0x75964f4e80
	public Void set_Item(String field, Object value) { }
	// RVA: 0x3edcee0 VA: 0x75964f4ee0
	public Object get_Item(Object field) { }
	// RVA: 0x3edcf38 VA: 0x75964f4f38
	public Void set_Item(Object field, Object value) { }
	// RVA: 0x VA: 0x0
	public Void ForEach(Action`2 action) { }
	// RVA: 0x3edcf98 VA: 0x75964f4f98
	public Int32 get_Length() { }
	// RVA: 0x3edd0d0 VA: 0x75964f50d0
	public IEnumerable GetKeys() { }
	// RVA: 0x VA: 0x0
	public IEnumerable`1 GetKeys() { }
	// RVA: 0x VA: 0x0
	public T Get(Object key) { }
	// RVA: 0x VA: 0x0
	public TValue Get(TKey key) { }
	// RVA: 0x VA: 0x0
	public TValue Get(String key) { }
	// RVA: 0x3edd188 VA: 0x75964f5188
	public Void SetMetaTable(LuaTable metaTable) { }
	// RVA: 0x VA: 0x0
	public T Cast() { }
	// RVA: 0x3edd2fc VA: 0x75964f52fc
	internal override Void push(IntPtr L) { }
	// RVA: 0x3edd310 VA: 0x75964f5310
	public override String ToString() { }
}
```