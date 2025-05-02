# ThreadSafeQueue

**Namespace:** `Torappu`


## Fields

- `Object m_syncObj`


## Properties

- `Int32 count`


## Methods

- `Int32 get_count()`

- `Void Clear()`

- `Boolean Contains(T)`

- `T Dequeue()`

- `Void Enqueue(T)`

- `T Peek()`

- `Boolean TryDequeue(out)`

- `Boolean TryPeek(out)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class ThreadSafeQueue`1
{
	private Object m_syncObj; // 0x0
	private Queue`1 m_queue; // 0x0

	public Int32 count { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEnumerable`1 collection) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 count) { }
	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Boolean Contains(T item) { }
	// RVA: 0x VA: 0x0
	public T Dequeue() { }
	// RVA: 0x VA: 0x0
	public Void Enqueue(T item) { }
	// RVA: 0x VA: 0x0
	public T Peek() { }
	// RVA: 0x VA: 0x0
	public Boolean TryDequeue(out T item) { }
	// RVA: 0x VA: 0x0
	public Boolean TryPeek(out T item) { }
	// RVA: 0x VA: 0x0
	public T[] TakeAll() { }
	// RVA: 0x VA: 0x0
	public T[] ToArray() { }
}
```