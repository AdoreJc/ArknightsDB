# UIDialogueState

**Namespace:** `Torappu.Battle`


## Fields

- `GameObject _dialogueGroup`

- `DialogPanel _dialogPanel`

- `BattleDialogParam m_stateParam`

- `SpeedLevel m_cachedSpeedLevel`

- `Int32 m_cachedMaxCostOffset`

- `DialogPanel m_dialogPanel`


## Properties

- `DialogPanel panel`


## Methods

- `DialogPanel get_panel()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableBackpress()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UIDialogueState : UIStateNode
{
	private GameObject _dialogueGroup; // 0x20
	private DialogPanel _dialogPanel; // 0x28
	private BattleDialogParam m_stateParam; // 0x30
	private SpeedLevel m_cachedSpeedLevel; // 0x34
	private Int32 m_cachedMaxCostOffset; // 0x38
	private DialogPanel m_dialogPanel; // 0x40
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x0
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x8
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x10
	private static DelegateBridge __Hotfix0_get_panel; // 0x18
	private static DelegateBridge __Hotfix0_get_uiState; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Boolean enablePause { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableBackpress { get; }
	public DialogPanel panel { get; }
	public override UIStateEnum uiState { get; }

	// RVA: 0x1c468bc VA: 0x759425e8bc
	public override Boolean get_enablePause() { }
	// RVA: 0x1c46920 VA: 0x759425e920
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x1c46984 VA: 0x759425e984
	public override Boolean get_enableBackpress() { }
	// RVA: 0x1c469e8 VA: 0x759425e9e8
	public DialogPanel get_panel() { }
	// RVA: 0x1c46a50 VA: 0x759425ea50
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1c46ab8 VA: 0x759425eab8
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1c46e2c VA: 0x759425ee2c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c47060 VA: 0x759425f060
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c470d8 VA: 0x759425f0d8
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1c47284 VA: 0x759425f284
	public Void .ctor() { }
	// RVA: 0x1c472f4 VA: 0x759425f2f4
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x1c472fc VA: 0x759425f2fc
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x1c47304 VA: 0x759425f304
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x1c4730c VA: 0x759425f30c
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1c47314 VA: 0x759425f314
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1c4731c VA: 0x759425f31c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```