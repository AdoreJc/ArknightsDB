# SettingsPropertyCollection

**Namespace:** `System.Configuration`


## Properties

- `Int32 Count`

- `Boolean IsSynchronized`

- `SettingsProperty Item`

- `Object SyncRoot`


## Methods

- `Int32 get_Count()`

- `Boolean get_IsSynchronized()`

- `SettingsProperty get_Item(String)`

- `Object get_SyncRoot()`

- `Void Add(SettingsProperty)`

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
public class SettingsPropertyCollection : ICollection, IEnumerable, ICloneable
{

	public Int32 Count { get; }
	public Boolean IsSynchronized { get; }
	public SettingsProperty Item { get; }
	public Object SyncRoot { get; }

	// RVA: 0x63644c4 VA: 0x759897c4c4
	public Void .ctor() { }
	// RVA: 0x63644fc VA: 0x759897c4fc
	public Int32 get_Count() { }
	// RVA: 0x6364534 VA: 0x759897c534
	public Boolean get_IsSynchronized() { }
	// RVA: 0x636456c VA: 0x759897c56c
	public SettingsProperty get_Item(String name) { }
	// RVA: 0x63645a4 VA: 0x759897c5a4
	public Object get_SyncRoot() { }
	// RVA: 0x63645dc VA: 0x759897c5dc
	public Void Add(SettingsProperty property) { }
	// RVA: 0x6364614 VA: 0x759897c614
	public Void Clear() { }
	// RVA: 0x636464c VA: 0x759897c64c
	public Object Clone() { }
	// RVA: 0x6364684 VA: 0x759897c684
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x63646bc VA: 0x759897c6bc
	public IEnumerator GetEnumerator() { }
	// RVA: 0x63646f4 VA: 0x759897c6f4
	protected virtual Void OnAdd(SettingsProperty property) { }
	// RVA: 0x636472c VA: 0x759897c72c
	protected virtual Void OnAddComplete(SettingsProperty property) { }
	// RVA: 0x6364764 VA: 0x759897c764
	protected virtual Void OnClear() { }
	// RVA: 0x636479c VA: 0x759897c79c
	protected virtual Void OnClearComplete() { }
	// RVA: 0x63647d4 VA: 0x759897c7d4
	protected virtual Void OnRemove(SettingsProperty property) { }
	// RVA: 0x636480c VA: 0x759897c80c
	protected virtual Void OnRemoveComplete(SettingsProperty property) { }
	// RVA: 0x6364844 VA: 0x759897c844
	public Void Remove(String name) { }
	// RVA: 0x636487c VA: 0x759897c87c
	public Void SetReadOnly() { }
}
```