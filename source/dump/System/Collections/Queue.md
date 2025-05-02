# Queue

**Namespace:** `System.Collections`


## Fields

- `Int32 _head`

- `Int32 _tail`

- `Int32 _size`

- `Int32 _growFactor`

- `Int32 _version`

- `Object _syncRoot`


## Methods

- `Void SetCapacity(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Collections
public class Queue : ICollection, IEnumerable, ICloneable
{
	private Object[] _array; // 0x10
	private Int32 _head; // 0x18
	private Int32 _tail; // 0x1c
	private Int32 _size; // 0x20
	private Int32 _growFactor; // 0x24
	private Int32 _version; // 0x28
	private Object _syncRoot; // 0x30

	public virtual Int32 Count { get; }
	public virtual Boolean IsSynchronized { get; }
	public virtual Object SyncRoot { get; }

	// RVA: 0x607e828 VA: 0x7598696828
	public Void .ctor() { }
	// RVA: 0x607ea04 VA: 0x7598696a04
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x607e834 VA: 0x7598696834
	public Void .ctor(Int32 capacity, Single growFactor) { }
	// RVA: 0x607ea0c VA: 0x7598696a0c
	public Void .ctor(ICollection col) { }
	// RVA: 0x607ec78 VA: 0x7598696c78
	public virtual Int32 get_Count() { }
	// RVA: 0x607ec80 VA: 0x7598696c80
	public virtual Object Clone() { }
	// RVA: 0x607ed64 VA: 0x7598696d64
	public virtual Boolean get_IsSynchronized() { }
	// RVA: 0x607ed6c VA: 0x7598696d6c
	public virtual Object get_SyncRoot() { }
	// RVA: 0x607ede8 VA: 0x7598696de8
	public virtual Void CopyTo(Array array, Int32 index) { }
	// RVA: 0x607efdc VA: 0x7598696fdc
	public virtual Void Enqueue(Object obj) { }
	// RVA: 0x607f1d8 VA: 0x75986971d8
	public virtual IEnumerator GetEnumerator() { }
	// RVA: 0x607f2b0 VA: 0x75986972b0
	public virtual Object Dequeue() { }
	// RVA: 0x607f394 VA: 0x7598697394
	public virtual Object Peek() { }
	// RVA: 0x607f428 VA: 0x7598697428
	internal Object GetElement(Int32 i) { }
	// RVA: 0x607f0e0 VA: 0x75986970e0
	private Void SetCapacity(Int32 capacity) { }
}
```