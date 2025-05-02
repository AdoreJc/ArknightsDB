# ValueList

**Namespace:** ` `


## Fields

- `SortedList sortedList`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class ValueList : IList, ICollection, IEnumerable
{
	private SortedList sortedList; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Object Item { get; set; }

	// RVA: 0x6080884 VA: 0x7598698884
	internal Void .ctor(SortedList sortedList) { }
	// RVA: 0x6082874 VA: 0x759869a874
	public virtual Int32 get_Count() { }
	// RVA: 0x6082890 VA: 0x759869a890
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x6082898 VA: 0x759869a898
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x60828a0 VA: 0x759869a8a0
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x60828c4 VA: 0x759869a8c4
	public virtual Object get_SyncRoot() { }
	// RVA: 0x60828e8 VA: 0x759869a8e8
	public virtual Int32 Add(Object key) { }
	// RVA: 0x6082938 VA: 0x759869a938
	public virtual Void Clear() { }
	// RVA: 0x6082988 VA: 0x759869a988
	public virtual Boolean Contains(Object value) { }
	// RVA: 0x60829ac VA: 0x759869a9ac
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6082a7c VA: 0x759869aa7c
	public virtual Void Insert(Int32 index, Object value) { }
	// RVA: 0x6082acc VA: 0x759869aacc
	public virtual Object get_Item(Int32 index) { }
	// RVA: 0x6082af0 VA: 0x759869aaf0
	public virtual Void set_Item(Int32 index, Object value) { }
	// RVA: 0x6082b40 VA: 0x759869ab40
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x6082bd0 VA: 0x759869abd0
	public virtual Int32 IndexOf(Object value) { }
	// RVA: 0x6082c48 VA: 0x759869ac48
	public virtual Void Remove(Object value) { }
	// RVA: 0x6082c98 VA: 0x759869ac98
	public virtual Void RemoveAt(Int32 index) { }
}
```