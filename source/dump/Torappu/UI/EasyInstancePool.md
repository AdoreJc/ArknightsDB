# EasyInstancePool

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _testItemsCnt`

- `Object _instancePrefab`

- `Boolean _autoFillIndex`

- `Boolean _autoAdjustPos`

- `Boolean _setZAxisToZero`

- `Boolean _clearOnDisable`

- `Vector3 _slotsBeginPos`

- `Vector2 _slotsOffsetPos`

- `Int32 _slotsMaxPerLineOrRow`

- `Boolean _horizontal`

- `OnItemChangeUsage onItemDequeue`

- `OnItemChangeUsage onItemEnqueue`

- `MessageCb onMakeItemsComplete`

- `Int32 m_rowNum`

- `Int32 m_colNum`


## Properties

- `GameObject Item`

- `Int32 count`

- `Vector2 size`

- `Vector2 center`


## Methods

- `GameObject get_Item(Int32)`

- `Int32 get_count()`

- `Vector2 get_size()`

- `Vector2 get_center()`

- `Void MakeItems(Int32)`

- `GameObject AllocateObject(Boolean)`

- `Void RecycleObject(GameObject, Boolean)`

- `Void DestroyInstancesInUseList()`

- `Void _CreateInstance()`

- `Void _SetPos()`

- `Vector3 _GetOffsetPos(Int32)`

- `Void _CalcRowCol()`

- `Void Start()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class EasyInstancePool : MonoBehaviour
{
	private Int32 _testItemsCnt; // 0x18
	private Object _instancePrefab; // 0x20
	private Boolean _autoFillIndex; // 0x28
	private Boolean _autoAdjustPos; // 0x29
	private Boolean _setZAxisToZero; // 0x2a
	private Boolean _clearOnDisable; // 0x2b
	private Vector3 _slotsBeginPos; // 0x2c
	private Vector2 _slotsOffsetPos; // 0x38
	private Int32 _slotsMaxPerLineOrRow; // 0x40
	private Boolean _horizontal; // 0x44
	public OnItemChangeUsage onItemDequeue; // 0x48
	public OnItemChangeUsage onItemEnqueue; // 0x50
	public MessageCb onMakeItemsComplete; // 0x58
	private Int32 m_rowNum; // 0x60
	private Int32 m_colNum; // 0x64
	private List`1 m_instancesInUse; // 0x68
	private List`1 m_instancesNotInUse; // 0x70

	public GameObject Item { get; }
	public Int32 count { get; }
	public Vector2 size { get; }
	public Vector2 center { get; }

	// RVA: 0x21c2a70 VA: 0x75947daa70
	public GameObject get_Item(Int32 i) { }
	// RVA: 0x21c2dbc VA: 0x75947dadbc
	public Int32 get_count() { }
	// RVA: 0x21c2e04 VA: 0x75947dae04
	public Vector2 get_size() { }
	// RVA: 0x21c2e24 VA: 0x75947dae24
	public Vector2 get_center() { }
	// RVA: 0x21c2b10 VA: 0x75947dab10
	public Void MakeItems(Int32 count) { }
	// RVA: 0x21c32a8 VA: 0x75947db2a8
	public GameObject AllocateObject(Boolean setActive) { }
	// RVA: 0x21c3408 VA: 0x75947db408
	public Void RecycleObject(GameObject obj, Boolean setInActive) { }
	// RVA: 0x21c3558 VA: 0x75947db558
	public Void DestroyInstancesInUseList() { }
	// RVA: 0x21c2eec VA: 0x75947daeec
	private Void _CreateInstance() { }
	// RVA: 0x21c30dc VA: 0x75947db0dc
	private Void _SetPos() { }
	// RVA: 0x21c3654 VA: 0x75947db654
	private Vector3 _GetOffsetPos(Int32 index) { }
	// RVA: 0x21c3210 VA: 0x75947db210
	private Void _CalcRowCol() { }
	// RVA: 0x21c36ac VA: 0x75947db6ac
	private Void Start() { }
	// RVA: 0x21c36c0 VA: 0x75947db6c0
	private Void OnDisable() { }
	// RVA: 0x21c36d4 VA: 0x75947db6d4
	public Void .ctor() { }
}
```