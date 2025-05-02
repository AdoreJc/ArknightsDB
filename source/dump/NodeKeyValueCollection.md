# NodeKeyValueCollection

**Namespace:** ` `


## Fields

- `ListDictionaryInternal list`

- `Boolean isKeys`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class NodeKeyValueCollection : ICollection, IEnumerable
{
	private ListDictionaryInternal list; // 0x10
	private Boolean isKeys; // 0x18

	private Int32 System.Collections.ICollection.Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x607c4d4 VA: 0x75986944d4
	public Void .ctor(ListDictionaryInternal list, Boolean isKeys) { }
	// RVA: 0x607d010 VA: 0x7598695010
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x607d1dc VA: 0x75986951dc
	private Int32 System.Collections.ICollection.get_Count() { }
	// RVA: 0x607d214 VA: 0x7598695214
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x607d21c VA: 0x759869521c
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x607d234 VA: 0x7598695234
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```