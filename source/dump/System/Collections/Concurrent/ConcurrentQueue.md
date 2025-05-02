# ConcurrentQueue

**Namespace:** `System.Collections.Concurrent`


## Fields

- `Object _crossSegmentLock`

- `Segment _tail`

- `Segment _head`


## Properties

- `Int32 Count`


## Methods

- `Int32 get_Count()`

- `Void CopyTo(T[], Int32)`

- `Void SnapForObservation(out, out, out, out)`

- `T GetItemWhenAvailable(Segment, Int32)`

- `Void Enqueue(T)`

- `Void EnqueueSlow(T)`

- `Boolean TryDequeue(out)`

- `Boolean TryDequeueSlow(out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections.Concurrent
public class ConcurrentQueue`1 : IEnumerable`1, IEnumerable, ICollection, IReadOnlyCollection`1
{
	private const Int32 InitialSegmentLength; // 0x0
	private const Int32 MaxSegmentLength; // 0x0
	private Object _crossSegmentLock; // 0x0
	private Segment _tail; // 0x0
	private Segment _head; // 0x0

	private Boolean System.Collections.ICollection.IsSynchronized { get; }
	private Object System.Collections.ICollection.SyncRoot { get; }
	public Int32 Count { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.ICollection.CopyTo(Array array, Int32 index) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.ICollection.get_IsSynchronized() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.ICollection.get_SyncRoot() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public T[] ToArray() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	private static Int32 GetCount(Segment s, Int32 head, Int32 tail) { }
	// RVA: 0x VA: 0x0
	private static Int64 GetCount(Segment head, Int32 headHead, Segment tail, Int32 tailTail) { }
	// RVA: 0x VA: 0x0
	public Void CopyTo(T[] array, Int32 index) { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void SnapForObservation(out Segment head, out Int32 headHead, out Segment tail, out Int32 tailTail) { }
	// RVA: 0x VA: 0x0
	private T GetItemWhenAvailable(Segment segment, Int32 i) { }
	// RVA: 0x VA: 0x0
	private IEnumerator`1 Enumerate(Segment head, Int32 headHead, Segment tail, Int32 tailTail) { }
	// RVA: 0x VA: 0x0
	public Void Enqueue(T item) { }
	// RVA: 0x VA: 0x0
	private Void EnqueueSlow(T item) { }
	// RVA: 0x VA: 0x0
	public Boolean TryDequeue(out T result) { }
	// RVA: 0x VA: 0x0
	private Boolean TryDequeueSlow(out T item) { }
}
```