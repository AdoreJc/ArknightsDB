# UICooperatePinMarkState

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateBattlePinMarkMenu _pinMarkMenu`

- `Single _tileLocateRadius`

- `Vector2 _touchOffset`

- `State m_state`

- `Transform m_dummy`

- `Transform m_dragPlane`

- `Tile m_currentTile`

- `UICooperateBattlePinMarkMenu m_pinMarkMenu`

- `UICooperatePinMarkCard m_pinMarkCard`


## Methods

- `Void _OnBeginDrag(Object)`

- `Void _OnEndDrag(Object)`

- `Void _ClearDummy()`

- `Boolean _TryGetScreenPos(out)`

- `Vector2 _ConvertScreenPos(Vector2)`

- `Boolean _CheckLocatable(Tile, Vector2)`

- `Void _MoveToMatch(Tile)`

- `Void _UpdateInternal()`

- `Void _PutDownInternal(Tile)`

- `Boolean _TileOutOfScreen()`

- `Boolean _PointInScreen(RectTransform, Vector2)`

- `Void _OnBottomMaskClicked(Object)`

- `Void _SendPinMark(PinType, Tile)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperatePinMarkState : UIStateNode
{
	private UICooperateBattlePinMarkMenu _pinMarkMenu; // 0x20
	private Single _tileLocateRadius; // 0x28
	private Vector2 _touchOffset; // 0x2c
	private State m_state; // 0x34
	private Transform m_dummy; // 0x38
	private Transform m_dragPlane; // 0x40
	private Tile m_currentTile; // 0x48
	private UICooperateBattlePinMarkMenu m_pinMarkMenu; // 0x50
	private UICooperatePinMarkCard m_pinMarkCard; // 0x58
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x10
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x28
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0__ClearDummy; // 0x58
	private static DelegateBridge __Hotfix0__TryGetScreenPos; // 0x60
	private static DelegateBridge __Hotfix0__ConvertScreenPos; // 0x68
	private static DelegateBridge __Hotfix0__CheckLocatable; // 0x70
	private static DelegateBridge __Hotfix0__MoveToMatch; // 0x78
	private static DelegateBridge __Hotfix0__UpdateInternal; // 0x80
	private static DelegateBridge __Hotfix0__PutDownInternal; // 0x88
	private static DelegateBridge __Hotfix0__TileOutOfScreen; // 0x90
	private static DelegateBridge __Hotfix0__PointInScreen; // 0x98
	private static DelegateBridge __Hotfix0__OnBottomMaskClicked; // 0xa0
	private static DelegateBridge __Hotfix0__SendPinMark; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20dc508 VA: 0x75946f4508
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20dc59c VA: 0x75946f459c
	public override Boolean get_enablePause() { }
	// RVA: 0x20dc600 VA: 0x75946f4600
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20dc664 VA: 0x75946f4664
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20dc6c8 VA: 0x75946f46c8
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x20dc730 VA: 0x75946f4730
	private Void _OnBeginDrag(Object arg) { }
	// RVA: 0x20dc8d8 VA: 0x75946f48d8
	private Void _OnEndDrag(Object arg) { }
	// RVA: 0x20dcecc VA: 0x75946f4ecc
	public override Void OnInit(UIStateEnum uiState, UIStateMachine stateMachine) { }
	// RVA: 0x20dd280 VA: 0x75946f5280
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20dd6b8 VA: 0x75946f56b8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20dd79c VA: 0x75946f579c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20dd950 VA: 0x75946f5950
	private Void _ClearDummy() { }
	// RVA: 0x20dda58 VA: 0x75946f5a58
	private Boolean _TryGetScreenPos(out Vector2 screenPos) { }
	// RVA: 0x20ddbb4 VA: 0x75946f5bb4
	private Vector2 _ConvertScreenPos(Vector2 screenPos) { }
	// RVA: 0x20ddc64 VA: 0x75946f5c64
	private Boolean _CheckLocatable(Tile tile, Vector2 mapPos) { }
	// RVA: 0x20ddd30 VA: 0x75946f5d30
	private Void _MoveToMatch(Tile tile) { }
	// RVA: 0x20dd48c VA: 0x75946f548c
	private Void _UpdateInternal() { }
	// RVA: 0x20dcc58 VA: 0x75946f4c58
	private Void _PutDownInternal(Tile tile) { }
	// RVA: 0x20dca3c VA: 0x75946f4a3c
	private Boolean _TileOutOfScreen() { }
	// RVA: 0x20de1f8 VA: 0x75946f61f8
	private Boolean _PointInScreen(RectTransform screen, Vector2 localPos) { }
	// RVA: 0x20de2c0 VA: 0x75946f62c0
	private Void _OnBottomMaskClicked(Object arg) { }
	// RVA: 0x20ddf34 VA: 0x75946f5f34
	private Void _SendPinMark(PinType type, Tile tile) { }
	// RVA: 0x20de394 VA: 0x75946f6394
	public Void .ctor() { }
	// RVA: 0x20de448 VA: 0x75946f6448
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20de450 VA: 0x75946f6450
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20de458 VA: 0x75946f6458
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20de460 VA: 0x75946f6460
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20de468 VA: 0x75946f6468
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20de470 VA: 0x75946f6470
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20de478 VA: 0x75946f6478
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```