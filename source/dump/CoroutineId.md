# CoroutineId

**Namespace:** ` `


## Fields

- `WeakReference m_coroutine`

- `IEnumerator <routine>k__BackingField`


## Properties

- `IEnumerator routine`


## Methods

- `IEnumerator get_routine()`

- `Void set_routine(IEnumerator)`

- `Coroutine GetCoroutine()`

- `Boolean Match(Coroutine)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CoroutineId
{
	private WeakReference m_coroutine; // 0x10
	private IEnumerator <routine>k__BackingField; // 0x18

	public IEnumerator routine { get; set; }

	// RVA: 0x2157d84 VA: 0x759476fd84
	private Void .ctor() { }
	// RVA: 0x2157d8c VA: 0x759476fd8c
	public IEnumerator get_routine() { }
	// RVA: 0x2157d94 VA: 0x759476fd94
	private Void set_routine(IEnumerator value) { }
	// RVA: 0x2157d9c VA: 0x759476fd9c
	public Coroutine GetCoroutine() { }
	// RVA: 0x2157e50 VA: 0x759476fe50
	public Boolean Match(Coroutine target) { }
	// RVA: 0x2157e8c VA: 0x759476fe8c
	public static CoroutineId Alloc(Coroutine coro, IEnumerator routine, Queue`1 pool) { }
	// RVA: 0x2157f94 VA: 0x759476ff94
	public static Void Dealloc(CoroutineId id, Queue`1 pool) { }
}
```