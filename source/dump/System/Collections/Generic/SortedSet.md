# SortedSet

**Namespace:** `System.Collections.Generic`


## Fields

- `Node root`

- `Int32 count`

- `Int32 version`

- `Object _syncRoot`

- `SerializationInfo siInfo`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Boolean Add(T)`

- `Boolean Remove(T)`

- `Void CopyTo(T[], Int32)`

- `Void CopyTo(T[], Int32, Int32)`

- `Enumerator GetEnumerator()`

- `Void InsertionBalance(Node, ref, Node, Node)`

- `Void ReplaceChildOrRoot(Node, Node, Node)`

- `Void ReplaceNode(Node, Node, Node, Node)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Generic
public class SortedSet`1 : ICollection`1, IEnumerable`1, IEnumerable, ICollection, IReadOnlyCollection`1, ISerializable, IDeserializationCallback
{
	private Node root; // 0x0
	private IComparer`1 comparer; // 0x0
	private Int32 count; // 0x0
	private Int32 version; // 0x0
	private Object _syncRoot; // 0x0
	private SerializationInfo siInfo; // 0x0

	public Int32 Count { get; }
	private Boolean System.Collections.Generic.ICollection<T>.IsReadOnly { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IComparer`1 comparer) { }
	// RVA: 0x VA: 0x0
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	internal virtual Boolean InOrderTreeWalk(TreeWalkPredicate`1 action) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.Generic.ICollection<T>.get_IsReadOnly() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	internal virtual Void VersionCheck() { }
	// RVA: 0x VA: 0x0
	internal virtual Boolean IsWithinRange(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Add(T item) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.Generic.ICollection<T>.Add(T item) { }
	// RVA: 0x VA: 0x0
	internal virtual Boolean AddIfNotPresent(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T item) { }
	// RVA: 0x VA: 0x0
	internal virtual Boolean DoRemove(T item) { }
	// RVA: 0x VA: 0x0
	public virtual Void Clear() { }
	// RVA: 0x VA: 0x0
	public virtual Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index, Int32 count) { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void InsertionBalance(Node current, ref Node parent, Node grandParent, Node greatGrandParent) { }
	// RVA: 0x VA: 0x0
	private Void ReplaceChildOrRoot(Node parent, Node child, Node newChild) { }
	// RVA: 0x VA: 0x0
	private Void ReplaceNode(Node match, Node parentOfMatch, Node successor, Node parentOfSuccessor) { }
	// RVA: 0x VA: 0x0
	internal virtual Node FindNode(T item) { }
	// RVA: 0x VA: 0x0
	internal Void UpdateVersion() { }
	// RVA: 0x VA: 0x0
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	protected virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x VA: 0x0
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnDeserialization(Object sender) { }
	// RVA: 0x VA: 0x0
	private static Int32 Log2(Int32 value) { }
}
```