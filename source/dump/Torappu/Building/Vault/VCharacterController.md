# VCharacterController

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Single _moveMaxSpeed`

- `Single _moveSpeed`

- `Single _moveAnimScale`

- `Single _colliderRangeY`

- `Single _cameraFocusMaxDist`

- `Single _cameraZoom`

- `Boolean _highlightWhenMove`

- `Boolean _forceIdleWhenCannotMove`

- `Single _elevatorTime`

- `Single _elevatorAutoMoveTime`

- `AnimationCurve _elevatorCurve`

- `Single _elevatorHeightOffset`

- `Single _distanceToInteract`

- `Single _distanceToInteractUpdate`

- `Single _focusDoorSpeedRatio`

- `Single _speedToLeaveInteract`

- `Boolean _canInterruptSpecialAnim`

- `VCharacterEmojiPanel _emojiPanel`

- `VCharacterElevatorController m_elevatorController`

- `VCharacterMoveChecker m_moveChecker`

- `VCharacterEmojiPanel m_emojiPanel`

- `Boolean m_needDetailUpdate`

- `Boolean m_stateChanged`

- `IMoveHolder m_moveHolder`

- `Single m_moveSpeed`

- `Single m_moveSpeedScale`

- `Vector2 m_direction`

- `VCharacter m_character`

- `IVCharInteractable m_interactCandidate`

- `DoorPosState m_doorPosState`

- `VDoor m_predictedDoor`

- `Options m_options`

- `Boolean <inElevatorRoom>k__BackingField`


## Properties

- `VCharacterElevatorController elevatorController`

- `Options options`

- `VCharacter character`

- `Single moveSpeed`

- `Boolean inControlMode`

- `Boolean inElevatorRoom`

- `Boolean interactable`

- `Boolean interacting`

- `Boolean specialnteractable`

- `Boolean moveable`

- `Boolean inUpDownstairs`

- `Boolean isGoingUp`

- `Boolean isGoingDown`

- `Boolean canGoUpstairs`

- `Boolean canGoDownstairs`

- `DoorPosState doorPosState`

- `VRoomSlot predictedNextSlot`


## Methods

- `VCharacterElevatorController get_elevatorController()`

- `Options get_options()`

- `VCharacter get_character()`

- `Single get_moveSpeed()`

- `Boolean get_inControlMode()`

- `Boolean get_inElevatorRoom()`

- `Void set_inElevatorRoom(Boolean)`

- `Boolean get_interactable()`

- `Boolean get_interacting()`

- `Boolean get_specialnteractable()`

- `Boolean get_moveable()`

- `Boolean get_inUpDownstairs()`

- `Boolean get_isGoingUp()`

- `Boolean get_isGoingDown()`

- `Boolean get_canGoUpstairs()`

- `Boolean get_canGoDownstairs()`

- `DoorPosState get_doorPosState()`

- `VRoomSlot get_predictedNextSlot()`

- `Void SetMoveHolder(IMoveHolder)`

- `Boolean StartControlVChar(VCharacter)`

- `Boolean StopControl()`

- `Void VCharacterGoUpstairs()`

- `Void VCharacterGoDownstairs()`

- `Void InteractInControl()`

- `Void SpecialInteractInControl()`

- `Void VCharacterShowEmoji(String)`

- `VRoom GetVRoomBySlotId(String)`

- `Void VCharacterMove(ref)`

- `Void _DoVCharMove(Vector2)`

- `Void _DisableCurrentHighlight()`

- `Void _RefreshHighlightDoor(GridPosition)`

- `Boolean IsPositionDoorRow(GridPosition)`

- `Boolean _CheckMovePositionChangeRoom(GridPosition)`

- `DoorPosState _RefreshDoorPosState(GridPosition)`

- `Boolean VCharRoomChanged(VCharacter, VRoom, Boolean)`

- `Void _RefreshInteractCandidate()`

- `Boolean _FindInteractFurnitureSlotCandidate()`

- `Boolean _FindInteractVFurnitureEntityCandidate()`

- `Void _OnRoomUpdated()`

- `Void _NotifyNeedDetialUpdate()`

- `Void NotifyStateChanged()`

- `Void _OnStateChanged()`

- `Void _UpdateControlInput()`

- `Void FocusCharacter()`

- `Void Update()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VCharacterController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	private Single _moveMaxSpeed; // 0x18
	private Single _moveSpeed; // 0x1c
	private Single _moveAnimScale; // 0x20
	private Single _colliderRangeY; // 0x24
	private Single _cameraFocusMaxDist; // 0x28
	private Single _cameraZoom; // 0x2c
	private Boolean _highlightWhenMove; // 0x30
	private Boolean _forceIdleWhenCannotMove; // 0x31
	private Single _elevatorTime; // 0x34
	private Single _elevatorAutoMoveTime; // 0x38
	private AnimationCurve _elevatorCurve; // 0x40
	private Single _elevatorHeightOffset; // 0x48
	private Single _distanceToInteract; // 0x4c
	private Single _distanceToInteractUpdate; // 0x50
	private Single _focusDoorSpeedRatio; // 0x54
	private Single _speedToLeaveInteract; // 0x58
	private Boolean _canInterruptSpecialAnim; // 0x5c
	private VCharacterEmojiPanel _emojiPanel; // 0x60
	private VCharacterElevatorController m_elevatorController; // 0x68
	private VCharacterMoveChecker m_moveChecker; // 0x70
	private VCharacterEmojiPanel m_emojiPanel; // 0x78
	private Boolean m_needDetailUpdate; // 0x80
	private Boolean m_stateChanged; // 0x81
	private IMoveHolder m_moveHolder; // 0x88
	private Single m_moveSpeed; // 0x90
	private Single m_moveSpeedScale; // 0x94
	private Vector2 m_direction; // 0x98
	private VCharacter m_character; // 0xa0
	private IVCharInteractable m_interactCandidate; // 0xa8
	private DoorPosState m_doorPosState; // 0xb0
	private VDoor m_predictedDoor; // 0xb8
	private Options m_options; // 0xc0
	private Boolean <inElevatorRoom>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_elevatorController; // 0x0
	private static DelegateBridge __Hotfix0_get_options; // 0x8
	private static DelegateBridge __Hotfix0_get_character; // 0x10
	private static DelegateBridge __Hotfix0_get_moveSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_inControlMode; // 0x20
	private static DelegateBridge __Hotfix0_get_inElevatorRoom; // 0x28
	private static DelegateBridge __Hotfix0_set_inElevatorRoom; // 0x30
	private static DelegateBridge __Hotfix0_get_interactable; // 0x38
	private static DelegateBridge __Hotfix0_get_interacting; // 0x40
	private static DelegateBridge __Hotfix0_get_specialnteractable; // 0x48
	private static DelegateBridge __Hotfix0_get_moveable; // 0x50
	private static DelegateBridge __Hotfix0_get_inUpDownstairs; // 0x58
	private static DelegateBridge __Hotfix0_get_isGoingUp; // 0x60
	private static DelegateBridge __Hotfix0_get_isGoingDown; // 0x68
	private static DelegateBridge __Hotfix0_get_canGoUpstairs; // 0x70
	private static DelegateBridge __Hotfix0_get_canGoDownstairs; // 0x78
	private static DelegateBridge __Hotfix0_get_doorPosState; // 0x80
	private static DelegateBridge __Hotfix0_get_predictedNextSlot; // 0x88
	private static DelegateBridge __Hotfix0_SetMoveHolder; // 0x90
	private static DelegateBridge __Hotfix0_StartControlVChar; // 0x98
	private static DelegateBridge __Hotfix0_StopControl; // 0xa0
	private static DelegateBridge __Hotfix0_VCharacterGoUpstairs; // 0xa8
	private static DelegateBridge __Hotfix0_VCharacterGoDownstairs; // 0xb0
	private static DelegateBridge __Hotfix0_InteractInControl; // 0xb8
	private static DelegateBridge __Hotfix0_SpecialInteractInControl; // 0xc0
	private static DelegateBridge __Hotfix0_VCharacterShowEmoji; // 0xc8
	private static DelegateBridge __Hotfix0_GetVRoomBySlotId; // 0xd0
	private static DelegateBridge __Hotfix0_VCharacterMove; // 0xd8
	private static DelegateBridge __Hotfix0__DoVCharMove; // 0xe0
	private static DelegateBridge __Hotfix0__DisableCurrentHighlight; // 0xe8
	private static DelegateBridge __Hotfix0__RefreshHighlightDoor; // 0xf0
	private static DelegateBridge __Hotfix0_IsPositionDoorRow; // 0xf8
	private static DelegateBridge __Hotfix0__CheckMovePositionChangeRoom; // 0x100
	private static DelegateBridge __Hotfix0__RefreshDoorPosState; // 0x108
	private static DelegateBridge __Hotfix0_VCharRoomChanged; // 0x110
	private static DelegateBridge __Hotfix0__RefreshInteractCandidate; // 0x118
	private static DelegateBridge __Hotfix0__FindInteractFurnitureSlotCandidate; // 0x120
	private static DelegateBridge __Hotfix0__FindInteractVFurnitureEntityCandidate; // 0x128
	private static DelegateBridge __Hotfix0__OnRoomUpdated; // 0x130
	private static DelegateBridge __Hotfix0__NotifyNeedDetialUpdate; // 0x138
	private static DelegateBridge __Hotfix0_NotifyStateChanged; // 0x140
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x148
	private static DelegateBridge __Hotfix0__UpdateControlInput; // 0x150
	private static DelegateBridge __Hotfix0_FocusCharacter; // 0x158
	private static DelegateBridge __Hotfix0_Update; // 0x160
	private static DelegateBridge __Hotfix0_OnDisable; // 0x168
	private static DelegateBridge __Hotfix0_Awake; // 0x170
	private static DelegateBridge _c__Hotfix0_ctor; // 0x178

	public VCharacterElevatorController elevatorController { get; }
	public Options options { get; }
	public VCharacter character { get; }
	public Single moveSpeed { get; }
	public Boolean inControlMode { get; }
	public Boolean inElevatorRoom { get; set; }
	public Boolean interactable { get; }
	public Boolean interacting { get; }
	public Boolean specialnteractable { get; }
	public Boolean moveable { get; }
	public Boolean inUpDownstairs { get; }
	public Boolean isGoingUp { get; }
	public Boolean isGoingDown { get; }
	public Boolean canGoUpstairs { get; }
	public Boolean canGoDownstairs { get; }
	public DoorPosState doorPosState { get; }
	private VRoomSlot predictedNextSlot { get; }

	// RVA: 0x3cfbf38 VA: 0x7596313f38
	public VCharacterElevatorController get_elevatorController() { }
	// RVA: 0x3cfbfa0 VA: 0x7596313fa0
	public Options get_options() { }
	// RVA: 0x3cfc03c VA: 0x759631403c
	public VCharacter get_character() { }
	// RVA: 0x3cfc0a4 VA: 0x75963140a4
	public Single get_moveSpeed() { }
	// RVA: 0x3cf65cc VA: 0x759630e5cc
	public Boolean get_inControlMode() { }
	// RVA: 0x3cfc10c VA: 0x759631410c
	public Boolean get_inElevatorRoom() { }
	// RVA: 0x3cfc174 VA: 0x7596314174
	private Void set_inElevatorRoom(Boolean value) { }
	// RVA: 0x3cfc1f4 VA: 0x75963141f4
	public Boolean get_interactable() { }
	// RVA: 0x3cfc278 VA: 0x7596314278
	public Boolean get_interacting() { }
	// RVA: 0x3cfc30c VA: 0x759631430c
	public Boolean get_specialnteractable() { }
	// RVA: 0x3cfc3b8 VA: 0x75963143b8
	public Boolean get_moveable() { }
	// RVA: 0x3cfc448 VA: 0x7596314448
	public Boolean get_inUpDownstairs() { }
	// RVA: 0x3cfc53c VA: 0x759631453c
	public Boolean get_isGoingUp() { }
	// RVA: 0x3cfc614 VA: 0x7596314614
	public Boolean get_isGoingDown() { }
	// RVA: 0x3cfc6ec VA: 0x75963146ec
	public Boolean get_canGoUpstairs() { }
	// RVA: 0x3cfc860 VA: 0x7596314860
	public Boolean get_canGoDownstairs() { }
	// RVA: 0x3cfc8d8 VA: 0x75963148d8
	public DoorPosState get_doorPosState() { }
	// RVA: 0x3cfc940 VA: 0x7596314940
	private VRoomSlot get_predictedNextSlot() { }
	// RVA: 0x3cfc9f0 VA: 0x75963149f0
	public Void SetMoveHolder(IMoveHolder moveHolder) { }
	// RVA: 0x3cfca74 VA: 0x7596314a74
	public Boolean StartControlVChar(VCharacter character) { }
	// RVA: 0x3cfd51c VA: 0x759631551c
	public Boolean StopControl() { }
	// RVA: 0x3cfd928 VA: 0x7596315928
	public Void VCharacterGoUpstairs() { }
	// RVA: 0x3cfdab0 VA: 0x7596315ab0
	public Void VCharacterGoDownstairs() { }
	// RVA: 0x3cfdb58 VA: 0x7596315b58
	public Void InteractInControl() { }
	// RVA: 0x3cfdcc4 VA: 0x7596315cc4
	public Void SpecialInteractInControl() { }
	// RVA: 0x3cfdd58 VA: 0x7596315d58
	public Void VCharacterShowEmoji(String emojiId) { }
	// RVA: 0x3cfde4c VA: 0x7596315e4c
	public VRoom GetVRoomBySlotId(String slotId) { }
	// RVA: 0x3cfdf78 VA: 0x7596315f78
	public Void VCharacterMove(ref Vector2 direction) { }
	// RVA: 0x3cfe390 VA: 0x7596316390
	private Void _DoVCharMove(Vector2 direction) { }
	// RVA: 0x3cfcd0c VA: 0x7596314d0c
	private Void _DisableCurrentHighlight() { }
	// RVA: 0x3cfe860 VA: 0x7596316860
	private Void _RefreshHighlightDoor(GridPosition pos) { }
	// RVA: 0x3cfea50 VA: 0x7596316a50
	public Boolean IsPositionDoorRow(GridPosition pos) { }
	// RVA: 0x3cfe688 VA: 0x7596316688
	private Boolean _CheckMovePositionChangeRoom(GridPosition pos) { }
	// RVA: 0x3cfe260 VA: 0x7596316260
	private DoorPosState _RefreshDoorPosState(GridPosition pos) { }
	// RVA: 0x3cfe750 VA: 0x7596316750
	public Boolean VCharRoomChanged(VCharacter character, VRoom room, Boolean force) { }
	// RVA: 0x3cfce80 VA: 0x7596314e80
	public Void _RefreshInteractCandidate() { }
	// RVA: 0x3cfead4 VA: 0x7596316ad4
	private Boolean _FindInteractFurnitureSlotCandidate() { }
	// RVA: 0x3cfeda4 VA: 0x7596316da4
	private Boolean _FindInteractVFurnitureEntityCandidate() { }
	// RVA: 0x3cfd068 VA: 0x7596315068
	private Void _OnRoomUpdated() { }
	// RVA: 0x3cff098 VA: 0x7596317098
	private Void _NotifyNeedDetialUpdate() { }
	// RVA: 0x3cfd8bc VA: 0x75963158bc
	public Void NotifyStateChanged() { }
	// RVA: 0x3cff1e8 VA: 0x75963171e8
	private Void _OnStateChanged() { }
	// RVA: 0x3cff2cc VA: 0x75963172cc
	private Void _UpdateControlInput() { }
	// RVA: 0x3cff4b8 VA: 0x75963174b8
	private Void FocusCharacter() { }
	// RVA: 0x3cff574 VA: 0x7596317574
	private Void Update() { }
	// RVA: 0x3cff5dc VA: 0x75963175dc
	private Void OnDisable() { }
	// RVA: 0x3cffc64 VA: 0x7596317c64
	protected override Void Awake() { }
	// RVA: 0x3cffffc VA: 0x7596317ffc
	public Void .ctor() { }
}
```