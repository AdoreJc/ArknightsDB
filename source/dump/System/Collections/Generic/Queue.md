# Queue

**Namespace:** `System.Collections.Generic`


## Fields

- `Int32 _head`

- `Int32 _tail`

- `Int32 _size`

- `Int32 _version`

- `Object _syncRoot`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void Clear()`

- `Void Enqueue(T)`

- `Enumerator GetEnumerator()`

- `T Dequeue()`

- `T Peek()`

- `Boolean Contains(T)`

- `Void SetCapacity(Int32)`

- `Void MoveNext(ref)`

- `Void ThrowForEmptyQueue()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Generic
public class Queue`1 : IEnumerable`1, IEnumerable, ICollection, IReadOnlyCollection`1
{
	private T[] _array; // 0x0
	private Int32 _head; // 0x0
	private Int32 _tail; // 0x0
	private Int32 _size; // 0x0
	private Int32 _version; // 0x0
	private Object _syncRoot; // 0x0
	private const Int32 MinimumGrow; // 0x0
	private const Int32 GrowFactor; // 0x0

	public Int32 Count { get; }
	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void Enqueue(T item) { }
	// RVA: 0x VA: 0x0
	public Enumerator GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 System.Collections.Generic.IEnumerable<T>.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public T Dequeue() { }
	// RVA: 0x VA: 0x0
	public T Peek() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public T[] ToArray() { }
	// RVA: 0x VA: 0x0
	private Void SetCapacity(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	private Void MoveNext(ref Int32 index) { }
	// RVA: 0x VA: 0x0
	private Void ThrowForEmptyQueue() { }
}
```