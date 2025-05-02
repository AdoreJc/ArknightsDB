# CollectionWrapper

**Namespace:** `Newtonsoft.Json.Utilities`


## Fields

- `Object _syncRoot`


## Properties

- `Object UnderlyingCollection`


## Methods

- `Object get_UnderlyingCollection()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class CollectionWrapper`1 : ICollection`1, IEnumerable`1, IEnumerable, IWrappedCollection, IList, ICollection
{
	private readonly IList _list; // 0x0
	private readonly ICollection`1 _genericCollection; // 0x0
	private Object _syncRoot; // 0x0

	public virtual Int32 Count { get; }
	public virtual Boolean IsReadOnly { get; }
	private Boolean System.Collections.IList.IsFixedSize { get; }
	private Object System.Collections.IList.Item { get; set; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public Object UnderlyingCollection { get; }

	// RVA: 0x VA: 0x0
	public virtual Void Add(T item) { }
	// RVA: 0x VA: 0x0
	public virtual Void Clear() { }
	// RVA: 0x VA: 0x0
	public virtual Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public virtual Void CopyTo(T[] array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	public virtual Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	public virtual Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	public virtual IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.Add(Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.Contains(Object value) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IList.IndexOf(Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.RemoveAt(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Insert(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IList.get_IsFixedSize() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.Remove(Object value) { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IList.get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IList.set_Item(Int32 index, Object value) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 arrayIndex) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private static Void VerifyValueType(Object value) { }
	// RVA: 0x VA: 0x0
	private static Boolean IsCompatibleObject(Object value) { }
	// RVA: 0x VA: 0x0
	public Object get_UnderlyingCollection() { }
}
```