# LRUCache

**Namespace:** `Torappu`


## Fields

- `Int32 m_capacity`


## Properties

- `Int32 capacity`

- `Int32 count`


## Methods

- `Int32 get_capacity()`

- `Int32 get_count()`

- `V Get(K)`

- `Boolean TryGetValue(K, out)`

- `Void Add(K, V)`

- `Void Clear()`

- `Void SetCapacity(Int32)`

- `Void _RemoveFirst()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class LRUCache`2
{
	private Int32 m_capacity; // 0x0
	private Dictionary`2 m_cacheMap; // 0x0
	private LinkedList`1 m_lruQueue; // 0x0

	public Int32 capacity { get; }
	public Int32 count { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_capacity() { }
	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public V Get(K key) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetValue(K key, out V val) { }
	// RVA: 0x VA: 0x0
	public Void Add(K key, V val) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Void SetCapacity(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	private Void _RemoveFirst() { }
}
```