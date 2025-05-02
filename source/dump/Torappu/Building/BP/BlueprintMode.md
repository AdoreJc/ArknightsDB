# BlueprintMode

**Namespace:** `Torappu.Building.BP`


## Fields

- `BLayoutManager _layout`

- `Camera _camera`

- `Transform _raycastBlocker`

- `CanvasGroup _hilightMask`

- `CameraTweenConfig _tweenOnInitConfig`

- `CameraTweenConfig _tweenToMaxConfig`

- `Boolean _blockRaycastInTween`

- `BRoomHilightViewModel m_hilightModel`

- `FadeSwitchTween m_hilightMaskTween`

- `Tween m_sharedBPPositionTween`

- `BCameraController m_bCamController`

- `IPlugin m_plugin`


## Properties

- `BCameraController bCamController`

- `IPlugin plugin`

- `Camera camera`


## Methods

- `BCameraController get_bCamController()`

- `IPlugin get_plugin()`

- `Void set_plugin(IPlugin)`

- `Camera get_camera()`

- `Void EnterArchitectureMode()`

- `Void ExitArchitectureMode()`

- `Void OnArchitectureRoomSelected(RoomSlotModel)`

- `Void CameraZoomToMax()`

- `Void CameraTweenOnModeInit()`

- `Void CameraTweenTo(Single, Boolean, CameraTweenConfig)`

- `Void _TweenBPCamPosTo(Vector3, Boolean, CameraTweenConfig)`

- `Void HilightRoomSlots(List`1, BuildingToDoCategory, BuildingToDoType)`

- `Void NotifySettleEffects(RoomType)`

- `Vector2 GetRoomAnchor(String)`

- `Void EventOnHilightedMaskClicked()`

- `IEnumerator <>n__0(TransitionParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BlueprintMode : BuildingMode`1, IListener
{
	private BLayoutManager _layout; // 0x20
	private Camera _camera; // 0x28
	private Transform _raycastBlocker; // 0x30
	private CanvasGroup _hilightMask; // 0x38
	private CameraTweenConfig _tweenOnInitConfig; // 0x40
	private CameraTweenConfig _tweenToMaxConfig; // 0x4c
	private Boolean _blockRaycastInTween; // 0x58
	private BRoomHilightViewModel m_hilightModel; // 0x60
	private FadeSwitchTween m_hilightMaskTween; // 0x68
	private Tween m_sharedBPPositionTween; // 0x70
	private BCameraController m_bCamController; // 0x78
	private IPlugin m_plugin; // 0x80
	private static DelegateBridge __Hotfix0_get_bCamController; // 0x0
	private static DelegateBridge __Hotfix0_get_plugin; // 0x8
	private static DelegateBridge __Hotfix0_set_plugin; // 0x10
	private static DelegateBridge __Hotfix0_get_camera; // 0x18
	private static DelegateBridge __Hotfix0_get_AVGOnly_layout; // 0x20
	private static DelegateBridge __Hotfix0_EnterArchitectureMode; // 0x28
	private static DelegateBridge __Hotfix0_ExitArchitectureMode; // 0x30
	private static DelegateBridge __Hotfix0_OnArchitectureRoomSelected; // 0x38
	private static DelegateBridge __Hotfix0_get_isRaycastBlocked; // 0x40
	private static DelegateBridge __Hotfix0_set_isRaycastBlocked; // 0x48
	private static DelegateBridge __Hotfix0_get_selectedRoom; // 0x50
	private static DelegateBridge __Hotfix0_OnRegister; // 0x58
	private static DelegateBridge __Hotfix0_OnEnter; // 0x60
	private static DelegateBridge __Hotfix0_OnExit; // 0x68
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x70
	private static DelegateBridge __Hotfix0_CameraZoomToMax; // 0x78
	private static DelegateBridge __Hotfix0_CameraTweenOnModeInit; // 0x80
	private static DelegateBridge __Hotfix0_CameraTweenTo; // 0x88
	private static DelegateBridge __Hotfix0__TweenBPCamPosTo; // 0x90
	private static DelegateBridge __Hotfix0_HilightRoomSlots; // 0x98
	private static DelegateBridge __Hotfix0_NotifySettleEffects; // 0xa0
	private static DelegateBridge __Hotfix0_GetRoomAnchor; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnHilightedMaskClicked; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	protected BCameraController bCamController { get; }
	public IPlugin plugin { get; set; }
	public Camera camera { get; }
	internal BLayoutManager AVGOnly_layout { get; }
	public override Boolean isRaycastBlocked { get; set; }
	public override RoomSlotModel selectedRoom { get; }

	// RVA: 0x3d156f4 VA: 0x759632d6f4
	protected BCameraController get_bCamController() { }
	// RVA: 0x3d157c4 VA: 0x759632d7c4
	public IPlugin get_plugin() { }
	// RVA: 0x3d1582c VA: 0x759632d82c
	public Void set_plugin(IPlugin value) { }
	// RVA: 0x3d13120 VA: 0x759632b120
	public Camera get_camera() { }
	// RVA: 0x3d159a8 VA: 0x759632d9a8
	internal BLayoutManager get_AVGOnly_layout() { }
	// RVA: 0x3d11cbc VA: 0x7596329cbc
	public Void EnterArchitectureMode() { }
	// RVA: 0x3d11d94 VA: 0x7596329d94
	public Void ExitArchitectureMode() { }
	// RVA: 0x3d15a10 VA: 0x759632da10
	public Void OnArchitectureRoomSelected(RoomSlotModel room) { }
	// RVA: 0x3d15b10 VA: 0x759632db10
	public override Boolean get_isRaycastBlocked() { }
	// RVA: 0x3d15b90 VA: 0x759632db90
	public override Void set_isRaycastBlocked(Boolean value) { }
	// RVA: 0x3d15c80 VA: 0x759632dc80
	public override RoomSlotModel get_selectedRoom() { }
	// RVA: 0x3d15d48 VA: 0x759632dd48
	protected override Void OnRegister() { }
	// RVA: 0x3d15de8 VA: 0x759632dde8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3d15ea4 VA: 0x759632dea4
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x3d15f60 VA: 0x759632df60
	public override IEnumerator HideCoroutine(TransitionParam param) { }
	// RVA: 0x3d1607c VA: 0x759632e07c
	public Void CameraZoomToMax() { }
	// RVA: 0x3d162bc VA: 0x759632e2bc
	public Void CameraTweenOnModeInit() { }
	// RVA: 0x3d16104 VA: 0x759632e104
	public Void CameraTweenTo(Single toZoom, Boolean tweenToLeft, CameraTweenConfig tweenConfig) { }
	// RVA: 0x3d16340 VA: 0x759632e340
	private Void _TweenBPCamPosTo(Vector3 targetPos, Boolean forceStart, CameraTweenConfig config) { }
	// RVA: 0x3d167c0 VA: 0x759632e7c0
	public Void HilightRoomSlots(List`1 slotIds, BuildingToDoCategory selectedCategory, BuildingToDoType selectedType) { }
	// RVA: 0x3d16b18 VA: 0x759632eb18
	public Void NotifySettleEffects(RoomType roomType) { }
	// RVA: 0x3d16ba0 VA: 0x759632eba0
	public Vector2 GetRoomAnchor(String slotId) { }
	// RVA: 0x3d16c28 VA: 0x759632ec28
	public Void EventOnHilightedMaskClicked() { }
	// RVA: 0x3d16cdc VA: 0x759632ecdc
	public Void .ctor() { }
	// RVA: 0x3d16e38 VA: 0x759632ee38
	private IEnumerator <>n__0(TransitionParam param) { }
}
```