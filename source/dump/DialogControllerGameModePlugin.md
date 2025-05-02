# DialogControllerGameModePlugin

**Namespace:** ` `


## Fields

- `BattleDialogParam <param>k__BackingField`


## Properties

- `BattleDialogParam param`

- `String currentSignal`


## Methods

- `BattleDialogParam get_param()`

- `Void set_param(BattleDialogParam)`

- `String get_currentSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DialogControllerGameModePlugin : IHotfixable
{
	private BattleDialogParam <param>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_mode; // 0x0
	private static DelegateBridge __Hotfix0_get_param; // 0x8
	private static DelegateBridge __Hotfix0_set_param; // 0x10
	private static DelegateBridge __Hotfix0_get_currentSignal; // 0x18
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x20
	private static DelegateBridge __Hotfix0_OnSignalStart; // 0x28
	private static DelegateBridge __Hotfix0_OnDialogEnd; // 0x30
	private static DelegateBridge __Hotfix0_GetBeforeBattleSignal; // 0x38
	private static DelegateBridge __Hotfix0_GetAfterBattleSignal; // 0x40
	private static DelegateBridge __Hotfix0_OnBeforeBattleWaveEnd; // 0x48
	private static DelegateBridge __Hotfix0_OnAfterBattleWaveStart; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public virtual GameModeType mode { get; }
	protected BattleDialogParam param { get; set; }
	protected String currentSignal { get; }

	// RVA: 0x1d1ecbc VA: 0x7594336cbc
	public virtual GameModeType get_mode() { }
	// RVA: 0x1d1ed20 VA: 0x7594336d20
	protected BattleDialogParam get_param() { }
	// RVA: 0x1d1ed88 VA: 0x7594336d88
	private Void set_param(BattleDialogParam value) { }
	// RVA: 0x1d1ee04 VA: 0x7594336e04
	protected String get_currentSignal() { }
	// RVA: 0x1d1ee9c VA: 0x7594336e9c
	public virtual Dictionary`2 GetExecutors() { }
	// RVA: 0x1d1ef00 VA: 0x7594336f00
	public virtual Void OnSignalStart(String signal, BattleDialogParam param) { }
	// RVA: 0x1d1ef88 VA: 0x7594336f88
	public virtual Void OnDialogEnd() { }
	// RVA: 0x1d1efec VA: 0x7594336fec
	public virtual String GetBeforeBattleSignal() { }
	// RVA: 0x1d1f070 VA: 0x7594337070
	public virtual String GetAfterBattleSignal() { }
	// RVA: 0x1d1f0f4 VA: 0x75943370f4
	public virtual Void OnBeforeBattleWaveEnd() { }
	// RVA: 0x1d1f158 VA: 0x7594337158
	public virtual Void OnAfterBattleWaveStart() { }
	// RVA: 0x1d1f1bc VA: 0x75943371bc
	public Void .ctor() { }
}
```