# VCameraController

**Namespace:** `Torappu.Building.Vault`


## Fields

- `MobileTouchCamera _touchCamera`

- `FocusMatchType _matchType`

- `Vector2 _focsusZRange`

- `Vector2 _roomWidthRange`

- `Vector2 _roomHeightRange`

- `Single _planeHeightOffset`

- `Single _focusTime`

- `Ease _focusEaseType`

- `Single _flashInTime`

- `Ease _flashInEaseType`

- `Single _flashInFromZ`

- `Single _flashOutTime`

- `Ease _flashOutEaseType`

- `Tween m_tween`

- `Vector3 m_initialPosition`

- `UnityEvent onDragOrPinch`

- `OnZoomUpdateEvent onZoomUpdate`

- `LODState <lodState>k__BackingField`


## Properties

- `Camera camera`

- `Boolean enableTouchCamera`

- `Boolean isTweening`

- `Boolean isDraggingOrPinching`

- `LODState lodState`

- `Single camZoom`

- `Single camZoomMax`

- `Single camZoomMin`


## Methods

- `Camera get_camera()`

- `Boolean get_enableTouchCamera()`

- `Void set_enableTouchCamera(Boolean)`

- `Boolean get_isTweening()`

- `Boolean get_isDraggingOrPinching()`

- `LODState get_lodState()`

- `Void set_lodState(LODState)`

- `Single get_camZoom()`

- `Void set_camZoom(Single)`

- `Single get_camZoomMax()`

- `Single get_camZoomMin()`

- `Void SetBoundingBox(Rect, Boolean)`

- `Tween Focus(VRoomSlot, Boolean)`

- `Tween Focus(Object, Single, Single, Boolean)`

- `Tween ForcusCharacter(VCharacter, Boolean)`

- `Tween ForcusCharacter(VCharacter, Single, Boolean)`

- `Void ForcusCharacterInControl(VCharacter, Single, Single, Single)`

- `Tween ForcusFurniture(VFurnitureEntity, Boolean)`

- `Tween Focus(Vector3, Boolean)`

- `Tween FlashIn(VRoomSlot, Boolean, Boolean)`

- `Tween FlashOut(Boolean)`

- `Void ResetCameraPosition()`

- `Void UpdateTouchCamera()`

- `Void AddLODListener(ILODListener)`

- `Void RemoveLODListener(ILODListener)`

- `Void UpdateLOD(Int32)`

- `Void _NotifyLODLevelChanged()`

- `Void _UpdateLOD()`

- `Tween _FocusInternal(Vector3, Boolean, Single, Ease)`

- `Vector3 _CalculateFocusPosition(VRoomSlot)`

- `Void _StopTween()`

- `Void _OnDragOrPinch()`

- `Void _OnZoomUpdate(Single, Single)`

- `Void Start()`

- `Void _InitCamera(Camera)`

- `Void Update()`

- `Vector3 <_FocusInternal>b__57_0()`

- `Void <_FocusInternal>b__57_1(Vector3)`

- `Void <Start>b__62_1(Vector3, Single, Single)`

- `Void <Start>b__62_2(Vector3, Vector3, Vector3)`

- `Void <Start>b__62_0(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VCameraController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable, ILODHolder
{
	private MobileTouchCamera _touchCamera; // 0x18
	private FocusMatchType _matchType; // 0x20
	private Vector2 _focsusZRange; // 0x24
	private Vector2 _roomWidthRange; // 0x2c
	private Vector2 _roomHeightRange; // 0x34
	private Single _planeHeightOffset; // 0x3c
	private Single _focusTime; // 0x40
	private Ease _focusEaseType; // 0x44
	private Single _flashInTime; // 0x48
	private Ease _flashInEaseType; // 0x4c
	private Single _flashInFromZ; // 0x50
	private Single _flashOutTime; // 0x54
	private Ease _flashOutEaseType; // 0x58
	private Tween m_tween; // 0x60
	private Vector3 m_initialPosition; // 0x68
	public UnityEvent onDragOrPinch; // 0x78
	public OnZoomUpdateEvent onZoomUpdate; // 0x80
	private List`1 m_lodListeners; // 0x88
	private LODState <lodState>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_camera; // 0x0
	private static DelegateBridge __Hotfix0_get_enableTouchCamera; // 0x8
	private static DelegateBridge __Hotfix0_set_enableTouchCamera; // 0x10
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x18
	private static DelegateBridge __Hotfix0_get_isDraggingOrPinching; // 0x20
	private static DelegateBridge __Hotfix0_get_lodState; // 0x28
	private static DelegateBridge __Hotfix0_set_lodState; // 0x30
	private static DelegateBridge __Hotfix0_get_camZoom; // 0x38
	private static DelegateBridge __Hotfix0_set_camZoom; // 0x40
	private static DelegateBridge __Hotfix0_get_camZoomMax; // 0x48
	private static DelegateBridge __Hotfix0_get_camZoomMin; // 0x50
	private static DelegateBridge __Hotfix0_SetBoundingBox; // 0x58
	private static DelegateBridge __Hotfix0_Focus; // 0x60
	private static DelegateBridge __Hotfix1_Focus; // 0x68
	private static DelegateBridge __Hotfix0_ForcusCharacter; // 0x70
	private static DelegateBridge __Hotfix1_ForcusCharacter; // 0x78
	private static DelegateBridge __Hotfix0_ForcusCharacterInControl; // 0x80
	private static DelegateBridge __Hotfix0_ForcusFurniture; // 0x88
	private static DelegateBridge __Hotfix2_Focus; // 0x90
	private static DelegateBridge __Hotfix0_FlashIn; // 0x98
	private static DelegateBridge __Hotfix0_FlashOut; // 0xa0
	private static DelegateBridge __Hotfix0_ResetCameraPosition; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateTouchCamera; // 0xb0
	private static DelegateBridge __Hotfix0_AddLODListener; // 0xb8
	private static DelegateBridge __Hotfix0_RemoveLODListener; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateLOD; // 0xc8
	private static DelegateBridge __Hotfix0__NotifyLODLevelChanged; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateLOD; // 0xd8
	private static DelegateBridge __Hotfix0__FocusInternal; // 0xe0
	private static DelegateBridge __Hotfix0__CalculateFocusPosition; // 0xe8
	private static DelegateBridge __Hotfix0__StopTween; // 0xf0
	private static DelegateBridge __Hotfix0__OnDragOrPinch; // 0xf8
	private static DelegateBridge __Hotfix0__OnZoomUpdate; // 0x100
	private static DelegateBridge __Hotfix0_Start; // 0x108
	private static DelegateBridge __Hotfix0__InitCamera; // 0x110
	private static DelegateBridge __Hotfix0_Update; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public Camera camera { get; }
	public Boolean enableTouchCamera { get; set; }
	public Boolean isTweening { get; }
	public Boolean isDraggingOrPinching { get; }
	public LODState lodState { get; set; }
	public Single camZoom { get; set; }
	public Single camZoomMax { get; }
	public Single camZoomMin { get; }

	// RVA: 0x3cf9da8 VA: 0x7596311da8
	public Camera get_camera() { }
	// RVA: 0x3cf9e1c VA: 0x7596311e1c
	public Boolean get_enableTouchCamera() { }
	// RVA: 0x3cf9e90 VA: 0x7596311e90
	public Void set_enableTouchCamera(Boolean value) { }
	// RVA: 0x3cf9f54 VA: 0x7596311f54
	public Boolean get_isTweening() { }
	// RVA: 0x3cf9fd0 VA: 0x7596311fd0
	public Boolean get_isDraggingOrPinching() { }
	// RVA: 0x3cf5b6c VA: 0x759630db6c
	public LODState get_lodState() { }
	// RVA: 0x3cfa044 VA: 0x7596312044
	public Void set_lodState(LODState value) { }
	// RVA: 0x3cfa0c8 VA: 0x75963120c8
	public Single get_camZoom() { }
	// RVA: 0x3cfa13c VA: 0x759631213c
	public Void set_camZoom(Single value) { }
	// RVA: 0x3cfa1c8 VA: 0x75963121c8
	public Single get_camZoomMax() { }
	// RVA: 0x3cfa23c VA: 0x759631223c
	public Single get_camZoomMin() { }
	// RVA: 0x3cfa2b0 VA: 0x75963122b0
	public Void SetBoundingBox(Rect boundingBox, Boolean moveToCenter) { }
	// RVA: 0x3cfa418 VA: 0x7596312418
	public Tween Focus(VRoomSlot room, Boolean tween) { }
	// RVA: 0x3cfa684 VA: 0x7596312684
	public Tween Focus(Object roomObject, Single worldY, Single worldZ, Boolean tween) { }
	// RVA: 0x3cfa83c VA: 0x759631283c
	public Tween ForcusCharacter(VCharacter roomChar, Boolean tween) { }
	// RVA: 0x3cfa8ec VA: 0x75963128ec
	public Tween ForcusCharacter(VCharacter roomChar, Single targetZ, Boolean tween) { }
	// RVA: 0x3cfa9bc VA: 0x75963129bc
	public Void ForcusCharacterInControl(VCharacter roomChar, Single targetX, Single targetZ, Single maxDist) { }
	// RVA: 0x3cfacf0 VA: 0x7596312cf0
	public Tween ForcusFurniture(VFurnitureEntity roomfurnitue, Boolean tween) { }
	// RVA: 0x3cfa5c0 VA: 0x75963125c0
	public Tween Focus(Vector3 pos, Boolean tween) { }
	// RVA: 0x3cf9c30 VA: 0x7596311c30
	public Tween FlashIn(VRoomSlot room, Boolean tween, Boolean fromInitPos) { }
	// RVA: 0x3cf9a50 VA: 0x7596311a50
	public Tween FlashOut(Boolean tween) { }
	// RVA: 0x3cf80ac VA: 0x75963100ac
	public Void ResetCameraPosition() { }
	// RVA: 0x3cf7434 VA: 0x759630f434
	public Void UpdateTouchCamera() { }
	// RVA: 0x3cf5a34 VA: 0x759630da34
	public Void AddLODListener(ILODListener listener) { }
	// RVA: 0x3cfb0c4 VA: 0x75963130c4
	public Void RemoveLODListener(ILODListener listener) { }
	// RVA: 0x3cfb1d8 VA: 0x75963131d8
	public Void UpdateLOD(Int32 lod) { }
	// RVA: 0x3cfb294 VA: 0x7596313294
	private Void _NotifyLODLevelChanged() { }
	// RVA: 0x3cfb42c VA: 0x759631342c
	private Void _UpdateLOD() { }
	// RVA: 0x3cfadd0 VA: 0x7596312dd0
	private Tween _FocusInternal(Vector3 pos, Boolean tween, Single time, Ease easeType) { }
	// RVA: 0x3cfa4ac VA: 0x75963124ac
	private Vector3 _CalculateFocusPosition(VRoomSlot room) { }
	// RVA: 0x3cfb524 VA: 0x7596313524
	private Void _StopTween() { }
	// RVA: 0x3cfb5b4 VA: 0x75963135b4
	private Void _OnDragOrPinch() { }
	// RVA: 0x3cfb648 VA: 0x7596313648
	private Void _OnZoomUpdate(Single oldSize, Single newSize) { }
	// RVA: 0x3cfb6f4 VA: 0x75963136f4
	private Void Start() { }
	// RVA: 0x3cfb998 VA: 0x7596313998
	private Void _InitCamera(Camera cam) { }
	// RVA: 0x3cfba6c VA: 0x7596313a6c
	private Void Update() { }
	// RVA: 0x3cfbadc VA: 0x7596313adc
	public Void .ctor() { }
	// RVA: 0x3cfbcd4 VA: 0x7596313cd4
	private Vector3 <_FocusInternal>b__57_0() { }
	// RVA: 0x3cfbcfc VA: 0x7596313cfc
	private Void <_FocusInternal>b__57_1(Vector3 p) { }
	// RVA: 0x3cfbd60 VA: 0x7596313d60
	private Void <Start>b__62_1(Vector3 _1, Single distance, Single startDist) { }
	// RVA: 0x3cfbde8 VA: 0x7596313de8
	private Void <Start>b__62_2(Vector3 startPos, Vector3 curPos, Vector3 _3) { }
	// RVA: 0x3cfbea8 VA: 0x7596313ea8
	private Void <Start>b__62_0(Single oldSize, Single newSize) { }
}
```