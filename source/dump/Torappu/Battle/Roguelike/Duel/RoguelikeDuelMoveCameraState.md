# RoguelikeDuelMoveCameraState

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelMoveCameraState : UIStateNode
{
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnExit; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x1d4d928 VA: 0x7594365928
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1d4d9bc VA: 0x75943659bc
	public override Boolean get_enablePause() { }
	// RVA: 0x1d4da20 VA: 0x7594365a20
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1d4da84 VA: 0x7594365a84
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1d4dae8 VA: 0x7594365ae8
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x1d4db50 VA: 0x7594365b50
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d4dbc8 VA: 0x7594365bc8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1d4dd08 VA: 0x7594365d08
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1d4ddc0 VA: 0x7594365dc0
	public Void .ctor() { }
	// RVA: 0x1d4de30 VA: 0x7594365e30
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1d4de38 VA: 0x7594365e38
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1d4de40 VA: 0x7594365e40
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1d4de48 VA: 0x7594365e48
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x1d4de50 VA: 0x7594365e50
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1d4de58 VA: 0x7594365e58
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```