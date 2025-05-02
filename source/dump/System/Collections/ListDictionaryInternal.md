# ListDictionaryInternal

**Namespace:** `System.Collections`


## Fields

- `DictionaryNode head`

- `Int32 version`

- `Int32 count`

- `Object _syncRoot`


## Properties

- `Object Item`

- `Int32 Count`

- `ICollection Keys`

- `Boolean IsReadOnly`

- `Boolean IsFixedSize`

- `Boolean IsSynchronized`

- `Object SyncRoot`

- `ICollection Values`


## Methods

- `Object get_Item(Object)`

- `Void set_Item(Object, Object)`

- `Int32 get_Count()`

- `ICollection get_Keys()`

- `Boolean get_IsReadOnly()`

- `Boolean get_IsFixedSize()`

- `Boolean get_IsSynchronized()`

- `Object get_SyncRoot()`

- `ICollection get_Values()`

- `Void Add(Object, Object)`

- `Void Clear()`

- `Boolean Contains(Object)`

- `Void CopyTo(Array, Int32)`

- `IDictionaryEnumerator GetEnumerator()`

- `Void Remove(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
internal class ListDictionaryInternal : IDictionary, ICollection, IEnumerable
{
	private DictionaryNode head; // 0x10
	private Int32 version; // 0x18
	private Int32 count; // 0x1c
	private Object _syncRoot; // 0x20

	public Object Item { get; set; }
	public Int32 Count { get; }
	public ICollection Keys { get; }
	public Boolean IsReadOnly { get; }
	public Boolean IsFixedSize { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	public ICollection Values { get; }

	// RVA: 0x607c208 VA: 0x7598694208
	public Void .ctor() { }
	// RVA: 0x607c210 VA: 0x7598694210
	public Object get_Item(Object key) { }
	// RVA: 0x607c2c8 VA: 0x75986942c8
	public Void set_Item(Object key, Object value) { }
	// RVA: 0x607c454 VA: 0x7598694454
	public Int32 get_Count() { }
	// RVA: 0x607c45c VA: 0x759869445c
	public ICollection get_Keys() { }
	// RVA: 0x607c510 VA: 0x7598694510
	public Boolean get_IsReadOnly() { }
	// RVA: 0x607c518 VA: 0x7598694518
	public Boolean get_IsFixedSize() { }
	// RVA: 0x607c520 VA: 0x7598694520
	public Boolean get_IsSynchronized() { }
	// RVA: 0x607c528 VA: 0x7598694528
	public Object get_SyncRoot() { }
	// RVA: 0x607c5a0 VA: 0x75986945a0
	public ICollection get_Values() { }
	// RVA: 0x607c614 VA: 0x7598694614
	public Void Add(Object key, Object value) { }
	// RVA: 0x607c7dc VA: 0x75986947dc
	public Void Clear() { }
	// RVA: 0x607c80c VA: 0x759869480c
	public Boolean Contains(Object key) { }
	// RVA: 0x607c8c4 VA: 0x75986948c4
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x607cadc VA: 0x7598694adc
	public IDictionaryEnumerator GetEnumerator() { }
	// RVA: 0x607cb94 VA: 0x7598694b94
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x607cbf4 VA: 0x7598694bf4
	public Void Remove(Object key) { }
}
```