# FunLiveUISystemMenuState

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `FunLiveUIPlugin m_plugin`

- `FunLiveUIBattleMenuSystemPanel m_panel`


## Methods

- `Void CloseSystemMenuPanel()`

- `Void FinishGameDirectly()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUISystemMenuState : CommonUIStateNode
{
	private FunLiveUIPlugin m_plugin; // 0x50
	private FunLiveUIBattleMenuSystemPanel m_panel; // 0x58
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x28
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override UIStateEnum uiState { get; }

	// RVA: 0x1c5ddfc VA: 0x7594275dfc
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1c5de90 VA: 0x7594275e90
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c5df08 VA: 0x7594275f08
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1c5e040 VA: 0x7594276040
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c5e214 VA: 0x7594276214
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1c5acf0 VA: 0x7594272cf0
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c5add0 VA: 0x7594272dd0
	public Void FinishGameDirectly() { }
	// RVA: 0x1c5e460 VA: 0x7594276460
	public Void .ctor() { }
	// RVA: 0x1c5e4d0 VA: 0x75942764d0
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1c5e4d8 VA: 0x75942764d8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1c5e4e0 VA: 0x75942764e0
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```