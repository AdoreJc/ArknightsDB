# ArrayList

**Namespace:** `System.Collections`


## Fields

- `Int32 _size`

- `Int32 _version`

- `Object _syncRoot`


## Methods

- `Void EnsureCapacity(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
public class ArrayList : IList, ICollection, IEnumerable, ICloneable
{
	private Object[] _items; // 0x10
	private Int32 _size; // 0x18
	private Int32 _version; // 0x1c
	private Object _syncRoot; // 0x20

	public virtual Int32 Capacity { set; }
	public virtual Int32 Count { get; }
	public virtual Boolean IsFixedSize { get; }
	public virtual Boolean IsReadOnly { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }
	public virtual Object Item { get; set; }

	// RVA: 0x607dc74 VA: 0x7598695c74
	public Void .ctor() { }
	// RVA: 0x6083748 VA: 0x759869b748
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x6083894 VA: 0x759869b894
	public Void .ctor(ICollection c) { }
	// RVA: 0x6083a54 VA: 0x759869ba54
	public virtual Void set_Capacity(Int32 value) { }
	// RVA: 0x6083b88 VA: 0x759869bb88
	public virtual Int32 get_Count() { }
	// RVA: 0x6083b90 VA: 0x759869bb90
	public virtual Boolean get_IsFixedSize() { }
	// RVA: 0x6083b98 VA: 0x759869bb98
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x6083ba0 VA: 0x759869bba0
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x6083ba8 VA: 0x759869bba8
	public virtual Object get_SyncRoot() { }
	// RVA: 0x6083c20 VA: 0x759869bc20
	public virtual Object get_Item(Int32 index) { }
	// RVA: 0x6083cc8 VA: 0x759869bcc8
	public virtual Void set_Item(Int32 index, Object value) { }
	// RVA: 0x6083dbc VA: 0x759869bdbc
	public static ArrayList Adapter(IList list) { }
	// RVA: 0x6083eb0 VA: 0x759869beb0
	public virtual Int32 Add(Object value) { }
	// RVA: 0x6083fbc VA: 0x759869bfbc
	public virtual Void AddRange(ICollection c) { }
	// RVA: 0x6083fd8 VA: 0x759869bfd8
	public virtual Void Clear() { }
	// RVA: 0x6084014 VA: 0x759869c014
	public virtual Object Clone() { }
	// RVA: 0x608409c VA: 0x759869c09c
	public virtual Boolean Contains(Object item) { }
	// RVA: 0x608415c VA: 0x759869c15c
	public virtual Void CopyTo(Array array) { }
	// RVA: 0x6084170 VA: 0x759869c170
	public virtual Void CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x6084220 VA: 0x759869c220
	public virtual Void CopyTo(Int32 index, Array array, Int32 arrayIndex, Int32 count) { }
	// RVA: 0x6083f60 VA: 0x759869bf60
	private Void EnsureCapacity(Int32 min) { }
	// RVA: 0x6084328 VA: 0x759869c328
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x60844a4 VA: 0x759869c4a4
	public virtual Int32 IndexOf(Object value) { }
	// RVA: 0x60844bc VA: 0x759869c4bc
	public virtual Void Insert(Int32 index, Object value) { }
	// RVA: 0x60845f8 VA: 0x759869c5f8
	public virtual Void InsertRange(Int32 index, ICollection c) { }
	// RVA: 0x608485c VA: 0x759869c85c
	public static ArrayList ReadOnly(ArrayList list) { }
	// RVA: 0x6084944 VA: 0x759869c944
	public virtual Void Remove(Object obj) { }
	// RVA: 0x6084984 VA: 0x759869c984
	public virtual Void RemoveAt(Int32 index) { }
	// RVA: 0x6084a70 VA: 0x759869ca70
	public virtual Void RemoveRange(Int32 index, Int32 count) { }
	// RVA: 0x6084bdc VA: 0x759869cbdc
	public virtual Void Reverse() { }
	// RVA: 0x6084c14 VA: 0x759869cc14
	public virtual Void Reverse(Int32 index, Int32 count) { }
	// RVA: 0x6084d58 VA: 0x759869cd58
	public virtual Void Sort(IComparer comparer) { }
	// RVA: 0x6084da4 VA: 0x759869cda4
	public virtual Void Sort(Int32 index, Int32 count, IComparer comparer) { }
	// RVA: 0x6084ea8 VA: 0x759869cea8
	public virtual Object[] ToArray() { }
	// RVA: 0x6084f78 VA: 0x759869cf78
	public virtual Array ToArray(Type type) { }
}
```