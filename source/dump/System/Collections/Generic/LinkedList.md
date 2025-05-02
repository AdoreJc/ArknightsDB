# LinkedList

**Namespace:** `System.Collections.Generic`


## Fields

- `Object _syncRoot`

- `SerializationInfo _siInfo`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void AddLast(LinkedListNode`1)`

- `Void Clear()`

- `Boolean Contains(T)`

- `Void CopyTo(T[], Int32)`

- `Enumerator GetEnumerator()`

- `Boolean Remove(T)`

- `Void Remove(LinkedListNode`1)`

- `Void RemoveFirst()`

- `Void InternalInsertNodeBefore(LinkedListNode`1, LinkedListNode`1)`

- `Void InternalInsertNodeToEmptyList(LinkedListNode`1)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Generic
public class LinkedList`1 : ICollection`1, IEnumerable`1, IEnumerable, ICollection, IReadOnlyCollection`1, ISerializable, IDeserializationCallback
{
	internal LinkedListNode`1 head; // 0x0
	internal Int32 count; // 0x0
	internal Int32 version; // 0x0
	private Object _syncRoot; // 0x0
	private SerializationInfo _siInfo; // 0x0
	private const String VersionName; // 0x0
	private const String CountName; // 0x0
	private const String ValuesName; // 0x0

	public Int32 Count { get; }
	public LinkedListNode`1 First { get; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public LinkedListNode`1 get_First() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<T>.Add(T value) { }
	// RVA: 0x VA: 0x0
	public LinkedListNode`1 AddFirst(T value) { }
	// RVA: 0x VA: 0x0
	public LinkedListNode`1 AddLast(T value) { }
	// RVA: 0x VA: 0x0
	public Void AddLast(LinkedListNode`1 node) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T value) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public LinkedListNode`1 Find(T value) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T value) { }
	// RVA: 0x VA: 0x0
	public Void Remove(LinkedListNode`1 node) { }
	// RVA: 0x VA: 0x0
	public Void RemoveFirst() { }
	// RVA: 0x VA: 0x0
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	public virtual Void OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	private Void InternalInsertNodeBefore(LinkedListNode`1 node, LinkedListNode`1 newNode) { }
	// RVA: 0x VA: 0x0
	private Void InternalInsertNodeToEmptyList(LinkedListNode`1 newNode) { }
	// RVA: 0x VA: 0x0
	internal Void InternalRemoveNode(LinkedListNode`1 node) { }
	// RVA: 0x VA: 0x0
	internal Void ValidateNewNode(LinkedListNode`1 node) { }
	// RVA: 0x VA: 0x0
	internal Void ValidateNode(LinkedListNode`1 node) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
}
```