# GameCityShowInfoState

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `GameCityInfoShowPanel _perform`


## Methods

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityShowInfoState : UIStateNode
{
	private const String SHOW_INFO_ANIMATION; // 0x0
	private GameCityInfoShowPanel _perform; // 0x20
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x33e7910 VA: 0x75959ff910
	public override UIStateEnum get_uiState() { }
	// RVA: 0x33e79a4 VA: 0x75959ff9a4
	public override Boolean get_enablePause() { }
	// RVA: 0x33e7a08 VA: 0x75959ffa08
	public override Boolean get_enableShowRange() { }
	// RVA: 0x33e7a6c VA: 0x75959ffa6c
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x33e7ad0 VA: 0x75959ffad0
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x33e7b38 VA: 0x75959ffb38
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x33e82e8 VA: 0x7595a002e8
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x33e83ac VA: 0x7595a003ac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x33e8424 VA: 0x7595a00424
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x33e84a4 VA: 0x7595a004a4
	public Void .ctor() { }
	// RVA: 0x33e8514 VA: 0x7595a00514
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x33e851c VA: 0x7595a0051c
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x33e8524 VA: 0x7595a00524
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x33e852c VA: 0x7595a0052c
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x33e8534 VA: 0x7595a00534
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x33e853c VA: 0x7595a0053c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x33e8544 VA: 0x7595a00544
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```