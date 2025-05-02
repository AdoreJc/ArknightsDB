# StringCollection

**Namespace:** `System.Collections.Specialized`


## Properties

- `String Item`

- `Int32 Count`

- `Boolean IsSynchronized`

- `Object SyncRoot`


## Methods

- `String get_Item(Int32)`

- `Void set_Item(Int32, String)`

- `Int32 get_Count()`

- `Int32 Add(String)`

- `Void Clear()`

- `Boolean Contains(String)`

- `Void CopyTo(String[], Int32)`

- `Int32 IndexOf(String)`

- `Void Insert(Int32, String)`

- `Boolean get_IsSynchronized()`

- `Void Remove(String)`

- `Void RemoveAt(Int32)`

- `Object get_SyncRoot()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Specialized
public class StringCollection : IList, ICollection, IEnumerable
{
	private readonly ArrayList data; // 0x10

	public String Item { get; set; }
	public Int32 Count { get; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	public Boolean IsSynchronized { get; }
	public Object SyncRoot { get; }
	private Object System.Collections.IList.Item { get; set; }

	// RVA: 0x640ceb8 VA: 0x7598a24eb8
	public String get_Item(Int32 index) { }
	// RVA: 0x640cf34 VA: 0x7598a24f34
	public Void set_Item(Int32 index, String value) { }
	// RVA: 0x640cf58 VA: 0x7598a24f58
	public Int32 get_Count() { }
	// RVA: 0x640cf7c VA: 0x7598a24f7c
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x640cf84 VA: 0x7598a24f84
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x640cf8c VA: 0x7598a24f8c
	public Int32 Add(String value) { }
	// RVA: 0x640cfb0 VA: 0x7598a24fb0
	public Void Clear() { }
	// RVA: 0x640cfd4 VA: 0x7598a24fd4
	public Boolean Contains(String value) { }
	// RVA: 0x640cff8 VA: 0x7598a24ff8
	public Void CopyTo(String[] array, Int32 index) { }
	// RVA: 0x640d01c VA: 0x7598a2501c
	public Int32 IndexOf(String value) { }
	// RVA: 0x640d040 VA: 0x7598a25040
	public Void Insert(Int32 index, String value) { }
	// RVA: 0x640d064 VA: 0x7598a25064
	public Boolean get_IsSynchronized() { }
	// RVA: 0x640d06c VA: 0x7598a2506c
	public Void Remove(String value) { }
	// RVA: 0x640d090 VA: 0x7598a25090
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x640d0b4 VA: 0x7598a250b4
	public Object get_SyncRoot() { }
	// RVA: 0x640d0d8 VA: 0x7598a250d8
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x640d0dc VA: 0x7598a250dc
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x640d168 VA: 0x7598a25168
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x640d1e4 VA: 0x7598a251e4
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x640d260 VA: 0x7598a25260
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x640d2dc VA: 0x7598a252dc
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x640d368 VA: 0x7598a25368
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x640d3e4 VA: 0x7598a253e4
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x640d408 VA: 0x7598a25408
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x640d42c VA: 0x7598a2542c
	public Void .ctor() { }
}
```