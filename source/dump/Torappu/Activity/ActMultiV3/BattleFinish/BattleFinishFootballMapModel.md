# BattleFinishFootballMapModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `Boolean <isNewGoal>k__BackingField`

- `Int32 <goalMine>k__BackingField`

- `Int32 <goalOther>k__BackingField`


## Properties

- `Boolean isNewGoal`

- `Int32 goalMine`

- `Int32 goalOther`

- `Int32 goalDiff`


## Methods

- `Boolean get_isNewGoal()`

- `Void set_isNewGoal(Boolean)`

- `Int32 get_goalMine()`

- `Void set_goalMine(Int32)`

- `Int32 get_goalOther()`

- `Void set_goalOther(Int32)`

- `Int32 get_goalDiff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class BattleFinishFootballMapModel : ActMultiV3BattleFinishMapModel
{
	private Boolean <isNewGoal>k__BackingField; // 0x10
	private Int32 <goalMine>k__BackingField; // 0x14
	private Int32 <goalOther>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_isNewGoal; // 0x0
	private static DelegateBridge __Hotfix0_set_isNewGoal; // 0x8
	private static DelegateBridge __Hotfix0_get_goalMine; // 0x10
	private static DelegateBridge __Hotfix0_set_goalMine; // 0x18
	private static DelegateBridge __Hotfix0_get_goalOther; // 0x20
	private static DelegateBridge __Hotfix0_set_goalOther; // 0x28
	private static DelegateBridge __Hotfix0_get_goalDiff; // 0x30
	private static DelegateBridge __Hotfix0_get_modeType; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean isNewGoal { get; set; }
	public Int32 goalMine { get; set; }
	public Int32 goalOther { get; set; }
	public Int32 goalDiff { get; }
	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x317dca0 VA: 0x7595795ca0
	public Boolean get_isNewGoal() { }
	// RVA: 0x318aa5c VA: 0x75957a2a5c
	private Void set_isNewGoal(Boolean value) { }
	// RVA: 0x317db30 VA: 0x7595795b30
	public Int32 get_goalMine() { }
	// RVA: 0x318aadc VA: 0x75957a2adc
	private Void set_goalMine(Int32 value) { }
	// RVA: 0x317db98 VA: 0x7595795b98
	public Int32 get_goalOther() { }
	// RVA: 0x318ab58 VA: 0x75957a2b58
	private Void set_goalOther(Int32 value) { }
	// RVA: 0x317dc00 VA: 0x7595795c00
	public Int32 get_goalDiff() { }
	// RVA: 0x318abd4 VA: 0x75957a2bd4
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x318ac3c VA: 0x75957a2c3c
	public override Void LoadData(Input input) { }
	// RVA: 0x3189d5c VA: 0x75957a1d5c
	public Void .ctor() { }
}
```