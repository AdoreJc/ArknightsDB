# BLayoutManager

**Namespace:** `Torappu.Building.BP`


## Fields

- `SafeParentComponent _container`

- `SafeParentComponent _hilightContainer`

- `ToggleGroup _toggleGroup`

- `RectTransform _frontground`

- `RectTransform _background`

- `Single _tweenTime`

- `Ease _tweenEaseType`

- `IListener <listener>k__BackingField`

- `Single m_initZoom`

- `BRoomSlot m_activeRoom`

- `BlueprintMode m_state`

- `BRoomHilightViewModel m_pendingHilightChange`


## Properties

- `IListener listener`

- `Single initZoom`

- `ToggleGroup toggleGroup`

- `Camera camera`

- `BRoomSlot selectedRoom`

- `Vector2 originPoint`


## Methods

- `IListener get_listener()`

- `Void set_listener(IListener)`

- `Single get_initZoom()`

- `ToggleGroup get_toggleGroup()`

- `Camera get_camera()`

- `BRoomSlot get_selectedRoom()`

- `Void set_selectedRoom(BRoomSlot)`

- `Void OnEnable()`

- `Void Init(List`1, BlueprintMode)`

- `Void OnEnter()`

- `Void OnExit()`

- `Void OnRoomClicked(BRoomSlot)`

- `Void FocusSelectedRoomForUI(Action`1)`

- `Void FocusRoomForUI(BRoomSlot, Action`1)`

- `Void UpdateRoomHilightStatus(BRoomHilightViewModel)`

- `Void _UpdateHilightStatus(BRoomHilightViewModel)`

- `Void _DealWithPendingHilight()`

- `Void _OnRoomClickNormal(BRoomSlot)`

- `Void _OnRoomClickArchitecture(BRoomSlot)`

- `Void _FocusToRoomBySide(BRoomSlot, LeftOrRight, Action`1)`

- `Tween ZoomTo(Single, BRoomSlot)`

- `Boolean TryGetRoomBySlotId(String, out)`

- `Vector2 get_originPoint()`

- `Void _ResetLayout()`

- `BRoomSlot _CreateRoom(RoomSlotModel)`

- `Void _ClearAll()`

- `Void _ResetToDefault()`

- `Void _SwitchToVault(BRoomSlot)`

- `Void _ResetFullBoundGround(RectTransform, Bounds, Vector2, Single)`

- `Rect _CalcLocalRectForBound(Bounds, RectTransform)`

- `Void NotifySettleEffect(RoomType)`

- `Vector2 GetRoomAnchorBySlotId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BLayoutManager : MonoBehaviour
{
	private static readonly Vector2 FTG_PADDING; // 0x0
	private static readonly Vector2 BKG_PADDING; // 0x8
	private const Single ZOOM_IN_FACTOR; // 0x0
	private SafeParentComponent _container; // 0x18
	private SafeParentComponent _hilightContainer; // 0x20
	private ToggleGroup _toggleGroup; // 0x28
	private RectTransform _frontground; // 0x30
	private RectTransform _background; // 0x38
	private Single _tweenTime; // 0x40
	private Ease _tweenEaseType; // 0x44
	private IListener <listener>k__BackingField; // 0x48
	private Single m_initZoom; // 0x50
	private BRoomSlot m_activeRoom; // 0x58
	private BlueprintMode m_state; // 0x60
	private List`1 m_rooms; // 0x68
	private Dictionary`2 m_modelToRoomMap; // 0x70
	private List`1 m_hilightedSlots; // 0x78
	private BRoomHilightViewModel m_pendingHilightChange; // 0x80

	private IListener listener { get; set; }
	public Single initZoom { get; }
	public ToggleGroup toggleGroup { get; }
	public Camera camera { get; }
	public BRoomSlot selectedRoom { get; set; }
	public Vector2 originPoint { get; }

	// RVA: 0x3d130e8 VA: 0x759632b0e8
	private IListener get_listener() { }
	// RVA: 0x3d130f0 VA: 0x759632b0f0
	public Void set_listener(IListener value) { }
	// RVA: 0x3d130f8 VA: 0x759632b0f8
	public Single get_initZoom() { }
	// RVA: 0x3d13100 VA: 0x759632b100
	public ToggleGroup get_toggleGroup() { }
	// RVA: 0x3d13108 VA: 0x759632b108
	public Camera get_camera() { }
	// RVA: 0x3d13188 VA: 0x759632b188
	public BRoomSlot get_selectedRoom() { }
	// RVA: 0x3d13190 VA: 0x759632b190
	public Void set_selectedRoom(BRoomSlot value) { }
	// RVA: 0x3d132dc VA: 0x759632b2dc
	private Void OnEnable() { }
	// RVA: 0x3d13320 VA: 0x759632b320
	public Void Init(List`1 layout, BlueprintMode state) { }
	// RVA: 0x3d13a28 VA: 0x759632ba28
	public Void OnEnter() { }
	// RVA: 0x3d13a98 VA: 0x759632ba98
	public Void OnExit() { }
	// RVA: 0x3d13a9c VA: 0x759632ba9c
	public Void OnRoomClicked(BRoomSlot room) { }
	// RVA: 0x3d13c7c VA: 0x759632bc7c
	public virtual Void SetArchitectureActive(Boolean active) { }
	// RVA: 0x3d13dc8 VA: 0x759632bdc8
	public Void FocusSelectedRoomForUI(Action`1 finishCb) { }
	// RVA: 0x3d13dd8 VA: 0x759632bdd8
	public Void FocusRoomForUI(BRoomSlot roomSlot, Action`1 finishCb) { }
	// RVA: 0x3d14310 VA: 0x759632c310
	public Void UpdateRoomHilightStatus(BRoomHilightViewModel viewModel) { }
	// RVA: 0x3d14378 VA: 0x759632c378
	private Void _UpdateHilightStatus(BRoomHilightViewModel viewModel) { }
	// RVA: 0x3d132e0 VA: 0x759632b2e0
	private Void _DealWithPendingHilight() { }
	// RVA: 0x3d13b68 VA: 0x759632bb68
	private Void _OnRoomClickNormal(BRoomSlot slot) { }
	// RVA: 0x3d13bb4 VA: 0x759632bbb4
	private Void _OnRoomClickArchitecture(BRoomSlot room) { }
	// RVA: 0x3d13ed0 VA: 0x759632bed0
	private Void _FocusToRoomBySide(BRoomSlot slot, LeftOrRight side, Action`1 finishCb) { }
	// RVA: 0x3d14864 VA: 0x759632c864
	public Tween ZoomTo(Single toZoom, BRoomSlot roomSlot) { }
	// RVA: 0x3d14658 VA: 0x759632c658
	public Boolean TryGetRoomBySlotId(String slotId, out BRoomSlot value) { }
	// RVA: 0x3d14b20 VA: 0x759632cb20
	public Vector2 get_originPoint() { }
	// RVA: 0x3d136f4 VA: 0x759632b6f4
	private Void _ResetLayout() { }
	// RVA: 0x3d1364c VA: 0x759632b64c
	private BRoomSlot _CreateRoom(RoomSlotModel model) { }
	// RVA: 0x3d13510 VA: 0x759632b510
	private Void _ClearAll() { }
	// RVA: 0x3d13a4c VA: 0x759632ba4c
	private Void _ResetToDefault() { }
	// RVA: 0x3d14798 VA: 0x759632c798
	private Void _SwitchToVault(BRoomSlot room) { }
	// RVA: 0x3d14c28 VA: 0x759632cc28
	private Void _ResetFullBoundGround(RectTransform rectground, Bounds worldBound, Vector2 padding, Single maxZoom) { }
	// RVA: 0x3d15078 VA: 0x759632d078
	private Rect _CalcLocalRectForBound(Bounds bound, RectTransform rect) { }
	// RVA: 0x3d151ac VA: 0x759632d1ac
	public Void NotifySettleEffect(RoomType roomType) { }
	// RVA: 0x3d1537c VA: 0x759632d37c
	public Vector2 GetRoomAnchorBySlotId(String slotId) { }
	// RVA: 0x3d154cc VA: 0x759632d4cc
	public Void .ctor() { }
	// RVA: 0x3d15604 VA: 0x759632d604
	private static Void .cctor() { }
}
```