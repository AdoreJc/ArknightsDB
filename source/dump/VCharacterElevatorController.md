# VCharacterElevatorController

**Namespace:** ` `


## Fields

- `Boolean <isGoingUp>k__BackingField`

- `Boolean <isGoingDown>k__BackingField`

- `VCharacterController m_controller`

- `String m_upstairsSlotId`

- `String m_downstairsSlotId`


## Properties

- `Boolean inUpDownstairs`

- `Boolean isGoingUp`

- `Boolean isGoingDown`


## Methods

- `Boolean get_inUpDownstairs()`

- `Boolean get_isGoingUp()`

- `Void set_isGoingUp(Boolean)`

- `Boolean get_isGoingDown()`

- `Void set_isGoingDown(Boolean)`

- `Void OnDisable()`

- `Void Refresh(VCharacter)`

- `Boolean CanGoUpDownStairs(Boolean, VCharacter)`

- `Void OnRoomUpdated(VCharacter)`

- `Void _RefreshAutoMovingElevators(String)`

- `Void _UpdateAutoMovingElevators(BuildingModel, String)`

- `Void _RefreshUpdownElevatorSlots(String)`

- `Boolean CanMoveToNextRoom(VRoomSlot)`

- `Void _UpdateMovingElevators(String, VRoom, Single)`

- `Void _ElevatorCurveMove(ElevatorObj, ElevatorMovingState, Single)`

- `Void _OnElevatorMoveSuccess(ElevatorObj, VRoom)`

- `Void _UpdateMovingRelatedElevators(String, Direction, VRoom, Single)`

- `IEnumerator DoMoveByElevator(VCharacter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class VCharacterElevatorController : IHotfixable
{
	private Boolean <isGoingUp>k__BackingField; // 0x10
	private Boolean <isGoingDown>k__BackingField; // 0x11
	private VCharacterController m_controller; // 0x18
	private ListDict`2 m_movingElevators; // 0x20
	private List`1 m_sharedCharacters; // 0x28
	private String m_upstairsSlotId; // 0x30
	private String m_downstairsSlotId; // 0x38
	private const Single ROOM_PLANE_OFFSET_MAX; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_inUpDownstairs; // 0x8
	private static DelegateBridge __Hotfix0_get_isGoingUp; // 0x10
	private static DelegateBridge __Hotfix0_set_isGoingUp; // 0x18
	private static DelegateBridge __Hotfix0_get_isGoingDown; // 0x20
	private static DelegateBridge __Hotfix0_set_isGoingDown; // 0x28
	private static DelegateBridge __Hotfix0_OnDisable; // 0x30
	private static DelegateBridge __Hotfix0_Refresh; // 0x38
	private static DelegateBridge __Hotfix0_CanGoUpDownStairs; // 0x40
	private static DelegateBridge __Hotfix0_OnRoomUpdated; // 0x48
	private static DelegateBridge __Hotfix0__RefreshAutoMovingElevators; // 0x50
	private static DelegateBridge __Hotfix0__UpdateAutoMovingElevators; // 0x58
	private static DelegateBridge __Hotfix0__RefreshUpdownElevatorSlots; // 0x60
	private static DelegateBridge __Hotfix0_CanMoveToNextRoom; // 0x68
	private static DelegateBridge __Hotfix0__UpdateMovingElevators; // 0x70
	private static DelegateBridge __Hotfix0__ElevatorCurveMove; // 0x78
	private static DelegateBridge __Hotfix0__OnElevatorMoveSuccess; // 0x80
	private static DelegateBridge __Hotfix0__UpdateMovingRelatedElevators; // 0x88
	private static DelegateBridge __Hotfix0_DoMoveByElevator; // 0x90

	public Boolean inUpDownstairs { get; }
	public Boolean isGoingUp { get; set; }
	public Boolean isGoingDown { get; set; }

	// RVA: 0x3cffe94 VA: 0x7596317e94
	public Void .ctor(VCharacterController controller) { }
	// RVA: 0x3cfc4b8 VA: 0x75963144b8
	public Boolean get_inUpDownstairs() { }
	// RVA: 0x3cfc5ac VA: 0x75963145ac
	public Boolean get_isGoingUp() { }
	// RVA: 0x3d000d8 VA: 0x75963180d8
	private Void set_isGoingUp(Boolean value) { }
	// RVA: 0x3cfc684 VA: 0x7596314684
	public Boolean get_isGoingDown() { }
	// RVA: 0x3d00158 VA: 0x7596318158
	private Void set_isGoingDown(Boolean value) { }
	// RVA: 0x3cff654 VA: 0x7596317654
	public Void OnDisable() { }
	// RVA: 0x3cfd118 VA: 0x7596315118
	public Void Refresh(VCharacter character) { }
	// RVA: 0x3cfc764 VA: 0x7596314764
	public Boolean CanGoUpDownStairs(Boolean isUp, VCharacter character) { }
	// RVA: 0x3cff104 VA: 0x7596317104
	public Void OnRoomUpdated(VCharacter character) { }
	// RVA: 0x3d004fc VA: 0x75963184fc
	private Void _RefreshAutoMovingElevators(String slotId) { }
	// RVA: 0x3d008e0 VA: 0x75963188e0
	private Void _UpdateAutoMovingElevators(BuildingModel buildingModel, String slotId) { }
	// RVA: 0x3d00254 VA: 0x7596318254
	private Void _RefreshUpdownElevatorSlots(String slotId) { }
	// RVA: 0x3d00f58 VA: 0x7596318f58
	public Boolean CanMoveToNextRoom(VRoomSlot nextSlot) { }
	// RVA: 0x3d00a4c VA: 0x7596318a4c
	private Void _UpdateMovingElevators(String slotId, VRoom targetRoom, Single duration) { }
	// RVA: 0x3d01278 VA: 0x7596319278
	private Void _ElevatorCurveMove(ElevatorObj obj, ElevatorMovingState movingState, Single duration) { }
	// RVA: 0x3d016bc VA: 0x75963196bc
	private Void _OnElevatorMoveSuccess(ElevatorObj obj, VRoom targetRoom) { }
	// RVA: 0x3d00c9c VA: 0x7596318c9c
	private Void _UpdateMovingRelatedElevators(String slotId, Direction direction, VRoom targetRoom, Single duration) { }
	// RVA: 0x3cfd9d0 VA: 0x75963159d0
	public IEnumerator DoMoveByElevator(VCharacter character, Boolean isUp) { }
}
```