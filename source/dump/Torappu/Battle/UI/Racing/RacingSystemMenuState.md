# RacingSystemMenuState

**Namespace:** `Torappu.Battle.UI.Racing`


## Fields

- `UIStateEnum m_lastState`


## Properties

- `UICharacterInfoPanel characterInfo`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `Void _DoShowPanel()`

- `Void OnCancel(Object)`

- `Void OnConfirmFinish(Object)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Racing
public class RacingSystemMenuState : UIStateNode
{
	private UIStateEnum m_lastState; // 0x20
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0__DoShowPanel; // 0x28
	private static DelegateBridge __Hotfix0_OnCancel; // 0x30
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }

	// RVA: 0x20f1cfc VA: 0x7594709cfc
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x20f1d88 VA: 0x7594709d88
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20f1e1c VA: 0x7594709e1c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20f2058 VA: 0x759470a058
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x20f2160 VA: 0x759470a160
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20f1f4c VA: 0x7594709f4c
	private Void _DoShowPanel() { }
	// RVA: 0x20f21d8 VA: 0x759470a1d8
	public Void OnCancel(Object obj) { }
	// RVA: 0x20f2304 VA: 0x759470a304
	public Void OnConfirmFinish(Object obj) { }
	// RVA: 0x20f23cc VA: 0x759470a3cc
	public Void .ctor() { }
	// RVA: 0x20f243c VA: 0x759470a43c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20f2444 VA: 0x759470a444
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```