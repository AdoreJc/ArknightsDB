# UIBattleStartState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIBattleStartPanel _startPanel`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleStartState : UIStateNode
{
	private UIBattleStartPanel _startPanel; // 0x20
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x2057498 VA: 0x759466f498
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2057500 VA: 0x759466f500
	public override Boolean get_enablePause() { }
	// RVA: 0x2057564 VA: 0x759466f564
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20575c8 VA: 0x759466f5c8
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x205762c VA: 0x759466f62c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20577bc VA: 0x759466f7bc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x2057834 VA: 0x759466f834
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20578d0 VA: 0x759466f8d0
	public Void .ctor() { }
	// RVA: 0x2057940 VA: 0x759466f940
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2057948 VA: 0x759466f948
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x2057950 VA: 0x759466f950
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2057958 VA: 0x759466f958
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2057960 VA: 0x759466f960
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```