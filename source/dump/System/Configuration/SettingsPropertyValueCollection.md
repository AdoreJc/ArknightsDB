# SettingsPropertyValueCollection

**Namespace:** `System.Configuration`


## Properties

- `Int32 Count`

- `Boolean IsSynchronized`

- `SettingsPropertyValue Item`

- `Object SyncRoot`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsSynchronized()`

- `SettingsPropertyValue get_Item(String)`

- `Object get_SyncRoot()`

- `Void Add(SettingsPropertyValue)`

- `Void Clear()`

- `Object Clone()`

- `Void CopyTo(Array, Int32)`

- `IEnumerator GetEnumerator()`

- `Void Remove(String)`

- `Void SetReadOnly()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class SettingsPropertyValueCollection : ICollection, IEnumerable, ICloneable
{

	public Int32 Count { get; }
	public Boolean IsSynchronized { get; }
	public SettingsPropertyValue Item { get; }
	public Object SyncRoot { get; }

	// RVA: 0x6364d4c VA: 0x759897cd4c
	public Void .ctor() { }
	// RVA: 0x6364d84 VA: 0x759897cd84
	public Int32 get_Count() { }
	// RVA: 0x6364dbc VA: 0x759897cdbc
	public Boolean get_IsSynchronized() { }
	// RVA: 0x6364df4 VA: 0x759897cdf4
	public SettingsPropertyValue get_Item(String name) { }
	// RVA: 0x6364e2c VA: 0x759897ce2c
	public Object get_SyncRoot() { }
	// RVA: 0x6364e64 VA: 0x759897ce64
	public Void Add(SettingsPropertyValue property) { }
	// RVA: 0x6364e9c VA: 0x759897ce9c
	public Void Clear() { }
	// RVA: 0x6364ed4 VA: 0x759897ced4
	public Object Clone() { }
	// RVA: 0x6364f0c VA: 0x759897cf0c
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x6364f44 VA: 0x759897cf44
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6364f7c VA: 0x759897cf7c
	public Void Remove(String name) { }
	// RVA: 0x6364fb4 VA: 0x759897cfb4
	public Void SetReadOnly() { }
}
```