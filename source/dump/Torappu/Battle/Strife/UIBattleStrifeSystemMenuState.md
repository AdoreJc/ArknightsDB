# UIBattleStrifeSystemMenuState

**Namespace:** `Torappu.Battle.Strife`


## Fields

- `Transform _parent`

- `GameObject _statePanel`

- `StrifeUIPlugin m_plugin`

- `UIBattleStrifeMenuSystemPanel m_panel`


## Methods

- `Void CloseSystemMenuPanel()`

- `Void FinishGameDirectly()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Strife
public class UIBattleStrifeSystemMenuState : UIStateNode
{
	private Transform _parent; // 0x20
	private GameObject _statePanel; // 0x28
	private StrifeUIPlugin m_plugin; // 0x30
	private UIBattleStrifeMenuSystemPanel m_panel; // 0x38
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x28
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override UIStateEnum uiState { get; }

	// RVA: 0x1c58fec VA: 0x7594270fec
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1c59080 VA: 0x7594271080
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c590f8 VA: 0x75942710f8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1c592ac VA: 0x75942712ac
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c5959c VA: 0x759427159c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1c58e2c VA: 0x7594270e2c
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c58f0c VA: 0x7594270f0c
	public Void FinishGameDirectly() { }
	// RVA: 0x1c59848 VA: 0x7594271848
	public Void .ctor() { }
	// RVA: 0x1c598b8 VA: 0x75942718b8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1c598c0 VA: 0x75942718c0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1c598c8 VA: 0x75942718c8
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```