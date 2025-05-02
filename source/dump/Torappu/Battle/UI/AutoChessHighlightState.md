# AutoChessHighlightState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _focusRatio`

- `Single _focusRatioHandTile`

- `AutoChessGameMode m_gameMode`

- `AutoChessCameraPlugin m_cameraPlugin`

- `AutoChessUIPlugin m_uiPlugin`

- `Tile m_tile`


## Properties

- `AutoChessGameMode gameMode`

- `AutoChessCameraPlugin cameraPlugin`

- `AutoChessUIPlugin uiPlugin`

- `Boolean isGameModeStateValid`


## Methods

- `AutoChessGameMode get_gameMode()`

- `AutoChessCameraPlugin get_cameraPlugin()`

- `AutoChessUIPlugin get_uiPlugin()`

- `Boolean get_isGameModeStateValid()`

- `Single _GetFocusRatio(Tile)`

- `Void _SetCameraOriginPos()`

- `Void _OnButtomMaskBeginDrag(Object)`

- `Void _OnTileClicked(Object)`

- `Void _OnBottomMaskClicked(Object)`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessHighlightState : UIStateNode
{
	private Single _focusRatio; // 0x20
	private Single _focusRatioHandTile; // 0x24
	private AutoChessGameMode m_gameMode; // 0x28
	private AutoChessCameraPlugin m_cameraPlugin; // 0x30
	private AutoChessUIPlugin m_uiPlugin; // 0x38
	private ObjectPtr`1 m_character; // 0x40
	private Tile m_tile; // 0x50
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x8
	private static DelegateBridge __Hotfix0_get_uiPlugin; // 0x10
	private static DelegateBridge __Hotfix0_get_uiState; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_get_isGameModeStateValid; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0__GetFocusRatio; // 0x58
	private static DelegateBridge __Hotfix0__SetCameraOriginPos; // 0x60
	private static DelegateBridge __Hotfix0__OnButtomMaskBeginDrag; // 0x68
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnBottomMaskClicked; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private AutoChessGameMode gameMode { get; }
	private AutoChessCameraPlugin cameraPlugin { get; }
	private AutoChessUIPlugin uiPlugin { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enablePerspectiveCanvas { get; }
	private Boolean isGameModeStateValid { get; }

	// RVA: 0x20259c4 VA: 0x759463d9c4
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x2025a74 VA: 0x759463da74
	private AutoChessCameraPlugin get_cameraPlugin() { }
	// RVA: 0x2025bd4 VA: 0x759463dbd4
	private AutoChessUIPlugin get_uiPlugin() { }
	// RVA: 0x2025d34 VA: 0x759463dd34
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2025d9c VA: 0x759463dd9c
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x2025e04 VA: 0x759463de04
	private Boolean get_isGameModeStateValid() { }
	// RVA: 0x2025eb8 VA: 0x759463deb8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x20260cc VA: 0x759463e0cc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x202620c VA: 0x759463e20c
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20262ac VA: 0x759463e2ac
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20266cc VA: 0x759463e6cc
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x2026614 VA: 0x759463e614
	private Single _GetFocusRatio(Tile tile) { }
	// RVA: 0x20268d0 VA: 0x759463e8d0
	private Void _SetCameraOriginPos() { }
	// RVA: 0x2026968 VA: 0x759463e968
	private Void _OnButtomMaskBeginDrag(Object arg) { }
	// RVA: 0x2026b10 VA: 0x759463eb10
	private Void _OnTileClicked(Object arg) { }
	// RVA: 0x2026e34 VA: 0x759463ee34
	private Void _OnBottomMaskClicked(Object arg) { }
	// RVA: 0x2026ffc VA: 0x759463effc
	public Void .ctor() { }
	// RVA: 0x2027078 VA: 0x759463f078
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x2027080 VA: 0x759463f080
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x2027088 VA: 0x759463f088
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
	// RVA: 0x2027090 VA: 0x759463f090
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2027098 VA: 0x759463f098
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```