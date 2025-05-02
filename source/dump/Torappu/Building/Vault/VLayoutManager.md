# VLayoutManager

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Transform _viewport`

- `Transform _container`

- `VWallGenerator _wallGenerator`

- `VRoomSlot _roomSlot`

- `BaseRaycaster _raycaster`

- `Single _paddingX`

- `Single _paddingY`

- `VaultMode m_state`

- `VRoomSlot m_currentSelectedRoom`

- `Object m_currentSelectedObject`

- `Rect <visibleRect>k__BackingField`


## Properties

- `VRoomSlot selectedRoom`

- `Transform roomContainer`

- `Object selectedObject`

- `VCharacter selectedCharacter`

- `BaseRaycaster raycster`

- `Rect visibleRect`


## Methods

- `VRoomSlot get_selectedRoom()`

- `Void set_selectedRoom(VRoomSlot)`

- `Transform get_roomContainer()`

- `Object get_selectedObject()`

- `Void set_selectedObject(Object)`

- `VCharacter get_selectedCharacter()`

- `BaseRaycaster get_raycster()`

- `Rect get_visibleRect()`

- `Void set_visibleRect(Rect)`

- `Void Init(List`1, VaultMode)`

- `Void OnEnter()`

- `Void OnExit()`

- `Void StopAllMusicInteractFurniture()`

- `Void OnRoomClicked(VRoomSlot, Boolean)`

- `Boolean TryGetRoomByModel(RoomSlotModel, out)`

- `Rect GetVisibleRect()`

- `Void OnFixedUpdate(Single)`

- `Void _OnLayoutUpdate()`

- `Void _OnLayoutDragOrPinch()`

- `Void _OnLayoutZoomUpdate(Single, Single)`

- `VRoomSlot _CreateRoomSlot(RoomSlotModel)`

- `Void _InitLayout(List`1)`

- `Void _ClearAll()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VLayoutManager : MonoBehaviour, IHotfixable
{
	private Transform _viewport; // 0x18
	private Transform _container; // 0x20
	private VWallGenerator _wallGenerator; // 0x28
	private VRoomSlot _roomSlot; // 0x30
	private BaseRaycaster _raycaster; // 0x38
	private Single _paddingX; // 0x40
	private Single _paddingY; // 0x44
	private VaultMode m_state; // 0x48
	private List`1 m_rooms; // 0x50
	private Dictionary`2 m_modelToRoomMap; // 0x58
	private VRoomSlot m_currentSelectedRoom; // 0x60
	private Object m_currentSelectedObject; // 0x68
	private Vector3[] m_frustumCorners; // 0x70
	private Rect <visibleRect>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_selectedRoom; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedRoom; // 0x8
	private static DelegateBridge __Hotfix0_get_roomContainer; // 0x10
	private static DelegateBridge __Hotfix0_get_rooms; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedObject; // 0x20
	private static DelegateBridge __Hotfix0_set_selectedObject; // 0x28
	private static DelegateBridge __Hotfix0_get_selectedCharacter; // 0x30
	private static DelegateBridge __Hotfix0_get_raycster; // 0x38
	private static DelegateBridge __Hotfix0_get_visibleRect; // 0x40
	private static DelegateBridge __Hotfix0_set_visibleRect; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x50
	private static DelegateBridge __Hotfix0_OnEnter; // 0x58
	private static DelegateBridge __Hotfix0_OnExit; // 0x60
	private static DelegateBridge __Hotfix0_StopAllMusicInteractFurniture; // 0x68
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x70
	private static DelegateBridge __Hotfix0_TryGetRoomByModel; // 0x78
	private static DelegateBridge __Hotfix0_GetVisibleRect; // 0x80
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x88
	private static DelegateBridge __Hotfix0__OnLayoutUpdate; // 0x90
	private static DelegateBridge __Hotfix0__OnLayoutDragOrPinch; // 0x98
	private static DelegateBridge __Hotfix0__OnLayoutZoomUpdate; // 0xa0
	private static DelegateBridge __Hotfix0__CreateRoomSlot; // 0xa8
	private static DelegateBridge __Hotfix0__InitLayout; // 0xb0
	private static DelegateBridge __Hotfix0__ClearAll; // 0xb8
	private static DelegateBridge __Hotfix0_Start; // 0xc0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public VRoomSlot selectedRoom { get; set; }
	public Transform roomContainer { get; }
	public List`1 rooms { get; }
	public Object selectedObject { get; set; }
	public VCharacter selectedCharacter { get; }
	public BaseRaycaster raycster { get; }
	public Rect visibleRect { get; set; }

	// RVA: 0x3cf7740 VA: 0x759630f740
	public VRoomSlot get_selectedRoom() { }
	// RVA: 0x3cf8f70 VA: 0x7596310f70
	public Void set_selectedRoom(VRoomSlot value) { }
	// RVA: 0x3cf7598 VA: 0x759630f598
	public Transform get_roomContainer() { }
	// RVA: 0x3d001d8 VA: 0x75963181d8
	public List`1 get_rooms() { }
	// RVA: 0x3d028cc VA: 0x759631a8cc
	public Object get_selectedObject() { }
	// RVA: 0x3cf4f68 VA: 0x759630cf68
	public Void set_selectedObject(Object value) { }
	// RVA: 0x3d02934 VA: 0x759631a934
	public VCharacter get_selectedCharacter() { }
	// RVA: 0x3cf33e0 VA: 0x759630b3e0
	public BaseRaycaster get_raycster() { }
	// RVA: 0x3cf6564 VA: 0x759630e564
	public Rect get_visibleRect() { }
	// RVA: 0x3d029ec VA: 0x759631a9ec
	private Void set_visibleRect(Rect value) { }
	// RVA: 0x3cf7a20 VA: 0x759630fa20
	public Void Init(List`1 layout, VaultMode state) { }
	// RVA: 0x3cf7fbc VA: 0x759630ffbc
	public Void OnEnter() { }
	// RVA: 0x3cf81ec VA: 0x75963101ec
	public Void OnExit() { }
	// RVA: 0x3cf862c VA: 0x759631062c
	public Void StopAllMusicInteractFurniture() { }
	// RVA: 0x3cf6d84 VA: 0x759630ed84
	public Void OnRoomClicked(VRoomSlot room, Boolean willFocus) { }
	// RVA: 0x3cf8ec4 VA: 0x7596310ec4
	public Boolean TryGetRoomByModel(RoomSlotModel model, out VRoomSlot value) { }
	// RVA: 0x3d02f58 VA: 0x759631af58
	public Rect GetVisibleRect() { }
	// RVA: 0x3cf83b8 VA: 0x75963103b8
	public Void OnFixedUpdate(Single deltaTime) { }
	// RVA: 0x3d0318c VA: 0x759631b18c
	private Void _OnLayoutUpdate() { }
	// RVA: 0x3d03490 VA: 0x759631b490
	private Void _OnLayoutDragOrPinch() { }
	// RVA: 0x3d03508 VA: 0x759631b508
	private Void _OnLayoutZoomUpdate(Single oldSize, Single newSize) { }
	// RVA: 0x3d02b90 VA: 0x759631ab90
	private VRoomSlot _CreateRoomSlot(RoomSlotModel model) { }
	// RVA: 0x3d02c74 VA: 0x759631ac74
	private Void _InitLayout(List`1 layout) { }
	// RVA: 0x3d02a90 VA: 0x759631aa90
	private Void _ClearAll() { }
	// RVA: 0x3d036c8 VA: 0x759631b6c8
	private Void Start() { }
	// RVA: 0x3d03838 VA: 0x759631b838
	private Void OnDestroy() { }
	// RVA: 0x3d039d8 VA: 0x759631b9d8
	public Void .ctor() { }
}
```