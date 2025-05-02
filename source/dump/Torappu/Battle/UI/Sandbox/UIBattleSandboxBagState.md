# UIBattleSandboxBagState

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIBattleSandboxBagPanel _bagPanelPrefab`

- `FadeSwitchTween m_fadeTween`

- `CanvasGroup m_canvasGroup`

- `UIBattleSandboxBagPanel m_bagPanel`

- `SandboxUIPlugin m_plugin`


## Properties

- `UIBattleSandboxBagPanel bagPanel`

- `FadeSwitchTween fadeTween`


## Methods

- `UIBattleSandboxBagPanel get_bagPanel()`

- `FadeSwitchTween get_fadeTween()`

- `Void _InitCanvasGroup()`

- `Void ShowBag()`

- `Void CloseBagPanel()`

- `Void <get_fadeTween>b__16_0()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxBagState : UIBattleSandboxStateNode
{
	private UIBattleSandboxBagPanel _bagPanelPrefab; // 0x30
	private FadeSwitchTween m_fadeTween; // 0x38
	private CanvasGroup m_canvasGroup; // 0x40
	private UIBattleSandboxBagPanel m_bagPanel; // 0x48
	private SandboxUIPlugin m_plugin; // 0x50
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x0
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x8
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x10
	private static DelegateBridge __Hotfix0_get_uiState; // 0x18
	private static DelegateBridge __Hotfix0_get_bagPanel; // 0x20
	private static DelegateBridge __Hotfix0_get_fadeTween; // 0x28
	private static DelegateBridge __Hotfix0__InitCanvasGroup; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_ShowBag; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0_CloseBagPanel; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override UIStateEnum uiState { get; }
	public UIBattleSandboxBagPanel bagPanel { get; }
	protected FadeSwitchTween fadeTween { get; }

	// RVA: 0x209e358 VA: 0x75946b6358
	public override Boolean get_enablePause() { }
	// RVA: 0x209e3bc VA: 0x75946b63bc
	public override Boolean get_enableShowRange() { }
	// RVA: 0x209e420 VA: 0x75946b6420
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x209e484 VA: 0x75946b6484
	public override UIStateEnum get_uiState() { }
	// RVA: 0x209e518 VA: 0x75946b6518
	public UIBattleSandboxBagPanel get_bagPanel() { }
	// RVA: 0x209e580 VA: 0x75946b6580
	protected FadeSwitchTween get_fadeTween() { }
	// RVA: 0x209e750 VA: 0x75946b6750
	private Void _InitCanvasGroup() { }
	// RVA: 0x209e818 VA: 0x75946b6818
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x209e9ec VA: 0x75946b69ec
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x209ea9c VA: 0x75946b6a9c
	public Void ShowBag() { }
	// RVA: 0x209ec98 VA: 0x75946b6c98
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x209ed74 VA: 0x75946b6d74
	public Void CloseBagPanel() { }
	// RVA: 0x209ee90 VA: 0x75946b6e90
	public Void .ctor() { }
	// RVA: 0x209ef00 VA: 0x75946b6f00
	private Void <get_fadeTween>b__16_0() { }
	// RVA: 0x209ef90 VA: 0x75946b6f90
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x209ef98 VA: 0x75946b6f98
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x209efa0 VA: 0x75946b6fa0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x209efa8 VA: 0x75946b6fa8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x209efb0 VA: 0x75946b6fb0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x209efb8 VA: 0x75946b6fb8
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```