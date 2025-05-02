# StandardValuesCollection

**Namespace:** ` `


## Fields

- `ICollection values`

- `Array valueArray`


## Properties

- `Int32 Count`

- `Object Item`


## Methods

- `Int32 get_Count()`

- `Object get_Item(Int32)`

- `Void CopyTo(Array, Int32)`

- `IEnumerator GetEnumerator()`


## Dump
```C#
// Dll : System.dll
// Namespace : 
public class StandardValuesCollection : ICollection, IEnumerable
{
	private ICollection values; // 0x10
	private Array valueArray; // 0x18

	public Int32 Count { get; }
	public Object Item { get; }
	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x63f420c VA: 0x7598a0c20c
	public Void .ctor(ICollection values) { }
	// RVA: 0x63f42d0 VA: 0x7598a0c2d0
	public Int32 get_Count() { }
	// RVA: 0x63f438c VA: 0x7598a0c38c
	public Object get_Item(Int32 index) { }
	// RVA: 0x63f4598 VA: 0x7598a0c598
	public Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x63f4650 VA: 0x7598a0c650
	public IEnumerator GetEnumerator() { }
	// RVA: 0x63f46f0 VA: 0x7598a0c6f0
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x63f46f4 VA: 0x7598a0c6f4
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x63f46fc VA: 0x7598a0c6fc
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x63f4704 VA: 0x7598a0c704
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x63f4708 VA: 0x7598a0c708
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```