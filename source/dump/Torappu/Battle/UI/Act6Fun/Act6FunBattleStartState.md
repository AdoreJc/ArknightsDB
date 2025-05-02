# Act6FunBattleStartState

**Namespace:** `Torappu.Battle.UI.Act6Fun`


## Fields

- `AnimationWrapper _animWrapper`

- `String _clipName`


## Methods

- `Void _OnAnimComplete()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableBackpress()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Act6Fun
public class Act6FunBattleStartState : UIStateNode
{
	private AnimationWrapper _animWrapper; // 0x20
	private String _clipName; // 0x28
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0__OnAnimComplete; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableBackpress { get; }

	// RVA: 0x20f50a4 VA: 0x759470d0a4
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20f5138 VA: 0x759470d138
	public override Boolean get_enablePause() { }
	// RVA: 0x20f519c VA: 0x759470d19c
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20f5200 VA: 0x759470d200
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20f5264 VA: 0x759470d264
	public override Boolean get_enableBackpress() { }
	// RVA: 0x20f52c8 VA: 0x759470d2c8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20f54cc VA: 0x759470d4cc
	private Void _OnAnimComplete() { }
	// RVA: 0x20f55ac VA: 0x759470d5ac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20f5624 VA: 0x759470d624
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20f56c0 VA: 0x759470d6c0
	public Void .ctor() { }
	// RVA: 0x20f5730 VA: 0x759470d730
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20f5738 VA: 0x759470d738
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20f5740 VA: 0x759470d740
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20f5748 VA: 0x759470d748
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x20f5750 VA: 0x759470d750
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20f5758 VA: 0x759470d758
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```