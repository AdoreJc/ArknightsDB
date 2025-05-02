# OrderedDictionaryKeyValueCollection

**Namespace:** ` `


## Fields

- `ArrayList _objects`

- `Boolean _isKeys`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class OrderedDictionaryKeyValueCollection : ICollection, IEnumerable
{
	private ArrayList _objects; // 0x10
	private Boolean _isKeys; // 0x18

	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x640b7d8 VA: 0x7598a237d8
	public Void .ctor(ArrayList array, Boolean isKeys) { }
	// RVA: 0x640c9f0 VA: 0x7598a249f0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x640cdec VA: 0x7598a24dec
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x640ce10 VA: 0x7598a24e10
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x640ce18 VA: 0x7598a24e18
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x640ce3c VA: 0x7598a24e3c
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```