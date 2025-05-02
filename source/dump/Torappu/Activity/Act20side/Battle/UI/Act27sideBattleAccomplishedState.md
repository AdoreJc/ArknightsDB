# Act27sideBattleAccomplishedState

**Namespace:** `Torappu.Activity.Act20side.Battle.UI`


## Fields

- `Transform _battleAccomplishedPanel`


## Methods

- `Void OnClick()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side.Battle.UI
public class Act27sideBattleAccomplishedState : UIStateNode
{
	private Transform _battleAccomplishedPanel; // 0x20
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x33081e8 VA: 0x75959201e8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x330827c VA: 0x759592027c
	public override Boolean get_enablePause() { }
	// RVA: 0x33082e0 VA: 0x75959202e0
	public override Boolean get_enableShowRange() { }
	// RVA: 0x3308344 VA: 0x7595920344
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x33083a8 VA: 0x75959203a8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3308478 VA: 0x7595920478
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x33084f0 VA: 0x75959204f0
	public Void OnClick() { }
	// RVA: 0x3308580 VA: 0x7595920580
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x3308600 VA: 0x7595920600
	public Void .ctor() { }
	// RVA: 0x3308670 VA: 0x7595920670
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x3308678 VA: 0x7595920678
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x3308680 VA: 0x7595920680
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x3308688 VA: 0x7595920688
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3308690 VA: 0x7595920690
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```