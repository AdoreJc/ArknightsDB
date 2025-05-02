# GameObjectPool

**Namespace:** `Torappu.ObjectPool`


## Fields

- `Int32 m_counter`

- `Options m_options`


## Properties

- `Int32 availableUnusedCnt`

- `Int32 allLoadedCnt`

- `Transform parentTransform`

- `Boolean isInUse`


## Methods

- `Int32 get_availableUnusedCnt()`

- `Int32 get_allLoadedCnt()`

- `Transform get_parentTransform()`

- `Boolean get_isInUse()`

- `GameObject Allocate(Vector3, Quaternion, Transform)`

- `Boolean Recycle(GameObject)`

- `Void RecoverAfterSceneReloaded(Boolean)`

- `Boolean ClearIfNotUsed()`

- `Void ComplementToPreloadSize()`

- `GameObject _PickOneAndForceReuse()`

- `Void PrunePool()`

- `Void _LoadToSize(Int32)`

- `Void _RecycleInternal(GameObject)`

- `Void _SendNotification(GameObject, NotificationEvent)`

- `GameObject _CreateNew(Boolean)`

- `Void EmptyPool(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.ObjectPool
public class GameObjectPool
{
	private Int32 m_counter; // 0x10
	private Options m_options; // 0x18
	private List`1 m_unusedObjs; // 0x30
	private HashSet`1 m_usingObjs; // 0x38
	private Func`2 m_constructor; // 0x40
	private Queue`1 m_pendingObjsToAutoReuse; // 0x48

	public Int32 availableUnusedCnt { get; }
	public Int32 allLoadedCnt { get; }
	public Transform parentTransform { get; }
	public Boolean isInUse { get; }

	// RVA: 0x3566ee8 VA: 0x7595b7eee8
	public Int32 get_availableUnusedCnt() { }
	// RVA: 0x3566f30 VA: 0x7595b7ef30
	public Int32 get_allLoadedCnt() { }
	// RVA: 0x3566f94 VA: 0x7595b7ef94
	public Transform get_parentTransform() { }
	// RVA: 0x3566f9c VA: 0x7595b7ef9c
	public Boolean get_isInUse() { }
	// RVA: 0x3566fec VA: 0x7595b7efec
	public Void .ctor(Func`2 constructor, Options options) { }
	// RVA: 0x3567308 VA: 0x7595b7f308
	public GameObject Allocate(Vector3 position, Quaternion rotation, Transform parent) { }
	// RVA: 0x3567a38 VA: 0x7595b7fa38
	public Boolean Recycle(GameObject obj) { }
	// RVA: 0x3567be0 VA: 0x7595b7fbe0
	public Void RecoverAfterSceneReloaded(Boolean allowComplement) { }
	// RVA: 0x3567e54 VA: 0x7595b7fe54
	public Boolean ClearIfNotUsed() { }
	// RVA: 0x3567f40 VA: 0x7595b7ff40
	public Void ComplementToPreloadSize() { }
	// RVA: 0x356778c VA: 0x7595b7f78c
	private GameObject _PickOneAndForceReuse() { }
	// RVA: 0x3567f48 VA: 0x7595b7ff48
	public Void PrunePool() { }
	// RVA: 0x35671b8 VA: 0x7595b7f1b8
	private Void _LoadToSize(Int32 size) { }
	// RVA: 0x3567aec VA: 0x7595b7faec
	private Void _RecycleInternal(GameObject obj) { }
	// RVA: 0x3567968 VA: 0x7595b7f968
	private Void _SendNotification(GameObject obj, NotificationEvent ev) { }
	// RVA: 0x3567574 VA: 0x7595b7f574
	private GameObject _CreateNew(Boolean initActive) { }
	// RVA: 0x35681c0 VA: 0x7595b801c0
	public Void EmptyPool(Action`1 preProcess) { }
}
```