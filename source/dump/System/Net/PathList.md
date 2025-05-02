# PathList

**Namespace:** `System.Net`


## Fields

- `SortedList m_list`


## Properties

- `Int32 Count`

- `ICollection Values`

- `Object Item`

- `Object SyncRoot`


## Methods

- `Int32 get_Count()`

- `Int32 GetCookiesCount()`

- `ICollection get_Values()`

- `Object get_Item(String)`

- `Void set_Item(String, Object)`

- `IEnumerator GetEnumerator()`

- `Object get_SyncRoot()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class PathList
{
	private SortedList m_list; // 0x10

	public Int32 Count { get; }
	public ICollection Values { get; }
	public Object Item { get; set; }
	public Object SyncRoot { get; }

	// RVA: 0x643ae4c VA: 0x7598a52e4c
	public Void .ctor() { }
	// RVA: 0x643cb6c VA: 0x7598a54b6c
	public Int32 get_Count() { }
	// RVA: 0x643af00 VA: 0x7598a52f00
	public Int32 GetCookiesCount() { }
	// RVA: 0x643c9dc VA: 0x7598a549dc
	public ICollection get_Values() { }
	// RVA: 0x643b368 VA: 0x7598a53368
	public Object get_Item(String s) { }
	// RVA: 0x643b38c VA: 0x7598a5338c
	public Void set_Item(String s, Object value) { }
	// RVA: 0x643e1d0 VA: 0x7598a561d0
	public IEnumerator GetEnumerator() { }
	// RVA: 0x643b344 VA: 0x7598a53344
	public Object get_SyncRoot() { }
}
```