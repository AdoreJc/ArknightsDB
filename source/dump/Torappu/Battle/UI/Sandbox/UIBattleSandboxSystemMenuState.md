# UIBattleSandboxSystemMenuState

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Boolean m_isFromFailState`


## Properties

- `UICharacterInfoPanel characterInfo`

- `SandboxGameMode gamemode`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `SandboxGameMode get_gamemode()`

- `Void OnCancel(Object)`

- `Void OnConfirmFinish(Object)`

- `Void _SwitchToFailedState(Boolean)`

- `Void _DoShowPanel()`

- `Void <OnConfirmFinish>b__8_0()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxSystemMenuState : UIBattleSandboxStateNode
{
	private Boolean m_isFromFailState; // 0x29
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_gamemode; // 0x10
	private static DelegateBridge __Hotfix0_OnCancel; // 0x18
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0__SwitchToFailedState; // 0x30
	private static DelegateBridge __Hotfix0__DoShowPanel; // 0x38
	private static DelegateBridge __Hotfix0_OnEnter; // 0x40
	private static DelegateBridge __Hotfix0_OnExit; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	private SandboxGameMode gamemode { get; }

	// RVA: 0x20be96c VA: 0x75946d696c
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x20be9f8 VA: 0x75946d69f8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20bea8c VA: 0x75946d6a8c
	private SandboxGameMode get_gamemode() { }
	// RVA: 0x20beb18 VA: 0x75946d6b18
	public Void OnCancel(Object obj) { }
	// RVA: 0x20bebd8 VA: 0x75946d6bd8
	public Void OnConfirmFinish(Object obj) { }
	// RVA: 0x20bed8c VA: 0x75946d6d8c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20bee04 VA: 0x75946d6e04
	private Void _SwitchToFailedState(Boolean isGiveUp) { }
	// RVA: 0x20beea8 VA: 0x75946d6ea8
	private Void _DoShowPanel() { }
	// RVA: 0x20befb4 VA: 0x75946d6fb4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20bf148 VA: 0x75946d7148
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20bf28c VA: 0x75946d728c
	public Void .ctor() { }
	// RVA: 0x20bf300 VA: 0x75946d7300
	private Void <OnConfirmFinish>b__8_0() { }
	// RVA: 0x20bf308 VA: 0x75946d7308
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x20bf30c VA: 0x75946d730c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20bf314 VA: 0x75946d7314
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```