# KeyList

**Namespace:** ` `


## Fields

- `SortedList sortedList`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class KeyList : IList, ICollection, IEnumerable
{
	private SortedList sortedList; // 0x10

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Object Item { get; set; }

	// RVA: 0x60807c8 VA: 0x75986987c8
	internal Void .ctor(SortedList sortedList) { }
	// RVA: 0x60823ac VA: 0x759869a3ac
	public virtual Int32 get_Count() { }
	// RVA: 0x60823c8 VA: 0x759869a3c8
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x60823d0 VA: 0x759869a3d0
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x60823d8 VA: 0x759869a3d8
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x60823fc VA: 0x759869a3fc
	public virtual Object get_SyncRoot() { }
	// RVA: 0x6082420 VA: 0x759869a420
	public virtual Int32 Add(Object key) { }
	// RVA: 0x6082470 VA: 0x759869a470
	public virtual Void Clear() { }
	// RVA: 0x60824c0 VA: 0x759869a4c0
	public virtual Boolean Contains(Object key) { }
	// RVA: 0x60824e4 VA: 0x759869a4e4
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x60825b4 VA: 0x759869a5b4
	public virtual Void Insert(Int32 index, Object value) { }
	// RVA: 0x6082604 VA: 0x759869a604
	public virtual Object get_Item(Int32 index) { }
	// RVA: 0x6082628 VA: 0x759869a628
	public virtual Void set_Item(Int32 index, Object value) { }
	// RVA: 0x6082678 VA: 0x759869a678
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x6082708 VA: 0x759869a708
	public virtual Int32 IndexOf(Object key) { }
	// RVA: 0x60827d4 VA: 0x759869a7d4
	public virtual Void Remove(Object key) { }
	// RVA: 0x6082824 VA: 0x759869a824
	public virtual Void RemoveAt(Int32 index) { }
}
```