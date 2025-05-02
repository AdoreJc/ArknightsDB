# DialogSandboxPlugin

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `NpcBattleInput m_currentNpc`

- `StringBuilder m_builder`


## Properties

- `SandboxCameraPlugin cameraPlugin`


## Methods

- `SandboxCameraPlugin get_cameraPlugin()`

- `Boolean _ItemGE(Command)`

- `Boolean _ItemGT(Command)`

- `Boolean _ConditionGE(Command)`

- `Boolean _ConditionGT(Command)`

- `Boolean _AddItem(Command)`

- `Boolean _SetCondition(Command)`

- `Boolean _ExecuteSave(Command)`

- `Boolean _ExecuteHeader(Command)`

- `Boolean _ExecutePredicate(Command)`

- `Boolean _ExecuteFogInView(Command)`

- `Boolean _ExecuteFogNotInView(Command)`

- `Boolean _ExecuteGacha(Command)`

- `Boolean _CheckRift(Command)`

- `Boolean _CheckRiftIDIs(Command)`

- `Boolean _CheckCanOrderRandomRift(Command)`

- `Boolean _OrderRift(Command)`

- `Boolean _CheckFavor(Command)`

- `Boolean _AddFavor(Command)`

- `GameModeType <>xLuaBaseProxy_get_mode()`

- `String <>xLuaBaseProxy_GetBeforeBattleSignal()`

- `String <>xLuaBaseProxy_GetAfterBattleSignal()`

- `Void <>xLuaBaseProxy_OnSignalStart(String, BattleDialogParam)`

- `Void <>xLuaBaseProxy_OnDialogEnd()`

- `Void <>xLuaBaseProxy_OnBeforeBattleWaveEnd()`

- `Void <>xLuaBaseProxy_OnAfterBattleWaveStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogSandboxPlugin : DialogControllerGameModePlugin
{
	private NpcBattleInput m_currentNpc; // 0x18
	private StringBuilder m_builder; // 0x20
	private static DelegateBridge __Hotfix0_get_mode; // 0x0
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x10
	private static DelegateBridge __Hotfix0__ItemGE; // 0x18
	private static DelegateBridge __Hotfix0__ItemGT; // 0x20
	private static DelegateBridge __Hotfix0__ConditionGE; // 0x28
	private static DelegateBridge __Hotfix0__ConditionGT; // 0x30
	private static DelegateBridge __Hotfix0__AddItem; // 0x38
	private static DelegateBridge __Hotfix0__SetCondition; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteSave; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteHeader; // 0x50
	private static DelegateBridge __Hotfix0__ExecutePredicate; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteFogInView; // 0x60
	private static DelegateBridge __Hotfix0__ExecuteFogNotInView; // 0x68
	private static DelegateBridge __Hotfix0__ExecuteGacha; // 0x70
	private static DelegateBridge __Hotfix0__CheckRift; // 0x78
	private static DelegateBridge __Hotfix0__CheckRiftIDIs; // 0x80
	private static DelegateBridge __Hotfix0__CheckCanOrderRandomRift; // 0x88
	private static DelegateBridge __Hotfix0__OrderRift; // 0x90
	private static DelegateBridge __Hotfix0__CheckFavor; // 0x98
	private static DelegateBridge __Hotfix0__AddFavor; // 0xa0
	private static DelegateBridge __Hotfix0_GetBeforeBattleSignal; // 0xa8
	private static DelegateBridge __Hotfix0_GetAfterBattleSignal; // 0xb0
	private static DelegateBridge __Hotfix0_OnSignalStart; // 0xb8
	private static DelegateBridge __Hotfix0_OnDialogEnd; // 0xc0
	private static DelegateBridge __Hotfix0_OnBeforeBattleWaveEnd; // 0xc8
	private static DelegateBridge __Hotfix0_OnAfterBattleWaveStart; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public override GameModeType mode { get; }
	private SandboxCameraPlugin cameraPlugin { get; }

	// RVA: 0x1d27d54 VA: 0x759433fd54
	public override GameModeType get_mode() { }
	// RVA: 0x1d27dbc VA: 0x759433fdbc
	private SandboxCameraPlugin get_cameraPlugin() { }
	// RVA: 0x1d27e94 VA: 0x759433fe94
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x1d285f8 VA: 0x75943405f8
	private Boolean _ItemGE(Command command) { }
	// RVA: 0x1d28734 VA: 0x7594340734
	private Boolean _ItemGT(Command command) { }
	// RVA: 0x1d28870 VA: 0x7594340870
	private Boolean _ConditionGE(Command command) { }
	// RVA: 0x1d289ac VA: 0x75943409ac
	private Boolean _ConditionGT(Command command) { }
	// RVA: 0x1d28ae8 VA: 0x7594340ae8
	private Boolean _AddItem(Command command) { }
	// RVA: 0x1d28c64 VA: 0x7594340c64
	private Boolean _SetCondition(Command command) { }
	// RVA: 0x1d28da4 VA: 0x7594340da4
	private Boolean _ExecuteSave(Command command) { }
	// RVA: 0x1d28ea8 VA: 0x7594340ea8
	private Boolean _ExecuteHeader(Command command) { }
	// RVA: 0x1d29050 VA: 0x7594341050
	private Boolean _ExecutePredicate(Command command) { }
	// RVA: 0x1d29208 VA: 0x7594341208
	private Boolean _ExecuteFogInView(Command command) { }
	// RVA: 0x1d294bc VA: 0x75943414bc
	private Boolean _ExecuteFogNotInView(Command command) { }
	// RVA: 0x1d29694 VA: 0x7594341694
	private Boolean _ExecuteGacha(Command command) { }
	// RVA: 0x1d2995c VA: 0x759434195c
	private Boolean _CheckRift(Command command) { }
	// RVA: 0x1d29a2c VA: 0x7594341a2c
	private Boolean _CheckRiftIDIs(Command command) { }
	// RVA: 0x1d29bac VA: 0x7594341bac
	private Boolean _CheckCanOrderRandomRift(Command command) { }
	// RVA: 0x1d29de8 VA: 0x7594341de8
	private Boolean _OrderRift(Command command) { }
	// RVA: 0x1d29f64 VA: 0x7594341f64
	private Boolean _CheckFavor(Command command) { }
	// RVA: 0x1d2a1f8 VA: 0x75943421f8
	private Boolean _AddFavor(Command command) { }
	// RVA: 0x1d2a404 VA: 0x7594342404
	public override String GetBeforeBattleSignal() { }
	// RVA: 0x1d2a4fc VA: 0x75943424fc
	public override String GetAfterBattleSignal() { }
	// RVA: 0x1d2a5f4 VA: 0x75943425f4
	public override Void OnSignalStart(String signal, BattleDialogParam param) { }
	// RVA: 0x1d2a6dc VA: 0x75943426dc
	public override Void OnDialogEnd() { }
	// RVA: 0x1d2a78c VA: 0x759434278c
	public override Void OnBeforeBattleWaveEnd() { }
	// RVA: 0x1d2a838 VA: 0x7594342838
	public override Void OnAfterBattleWaveStart() { }
	// RVA: 0x1d2accc VA: 0x7594342ccc
	public Void .ctor() { }
	// RVA: 0x1d2ad78 VA: 0x7594342d78
	private GameModeType <>xLuaBaseProxy_get_mode() { }
	// RVA: 0x1d2ad7c VA: 0x7594342d7c
	private Dictionary`2 <>xLuaBaseProxy_GetExecutors() { }
	// RVA: 0x1d2ad80 VA: 0x7594342d80
	private String <>xLuaBaseProxy_GetBeforeBattleSignal() { }
	// RVA: 0x1d2ad84 VA: 0x7594342d84
	private String <>xLuaBaseProxy_GetAfterBattleSignal() { }
	// RVA: 0x1d2ad88 VA: 0x7594342d88
	private Void <>xLuaBaseProxy_OnSignalStart(String P0, BattleDialogParam P1) { }
	// RVA: 0x1d2ad90 VA: 0x7594342d90
	private Void <>xLuaBaseProxy_OnDialogEnd() { }
	// RVA: 0x1d2ad94 VA: 0x7594342d94
	private Void <>xLuaBaseProxy_OnBeforeBattleWaveEnd() { }
	// RVA: 0x1d2ad98 VA: 0x7594342d98
	private Void <>xLuaBaseProxy_OnAfterBattleWaveStart() { }
}
```