# ObjectPool

**Namespace:** `Torappu.ObjectPool`


## Fields

- `Options m_options`


## Properties

- `Int32 availableUnusedCnt`

- `Int32 allLoadedCnt`


## Methods

- `Int32 get_availableUnusedCnt()`

- `Int32 get_allLoadedCnt()`

- `T Allocate()`

- `Boolean Recycle(T)`

- `Void Reset()`

- `Void ClearUsingLinksOnly()`

- `T _PickOneAndForceReuse()`

- `Void _LoadToSize(Int32)`

- `Void _RecycleInternal(T)`

- `Void _SendNotification(T, NotificationEvent)`

- `T _CreateNew()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.ObjectPool
public class ObjectPool`1
{
	private Options m_options; // 0x0
	private Stack`1 m_unusedObjs; // 0x0
	private HashSet`1 m_usingObjs; // 0x0
	private Func`1 m_constructor; // 0x0
	private Queue`1 m_pendingObjsToAutoReuse; // 0x0

	public Int32 availableUnusedCnt { get; }
	public Int32 allLoadedCnt { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_availableUnusedCnt() { }
	// RVA: 0x VA: 0x0
	public Int32 get_allLoadedCnt() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Func`1 constructor, Options options) { }
	// RVA: 0x VA: 0x0
	public T Allocate() { }
	// RVA: 0x VA: 0x0
	public Boolean Recycle(T obj) { }
	// RVA: 0x VA: 0x0
	public Void Reset() { }
	// RVA: 0x VA: 0x0
	public Void ClearUsingLinksOnly() { }
	// RVA: 0x VA: 0x0
	private T _PickOneAndForceReuse() { }
	// RVA: 0x VA: 0x0
	private Void _LoadToSize(Int32 size) { }
	// RVA: 0x VA: 0x0
	private Void _RecycleInternal(T obj) { }
	// RVA: 0x VA: 0x0
	private Void _SendNotification(T obj, NotificationEvent ev) { }
	// RVA: 0x VA: 0x0
	private T _CreateNew() { }
}
```