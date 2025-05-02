# ObjectPool

**Namespace:** `UnityEngine.Pool`


## Fields

- `Int32 <CountAll>k__BackingField`


## Properties

- `Int32 CountAll`

- `Int32 CountInactive`


## Methods

- `Int32 get_CountAll()`

- `Void set_CountAll(Int32)`

- `Int32 get_CountInactive()`

- `T Get()`

- `Void Release(T)`

- `Void Clear()`

- `Void Dispose()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Pool
public class ObjectPool`1 : IDisposable, IObjectPool`1
{
	internal readonly List`1 m_List; // 0x0
	private readonly Func`1 m_CreateFunc; // 0x0
	private readonly Action`1 m_ActionOnGet; // 0x0
	private readonly Action`1 m_ActionOnRelease; // 0x0
	private readonly Action`1 m_ActionOnDestroy; // 0x0
	private readonly Int32 m_MaxSize; // 0x0
	internal Boolean m_CollectionCheck; // 0x0
	private Int32 <CountAll>k__BackingField; // 0x0

	public Int32 CountAll { get; set; }
	public Int32 CountInactive { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_CountAll() { }
	// RVA: 0x VA: 0x0
	private Void set_CountAll(Int32 value) { }
	// RVA: 0x VA: 0x0
	public Int32 get_CountInactive() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Func`1 createFunc, Action`1 actionOnGet, Action`1 actionOnRelease, Action`1 actionOnDestroy, Boolean collectionCheck, Int32 defaultCapacity, Int32 maxSize) { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x VA: 0x0
	public PooledObject`1 Get(out T v) { }
	// RVA: 0x VA: 0x0
	public Void Release(T element) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
}
```