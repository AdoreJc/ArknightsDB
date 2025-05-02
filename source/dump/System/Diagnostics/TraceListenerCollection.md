# TraceListenerCollection

**Namespace:** `System.Diagnostics`


## Fields

- `ArrayList list`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Int32 Add(TraceListener)`

- `Void Clear()`

- `IEnumerator GetEnumerator()`

- `Void RemoveAt(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public class TraceListenerCollection : IList, ICollection, IEnumerable
{
	private ArrayList list; // 0x10

	public Int32 Count { get; }
	private Object System.Collections.IList.Item { get; set; }
	private Boolean System.Collections.IList.IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }

	// RVA: 0x6396c48 VA: 0x75989aec48
	internal Void .ctor() { }
	// RVA: 0x63979dc VA: 0x75989af9dc
	public Int32 get_Count() { }
	// RVA: 0x6396df4 VA: 0x75989aedf4
	public Int32 Add(TraceListener listener) { }
	// RVA: 0x6397af4 VA: 0x75989afaf4
	public Void Clear() { }
	// RVA: 0x6397b5c VA: 0x75989afb5c
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6397a00 VA: 0x75989afa00
	internal Void InitializeListener(TraceListener listener) { }
	// RVA: 0x6397b80 VA: 0x75989afb80
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x6397ca0 VA: 0x75989afca0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x6397cc4 VA: 0x75989afcc4
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x6397dd4 VA: 0x75989afdd4
	private Boolean System.Collections.IList.get_IsReadOnly() { }
	// RVA: 0x6397ddc VA: 0x75989afddc
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x6397de4 VA: 0x75989afde4
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x6397fc8 VA: 0x75989affc8
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x6397fec VA: 0x75989affec
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x6398010 VA: 0x75989b0010
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x63981ec VA: 0x75989b01ec
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x639830c VA: 0x75989b030c
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x6398310 VA: 0x75989b0310
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x6398318 VA: 0x75989b0318
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
}
```