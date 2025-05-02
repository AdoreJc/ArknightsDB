# RacingStartCountdownState

**Namespace:** `Torappu.Battle.UI.Racing`


## Fields

- `UIAnimationLocation _startAnim`

- `GameObject _battleTransitionHolder`

- `Image _battleTransitionBgImage`

- `RacingUIPlugin m_plugin`


## Methods

- `Void <OnEnter>b__15_0()`

- `Void <OnEnter>b__15_1()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Racing
public class RacingStartCountdownState : UIStateNode
{
	private const Single IMAGE_FADE_TIME; // 0x0
	private const Single IMAGE_FADE_DELAY_TIME; // 0x0
	private UIAnimationLocation _startAnim; // 0x20
	private GameObject _battleTransitionHolder; // 0x30
	private Image _battleTransitionBgImage; // 0x38
	private RacingUIPlugin m_plugin; // 0x40
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x20f13f4 VA: 0x75947093f4
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20f1488 VA: 0x7594709488
	public override Boolean get_enablePause() { }
	// RVA: 0x20f14ec VA: 0x75947094ec
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20f1550 VA: 0x7594709550
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x20f15b4 VA: 0x75947095b4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20f162c VA: 0x759470962c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20f19a0 VA: 0x75947099a0
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x20f1a20 VA: 0x7594709a20
	public Void .ctor() { }
	// RVA: 0x20f1a90 VA: 0x7594709a90
	private Void <OnEnter>b__15_0() { }
	// RVA: 0x20f1ab8 VA: 0x7594709ab8
	private Void <OnEnter>b__15_1() { }
	// RVA: 0x20f1cd4 VA: 0x7594709cd4
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x20f1cdc VA: 0x7594709cdc
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20f1ce4 VA: 0x7594709ce4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20f1cec VA: 0x7594709cec
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20f1cf4 VA: 0x7594709cf4
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```