# LegionUICardRedrawState

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `LegionUIPlugin m_plugin`

- `LegionGameMode m_manager`

- `UIBattleLegionRedrawPanel m_panel`


## Methods

- `Void _OnCardToggled(Object)`

- `Void OnConfirm()`

- `Void OnUnselect()`

- `Void OnShowPendingCard()`

- `Void OnShowUsedCard()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionUICardRedrawState : CommonUIStateNode
{
	private LegionUIPlugin m_plugin; // 0x50
	private LegionGameMode m_manager; // 0x58
	private List`1 m_selectedCardList; // 0x60
	private UIBattleLegionRedrawPanel m_panel; // 0x68
	private const BattleFunctionDisableMask FUNCTION_MASK; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0__OnCardToggled; // 0x38
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x40
	private static DelegateBridge __Hotfix0_OnUnselect; // 0x48
	private static DelegateBridge __Hotfix0_OnShowPendingCard; // 0x50
	private static DelegateBridge __Hotfix0_OnShowUsedCard; // 0x58
	private static DelegateBridge __Hotfix0_OnTick; // 0x60
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x1dbd85c VA: 0x75943d585c
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1dbd8f0 VA: 0x75943d58f0
	public override Boolean get_enablePause() { }
	// RVA: 0x1dbd954 VA: 0x75943d5954
	public override Boolean get_enableShowRange() { }
	// RVA: 0x1dbd9b8 VA: 0x75943d59b8
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1dbda1c VA: 0x75943d5a1c
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1dbdc48 VA: 0x75943d5c48
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1dbe020 VA: 0x75943d6020
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1dbe24c VA: 0x75943d624c
	private Void _OnCardToggled(Object item) { }
	// RVA: 0x1dbe51c VA: 0x75943d651c
	public Void OnConfirm() { }
	// RVA: 0x1dbe6c8 VA: 0x75943d66c8
	public Void OnUnselect() { }
	// RVA: 0x1dbe7c4 VA: 0x75943d67c4
	public Void OnShowPendingCard() { }
	// RVA: 0x1dbe838 VA: 0x75943d6838
	public Void OnShowUsedCard() { }
	// RVA: 0x1dbe8ac VA: 0x75943d68ac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1dbe924 VA: 0x75943d6924
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x1dbe9f0 VA: 0x75943d69f0
	public Void .ctor() { }
	// RVA: 0x1dbeab4 VA: 0x75943d6ab4
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1dbeabc VA: 0x75943d6abc
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x1dbeac4 VA: 0x75943d6ac4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1dbeacc VA: 0x75943d6acc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1dbead4 VA: 0x75943d6ad4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1dbeadc VA: 0x75943d6adc
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x1dbeae4 VA: 0x75943d6ae4
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```