# VRoomSlot

**Namespace:** `Torappu.Building.Vault`


## Fields

- `SpriteRenderer _highlight`

- `DragCancellableClickHandler m_clickHandler`

- `BoxCollider2D m_boxCollider`

- `Boolean m_isOn`

- `Boolean m_isVisible`

- `Boolean m_isEntered`

- `VRoom m_internalRoom`

- `Int32 m_lodValueOffset`

- `Int32 m_parentLOD`

- `LODState <lodState>k__BackingField`

- `VRoomSlot <leftSlot>k__BackingField`

- `VRoomSlot <rightSlot>k__BackingField`

- `VLayoutManager <layout>k__BackingField`


## Properties

- `LODState lodState`

- `Int32 assetPriority`

- `Boolean isVisible`

- `Boolean isHighlight`

- `VRoom room`

- `Vector2 minPos`

- `Vector2 center`

- `Vector3 worldCenter`

- `Vector3 worldStoreyCenter`

- `Rect boundingBox`

- `Boolean hasLeftDoor`

- `Boolean hasRightDoor`

- `GameObject leftDoorGameObject`

- `GameObject rightDoorGameObject`

- `VRoomSlot leftSlot`

- `VRoomSlot rightSlot`

- `VLayoutManager layout`


## Methods

- `LODState get_lodState()`

- `Void set_lodState(LODState)`

- `Int32 get_assetPriority()`

- `Boolean get_isVisible()`

- `Void set_isVisible(Boolean)`

- `Boolean get_isHighlight()`

- `Void set_isHighlight(Boolean)`

- `VRoom get_room()`

- `Vector2 get_minPos()`

- `Vector2 get_center()`

- `Vector3 get_worldCenter()`

- `Vector3 get_worldStoreyCenter()`

- `Rect get_boundingBox()`

- `Boolean get_hasLeftDoor()`

- `Boolean get_hasRightDoor()`

- `GameObject get_leftDoorGameObject()`

- `GameObject get_rightDoorGameObject()`

- `VRoomSlot get_leftSlot()`

- `Void set_leftSlot(VRoomSlot)`

- `VRoomSlot get_rightSlot()`

- `Void set_rightSlot(VRoomSlot)`

- `VLayoutManager get_layout()`

- `Void set_layout(VLayoutManager)`

- `Void Init(VRoomSlot, VRoomSlot, VLayoutManager)`

- `Void OnEnter()`

- `Void OnExit()`

- `Void OnFixedUpdate(Single)`

- `Void _UpdateVisible()`

- `Void _UpdateLOD()`

- `Void OnLODStateChanged(LODState)`

- `Void AddLODListener(ILODListener)`

- `Void RemoveLODListener(ILODListener)`

- `Void UpdateLOD(Int32)`

- `Void _NotifyLODLevelChanged()`

- `Void _OnDiyPageSavedChanges(Object)`

- `Void SetPositionV2(GridPosition)`

- `Void SetPositionV3(GridPosition, Single)`

- `String _GenerateRoomPrefabKey()`

- `Void _ReconstructInternalRoom(Boolean)`

- `Void _OnClicked(PointerEventData)`

- `Void _ResizeComponentsToMatchRoomSize()`

- `Void _SetIsOnInternal(Boolean, Boolean)`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VRoomSlot : AbstractRoomSlot, IDynamicAssetWrapper, ILODHolder, ILODListener
{
	private const Single HIGHLIGHT_OFFSET_Z; // 0x0
	private SpriteRenderer _highlight; // 0x20
	private DragCancellableClickHandler m_clickHandler; // 0x28
	private BoxCollider2D m_boxCollider; // 0x30
	private Boolean m_isOn; // 0x38
	private Boolean m_isVisible; // 0x39
	private Boolean m_isEntered; // 0x3a
	private VRoom m_internalRoom; // 0x40
	private Nullable`1 m_dataCache; // 0x48
	private Int32 m_lodValueOffset; // 0x58
	private Int32 m_parentLOD; // 0x5c
	private List`1 m_lodListeners; // 0x60
	private LODState <lodState>k__BackingField; // 0x68
	private VRoomSlot <leftSlot>k__BackingField; // 0x70
	private VRoomSlot <rightSlot>k__BackingField; // 0x78
	private VLayoutManager <layout>k__BackingField; // 0x80

	public LODState lodState { get; set; }
	public Int32 assetPriority { get; }
	public override Boolean isOn { get; set; }
	public Boolean isVisible { get; set; }
	public Boolean isHighlight { get; set; }
	public VRoom room { get; }
	public Vector2 minPos { get; }
	public Vector2 center { get; }
	public Vector3 worldCenter { get; }
	public Vector3 worldStoreyCenter { get; }
	public Rect boundingBox { get; }
	public Boolean hasLeftDoor { get; }
	public Boolean hasRightDoor { get; }
	public GameObject leftDoorGameObject { get; }
	public GameObject rightDoorGameObject { get; }
	public VRoomSlot leftSlot { get; set; }
	public VRoomSlot rightSlot { get; set; }
	public VLayoutManager layout { get; set; }

	// RVA: 0x3cf5228 VA: 0x759630d228
	public LODState get_lodState() { }
	// RVA: 0x3cf5230 VA: 0x759630d230
	public Void set_lodState(LODState value) { }
	// RVA: 0x3cf5238 VA: 0x759630d238
	public Int32 get_assetPriority() { }
	// RVA: 0x3cf5268 VA: 0x759630d268
	public override Boolean get_isOn() { }
	// RVA: 0x3cf5270 VA: 0x759630d270
	public override Void set_isOn(Boolean value) { }
	// RVA: 0x3cf52dc VA: 0x759630d2dc
	public Boolean get_isVisible() { }
	// RVA: 0x3cf52e4 VA: 0x759630d2e4
	public Void set_isVisible(Boolean value) { }
	// RVA: 0x3cf52f0 VA: 0x759630d2f0
	public Boolean get_isHighlight() { }
	// RVA: 0x3cf5318 VA: 0x759630d318
	public Void set_isHighlight(Boolean value) { }
	// RVA: 0x3cf5348 VA: 0x759630d348
	public VRoom get_room() { }
	// RVA: 0x3cf5350 VA: 0x759630d350
	public Vector2 get_minPos() { }
	// RVA: 0x3cf53c8 VA: 0x759630d3c8
	public Vector2 get_center() { }
	// RVA: 0x3cf546c VA: 0x759630d46c
	public Vector3 get_worldCenter() { }
	// RVA: 0x3cf5518 VA: 0x759630d518
	public Vector3 get_worldStoreyCenter() { }
	// RVA: 0x3cf55cc VA: 0x759630d5cc
	public Rect get_boundingBox() { }
	// RVA: 0x3cf1e58 VA: 0x7596309e58
	public Boolean get_hasLeftDoor() { }
	// RVA: 0x3cf1f00 VA: 0x7596309f00
	public Boolean get_hasRightDoor() { }
	// RVA: 0x3cf564c VA: 0x759630d64c
	public GameObject get_leftDoorGameObject() { }
	// RVA: 0x3cf5714 VA: 0x759630d714
	public GameObject get_rightDoorGameObject() { }
	// RVA: 0x3cf57dc VA: 0x759630d7dc
	public VRoomSlot get_leftSlot() { }
	// RVA: 0x3cf57e4 VA: 0x759630d7e4
	private Void set_leftSlot(VRoomSlot value) { }
	// RVA: 0x3cf57ec VA: 0x759630d7ec
	public VRoomSlot get_rightSlot() { }
	// RVA: 0x3cf57f4 VA: 0x759630d7f4
	private Void set_rightSlot(VRoomSlot value) { }
	// RVA: 0x3cf57fc VA: 0x759630d7fc
	public VLayoutManager get_layout() { }
	// RVA: 0x3cf5804 VA: 0x759630d804
	private Void set_layout(VLayoutManager value) { }
	// RVA: 0x3cf580c VA: 0x759630d80c
	public Void Init(VRoomSlot leftSlot, VRoomSlot rightSlot, VLayoutManager layout) { }
	// RVA: 0x3cf6000 VA: 0x759630e000
	public override Void OnContentChange(RoomSlotModel model) { }
	// RVA: 0x3cf6180 VA: 0x759630e180
	protected virtual Void OnSiblingReconstruct(VRoomSlot sibling) { }
	// RVA: 0x3cf6200 VA: 0x759630e200
	public Void OnEnter() { }
	// RVA: 0x3cf6288 VA: 0x759630e288
	public Void OnExit() { }
	// RVA: 0x3cf6314 VA: 0x759630e314
	public Void OnFixedUpdate(Single deltaTime) { }
	// RVA: 0x3cf632c VA: 0x759630e32c
	private Void _UpdateVisible() { }
	// RVA: 0x3cf6374 VA: 0x759630e374
	private Void _UpdateLOD() { }
	// RVA: 0x3cf66e0 VA: 0x759630e6e0
	public Void OnLODStateChanged(LODState state) { }
	// RVA: 0x3cf66fc VA: 0x759630e6fc
	public Void AddLODListener(ILODListener listener) { }
	// RVA: 0x3cf67e4 VA: 0x759630e7e4
	public Void RemoveLODListener(ILODListener listener) { }
	// RVA: 0x3cf6664 VA: 0x759630e664
	public Void UpdateLOD(Int32 lod) { }
	// RVA: 0x3cf68b4 VA: 0x759630e8b4
	private Void _NotifyLODLevelChanged() { }
	// RVA: 0x3cf6a04 VA: 0x759630ea04
	protected override Void OnInit() { }
	// RVA: 0x3cf6adc VA: 0x759630eadc
	private Void _OnDiyPageSavedChanges(Object arg) { }
	// RVA: 0x3cf6b48 VA: 0x759630eb48
	protected Void SetPositionV2(GridPosition gridPosition) { }
	// RVA: 0x3cf6a28 VA: 0x759630ea28
	protected Void SetPositionV3(GridPosition gridPosition, Single z) { }
	// RVA: 0x3cf6b88 VA: 0x759630eb88
	private String _GenerateRoomPrefabKey() { }
	// RVA: 0x3cf5d60 VA: 0x759630dd60
	private Void _ReconstructInternalRoom(Boolean isInit) { }
	// RVA: 0x3cf6ce0 VA: 0x759630ece0
	private Void _OnClicked(PointerEventData eventData) { }
	// RVA: 0x3cf5bd4 VA: 0x759630dbd4
	private Void _ResizeComponentsToMatchRoomSize() { }
	// RVA: 0x3cf527c VA: 0x759630d27c
	private Void _SetIsOnInternal(Boolean value, Boolean force) { }
	// RVA: 0x3cf7010 VA: 0x759630f010
	private Void Awake() { }
	// RVA: 0x3cf7124 VA: 0x759630f124
	private Void OnDestroy() { }
	// RVA: 0x3cf7208 VA: 0x759630f208
	public Void .ctor() { }
}
```