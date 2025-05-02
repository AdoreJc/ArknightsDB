# VaultMode

**Namespace:** `Torappu.Building.Vault`


## Fields

- `VLayoutManager _layout`

- `Camera _camera`

- `Transform _raycastBlocker`

- `VCharacterManager m_characterMgr`

- `VaultReflectionConfigHolder m_reflectConfig`

- `Boolean m_isReflectConfigUnavailable`


## Properties

- `Camera camera`

- `Transform roomContainer`

- `VRoomSlot selectedRoomSlot`

- `Boolean isActiveAndDisplayed`

- `VLayoutManager layout`


## Methods

- `Camera get_camera()`

- `Transform get_roomContainer()`

- `VRoomSlot get_selectedRoomSlot()`

- `Boolean get_isActiveAndDisplayed()`

- `VLayoutManager get_layout()`

- `Void StopAllMusicInteractFurniture()`

- `Void RegisterCharacter(VCharacter)`

- `Void UnregisterCharacter(VCharacter)`

- `Void ZoomInToRoom(RoomSlotModel)`

- `Void SelectRoomWithoutFocus(RoomSlotModel)`

- `VaultReflectionConfigHolder _EnsureReflectConfig()`

- `IRefectionMaterialFilter GetRefectFilter()`

- `ReflectCameraHolder GetReflectCameraHolder(VDIYRoom)`

- `VRoomSlot GetRoom(RoomSlotModel)`

- `IEnumerator _FocusRoomCoroutine(RoomSlotModel)`

- `IEnumerator <>n__0(TransitionParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VaultMode : BuildingMode`1
{
	private VLayoutManager _layout; // 0x20
	private Camera _camera; // 0x28
	private Transform _raycastBlocker; // 0x30
	private VCharacterManager m_characterMgr; // 0x38
	private VaultReflectionConfigHolder m_reflectConfig; // 0x40
	private Boolean m_isReflectConfigUnavailable; // 0x48
	private static DelegateBridge __Hotfix0_get_camera; // 0x0
	private static DelegateBridge __Hotfix0_get_isRaycastBlocked; // 0x8
	private static DelegateBridge __Hotfix0_set_isRaycastBlocked; // 0x10
	private static DelegateBridge __Hotfix0_get_roomContainer; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedRoom; // 0x20
	private static DelegateBridge __Hotfix0_get_selectedRoomSlot; // 0x28
	private static DelegateBridge __Hotfix0_get_isActiveAndDisplayed; // 0x30
	private static DelegateBridge __Hotfix0_get_layout; // 0x38
	private static DelegateBridge __Hotfix0_OnRegister; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58
	private static DelegateBridge __Hotfix0_StopAllMusicInteractFurniture; // 0x60
	private static DelegateBridge __Hotfix0_RegisterCharacter; // 0x68
	private static DelegateBridge __Hotfix0_UnregisterCharacter; // 0x70
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x78
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x80
	private static DelegateBridge __Hotfix0_ZoomInToRoom; // 0x88
	private static DelegateBridge __Hotfix0_SelectRoomWithoutFocus; // 0x90
	private static DelegateBridge __Hotfix0__EnsureReflectConfig; // 0x98
	private static DelegateBridge __Hotfix0_GetRefectFilter; // 0xa0
	private static DelegateBridge __Hotfix0_GetReflectCameraHolder; // 0xa8
	private static DelegateBridge __Hotfix0_GetRoom; // 0xb0
	private static DelegateBridge __Hotfix0__FocusRoomCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0_Awake; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Camera camera { get; }
	public override Boolean isRaycastBlocked { get; set; }
	public Transform roomContainer { get; }
	public override RoomSlotModel selectedRoom { get; }
	public VRoomSlot selectedRoomSlot { get; }
	public Boolean isActiveAndDisplayed { get; }
	public VLayoutManager layout { get; }

	// RVA: 0x3cf7290 VA: 0x759630f290
	public Camera get_camera() { }
	// RVA: 0x3cf72f8 VA: 0x759630f2f8
	public override Boolean get_isRaycastBlocked() { }
	// RVA: 0x3cf7378 VA: 0x759630f378
	public override Void set_isRaycastBlocked(Boolean value) { }
	// RVA: 0x3cf7528 VA: 0x759630f528
	public Transform get_roomContainer() { }
	// RVA: 0x3cf7600 VA: 0x759630f600
	public override RoomSlotModel get_selectedRoom() { }
	// RVA: 0x3cf77a8 VA: 0x759630f7a8
	public VRoomSlot get_selectedRoomSlot() { }
	// RVA: 0x3cf781c VA: 0x759630f81c
	public Boolean get_isActiveAndDisplayed() { }
	// RVA: 0x3cf76d8 VA: 0x759630f6d8
	public VLayoutManager get_layout() { }
	// RVA: 0x3cf78cc VA: 0x759630f8cc
	protected override Void OnRegister() { }
	// RVA: 0x3cf7ef0 VA: 0x759630fef0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3cf8144 VA: 0x7596310144
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x3cf82ac VA: 0x75963102ac
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x3cf85b8 VA: 0x75963105b8
	public Void StopAllMusicInteractFurniture() { }
	// RVA: 0x3cf8798 VA: 0x7596310798
	public Void RegisterCharacter(VCharacter character) { }
	// RVA: 0x3cf8950 VA: 0x7596310950
	public Void UnregisterCharacter(VCharacter character) { }
	// RVA: 0x3cf8a78 VA: 0x7596310a78
	public override IEnumerator ShowCoroutine(TransitionParam param) { }
	// RVA: 0x3cf8b94 VA: 0x7596310b94
	public override IEnumerator HideCoroutine(TransitionParam param) { }
	// RVA: 0x3cf8c9c VA: 0x7596310c9c
	public Void ZoomInToRoom(RoomSlotModel targetRoom) { }
	// RVA: 0x3cf8e24 VA: 0x7596310e24
	public Void SelectRoomWithoutFocus(RoomSlotModel targetRoom) { }
	// RVA: 0x3cf9100 VA: 0x7596311100
	protected VaultReflectionConfigHolder _EnsureReflectConfig() { }
	// RVA: 0x3cf933c VA: 0x759631133c
	public IRefectionMaterialFilter GetRefectFilter() { }
	// RVA: 0x3cf9408 VA: 0x7596311408
	public ReflectCameraHolder GetReflectCameraHolder(VDIYRoom vRoom) { }
	// RVA: 0x3cf94f0 VA: 0x75963114f0
	public VRoomSlot GetRoom(RoomSlotModel slotModel) { }
	// RVA: 0x3cf8d54 VA: 0x7596310d54
	private IEnumerator _FocusRoomCoroutine(RoomSlotModel targetRoom) { }
	// RVA: 0x3cf95b0 VA: 0x75963115b0
	protected override Void Awake() { }
	// RVA: 0x3cf9750 VA: 0x7596311750
	public Void .ctor() { }
	// RVA: 0x3cf97e0 VA: 0x75963117e0
	private IEnumerator <>n__0(TransitionParam param) { }
}
```