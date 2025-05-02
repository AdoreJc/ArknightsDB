# VRoom

**Namespace:** `Torappu.Building.Vault`


## Fields

- `String m_stayCharSignature`

- `VRoomGraphic _graphic`

- `VFloorPlane _floorPlane`

- `VBackwallPlane _backwallPlane`

- `Boolean _enableBackWall`

- `Boolean m_isEntered`

- `VDoor m_leftDoor`

- `VDoor m_rightDoor`

- `VFurnitureManager m_furnitureMgr`

- `RoomSlotModel <model>k__BackingField`

- `VRoomSlot <slot>k__BackingField`


## Properties

- `Boolean isOn`

- `GridPosition size`

- `Vector3 gridUnit`

- `VGridPlane floorPlane`

- `VGridPlane backwallPlane`

- `Boolean enableBackWall`

- `RoomSlotModel model`

- `VRoomGraphic graphic`

- `VFurnitureManager furnitureMgr`

- `VRoomSlot slot`

- `VDoor leftDoor`

- `VDoor rightDoor`

- `VLayoutManager layout`

- `Animator animator`

- `Boolean isEntered`


## Methods

- `Boolean get_isOn()`

- `GridPosition get_size()`

- `Vector3 get_gridUnit()`

- `VGridPlane get_floorPlane()`

- `VGridPlane get_backwallPlane()`

- `Boolean get_enableBackWall()`

- `RoomSlotModel get_model()`

- `Void set_model(RoomSlotModel)`

- `VRoomGraphic get_graphic()`

- `VFurnitureManager get_furnitureMgr()`

- `VRoomSlot get_slot()`

- `Void set_slot(VRoomSlot)`

- `VDoor get_leftDoor()`

- `VDoor get_rightDoor()`

- `VLayoutManager get_layout()`

- `Animator get_animator()`

- `Boolean get_isEntered()`

- `Void Init_EditorOnly(RoomSlotModel)`

- `Void OnSiblingReconstruct()`

- `Void OnContentChanged(RoomSlotModel)`

- `Void OnDestroy()`

- `Boolean OnClicked(PointerEventData, out)`

- `Boolean _TryInteractObjects(PointerEventData)`

- `Void _UpdateCharacters(Boolean)`

- `Void _InitFloorAndBackwall(Boolean)`

- `Void OnStayCharacterChangeRoom(VCharacter, Boolean)`

- `Boolean _ContainsStayCharacter(String)`

- `Void _OnVCharAsyncLoadFinished(VCharacter, Int32, EventPool`1)`

- `Void _AddVaultCharacter(ref, Int32, BuildingCharModel, EventPool`1)`

- `Void _RemoveVaultCharacter(VCharacter, EventPool`1)`

- `BuildingCharModel _FindStayCharByInstId(Int32)`

- `BuildingCharModel _FindStayCharByCharId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VRoom : MonoBehaviour, IHotfixable
{
	public const String FLOOR_CONTAINER_NAME; // 0x0
	public const String BACKWALL_CONTAINER_NAME; // 0x0
	private static List`1 s_sharedRaycastResults; // 0x0
	private static List`1 s_sharedCharIdList; // 0x8
	private List`1 m_stayChars; // 0x18
	private String m_stayCharSignature; // 0x20
	private ListSet`1 m_loadedOrLoadingChars; // 0x28
	private VRoomGraphic _graphic; // 0x30
	private VFloorPlane _floorPlane; // 0x38
	private VBackwallPlane _backwallPlane; // 0x40
	private Boolean _enableBackWall; // 0x48
	private Boolean m_isEntered; // 0x49
	private VDoor m_leftDoor; // 0x50
	private VDoor m_rightDoor; // 0x58
	protected List`1 m_objects; // 0x60
	protected VFurnitureManager m_furnitureMgr; // 0x68
	private RoomSlotModel <model>k__BackingField; // 0x70
	private VRoomSlot <slot>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_isOn; // 0x10
	private static DelegateBridge __Hotfix0_get_roomObjects; // 0x18
	private static DelegateBridge __Hotfix0_get_size; // 0x20
	private static DelegateBridge __Hotfix0_get_gridUnit; // 0x28
	private static DelegateBridge __Hotfix0_get_floorPlane; // 0x30
	private static DelegateBridge __Hotfix0_get_backwallPlane; // 0x38
	private static DelegateBridge __Hotfix0_get_enableBackWall; // 0x40
	private static DelegateBridge __Hotfix0_get_model; // 0x48
	private static DelegateBridge __Hotfix0_set_model; // 0x50
	private static DelegateBridge __Hotfix0_get_graphic; // 0x58
	private static DelegateBridge __Hotfix0_get_furnitureMgr; // 0x60
	private static DelegateBridge __Hotfix0_get_slot; // 0x68
	private static DelegateBridge __Hotfix0_set_slot; // 0x70
	private static DelegateBridge __Hotfix0_get_leftDoor; // 0x78
	private static DelegateBridge __Hotfix0_get_rightDoor; // 0x80
	private static DelegateBridge __Hotfix0_get_layout; // 0x88
	private static DelegateBridge __Hotfix0_get_animator; // 0x90
	private static DelegateBridge __Hotfix0_get_isEntered; // 0x98
	private static DelegateBridge __Hotfix0_TryGetRoomObject; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0xa8
	private static DelegateBridge __Hotfix0_Init_EditorOnly; // 0xb0
	private static DelegateBridge __Hotfix0_OnSiblingReconstruct; // 0xb8
	private static DelegateBridge __Hotfix0_OnContentChanged; // 0xc0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xc8
	private static DelegateBridge __Hotfix0_OnSelectChanged; // 0xd0
	private static DelegateBridge __Hotfix0_OnPreInit; // 0xd8
	private static DelegateBridge __Hotfix0_OnPostInit; // 0xe0
	private static DelegateBridge __Hotfix0_OnEnter; // 0xe8
	private static DelegateBridge __Hotfix0_OnExit; // 0xf0
	private static DelegateBridge __Hotfix0_OnInteractSelf; // 0xf8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x100
	private static DelegateBridge __Hotfix0__TryInteractObjects; // 0x108
	private static DelegateBridge __Hotfix0__UpdateCharacters; // 0x110
	private static DelegateBridge __Hotfix0__InitFloorAndBackwall; // 0x118
	private static DelegateBridge __Hotfix0_UpdateVFurniture; // 0x120
	private static DelegateBridge __Hotfix0_OnDestroyRoom; // 0x128
	private static DelegateBridge __Hotfix0_OnVCharacterUpdated; // 0x130
	private static DelegateBridge __Hotfix0_OnVCharacterToDestroy; // 0x138
	private static DelegateBridge __Hotfix0_GenerateDynamicObstacles; // 0x140
	private static DelegateBridge __Hotfix0_OnStayCharacterChangeRoom; // 0x148
	private static DelegateBridge __Hotfix0__ContainsStayCharacter; // 0x150
	private static DelegateBridge __Hotfix0__OnVCharAsyncLoadFinished; // 0x158
	private static DelegateBridge __Hotfix0__AddVaultCharacter; // 0x160
	private static DelegateBridge __Hotfix0__RemoveVaultCharacter; // 0x168
	private static DelegateBridge __Hotfix0__FindStayCharByInstId; // 0x170
	private static DelegateBridge __Hotfix0__FindStayCharByCharId; // 0x178
	private static DelegateBridge _c__Hotfix0_ctor; // 0x180

	public Boolean isOn { get; }
	public List`1 roomObjects { get; }
	public GridPosition size { get; }
	protected Vector3 gridUnit { get; }
	public VGridPlane floorPlane { get; }
	public VGridPlane backwallPlane { get; }
	public Boolean enableBackWall { get; }
	public RoomSlotModel model { get; set; }
	public VRoomGraphic graphic { get; }
	public VFurnitureManager furnitureMgr { get; }
	public VRoomSlot slot { get; set; }
	public VDoor leftDoor { get; }
	public VDoor rightDoor { get; }
	protected VLayoutManager layout { get; }
	protected Animator animator { get; }
	protected Boolean isEntered { get; }

	// RVA: 0x3cf13c0 VA: 0x75963093c0
	public Boolean get_isOn() { }
	// RVA: 0x3cf14c4 VA: 0x75963094c4
	public List`1 get_roomObjects() { }
	// RVA: 0x3cf153c VA: 0x759630953c
	public GridPosition get_size() { }
	// RVA: 0x3cf15c4 VA: 0x75963095c4
	protected Vector3 get_gridUnit() { }
	// RVA: 0x3cf1668 VA: 0x7596309668
	public VGridPlane get_floorPlane() { }
	// RVA: 0x3cf177c VA: 0x759630977c
	public VGridPlane get_backwallPlane() { }
	// RVA: 0x3cf1890 VA: 0x7596309890
	public Boolean get_enableBackWall() { }
	// RVA: 0x3cf055c VA: 0x759630855c
	public RoomSlotModel get_model() { }
	// RVA: 0x3cf1908 VA: 0x7596309908
	private Void set_model(RoomSlotModel value) { }
	// RVA: 0x3cf199c VA: 0x759630999c
	public VRoomGraphic get_graphic() { }
	// RVA: 0x3cf1a14 VA: 0x7596309a14
	public VFurnitureManager get_furnitureMgr() { }
	// RVA: 0x3cf144c VA: 0x759630944c
	public VRoomSlot get_slot() { }
	// RVA: 0x3cf1a8c VA: 0x7596309a8c
	private Void set_slot(VRoomSlot value) { }
	// RVA: 0x3cf1b20 VA: 0x7596309b20
	public VDoor get_leftDoor() { }
	// RVA: 0x3cf1b98 VA: 0x7596309b98
	public VDoor get_rightDoor() { }
	// RVA: 0x3cf1c10 VA: 0x7596309c10
	protected VLayoutManager get_layout() { }
	// RVA: 0x3cf1298 VA: 0x7596309298
	protected Animator get_animator() { }
	// RVA: 0x3cf1c98 VA: 0x7596309c98
	protected Boolean get_isEntered() { }
	// RVA: 0x3cf1d10 VA: 0x7596309d10
	public static Boolean TryGetRoomObject(GameObject go, out Object obj) { }
	// RVA: 0x3ceff18 VA: 0x7596307f18
	public virtual Void Init(VRoomSlot slot, RoomSlotModel model) { }
	// RVA: 0x3cf2b68 VA: 0x759630ab68
	public Void Init_EditorOnly(RoomSlotModel model) { }
	// RVA: 0x3cf2c48 VA: 0x759630ac48
	public Void OnSiblingReconstruct() { }
	// RVA: 0x3cf2d34 VA: 0x759630ad34
	public Void OnContentChanged(RoomSlotModel slotModel) { }
	// RVA: 0x3cf2dc4 VA: 0x759630adc4
	private Void OnDestroy() { }
	// RVA: 0x3cf2e44 VA: 0x759630ae44
	public virtual Void OnSelectChanged(Boolean isOn) { }
	// RVA: 0x3cf0f0c VA: 0x7596308f0c
	protected virtual Void OnPreInit() { }
	// RVA: 0x3cf2ecc VA: 0x759630aecc
	protected virtual Void OnPostInit() { }
	// RVA: 0x3cf0668 VA: 0x7596308668
	public virtual Void OnEnter() { }
	// RVA: 0x3cf2f40 VA: 0x759630af40
	public virtual Void OnExit() { }
	// RVA: 0x3cf3090 VA: 0x759630b090
	public virtual Boolean OnInteractSelf() { }
	// RVA: 0x3cf3104 VA: 0x759630b104
	public Boolean OnClicked(PointerEventData eventData, out Boolean willFocus) { }
	// RVA: 0x3cf31c8 VA: 0x759630b1c8
	private Boolean _TryInteractObjects(PointerEventData eventData) { }
	// RVA: 0x3cf224c VA: 0x759630a24c
	private Void _UpdateCharacters(Boolean isInit) { }
	// RVA: 0x3cf1fa8 VA: 0x7596309fa8
	private Void _InitFloorAndBackwall(Boolean ignoreBuiltInObstacles) { }
	// RVA: 0x3cf377c VA: 0x759630b77c
	protected virtual Void UpdateVFurniture(Object obj) { }
	// RVA: 0x3cf1100 VA: 0x7596309100
	protected virtual Void OnDestroyRoom() { }
	// RVA: 0x3cf3804 VA: 0x759630b804
	protected virtual Void OnVCharacterUpdated(VCharacter vc) { }
	// RVA: 0x3cf388c VA: 0x759630b88c
	protected virtual Void OnVCharacterToDestroy(VCharacter vc) { }
	// RVA: 0x3cf3914 VA: 0x759630b914
	protected virtual ObstacleRect[] GenerateDynamicObstacles(GridPosition gridSize) { }
	// RVA: 0x3cf399c VA: 0x759630b99c
	public Void OnStayCharacterChangeRoom(VCharacter vChar, Boolean isMoveIn) { }
	// RVA: 0x3cf3ca4 VA: 0x759630bca4
	private Boolean _ContainsStayCharacter(String charId) { }
	// RVA: 0x3cf3db8 VA: 0x759630bdb8
	private Void _OnVCharAsyncLoadFinished(VCharacter vChar, Int32 instId, EventPool`1 eventPool) { }
	// RVA: 0x3cf40b4 VA: 0x759630c0b4
	private Void _AddVaultCharacter(ref VCharacter vChar, Int32 charInstId, BuildingCharModel charModel, EventPool`1 eventPool) { }
	// RVA: 0x3cf3450 VA: 0x759630b450
	private Void _RemoveVaultCharacter(VCharacter vChar, EventPool`1 eventPool) { }
	// RVA: 0x3cf3efc VA: 0x759630befc
	private BuildingCharModel _FindStayCharByInstId(Int32 instId) { }
	// RVA: 0x3cf35d8 VA: 0x759630b5d8
	private BuildingCharModel _FindStayCharByCharId(String charId) { }
	// RVA: 0x3cf084c VA: 0x759630884c
	public Void .ctor() { }
	// RVA: 0x3cf43f0 VA: 0x759630c3f0
	private static Void .cctor() { }
}
```