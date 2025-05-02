# BattleFinishDefenceMapModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `String <desc>k__BackingField`

- `Int32 <damage>k__BackingField`

- `Single <bossHealthRatio>k__BackingField`

- `Boolean <isBossKilled>k__BackingField`

- `Boolean <isNewStar>k__BackingField`

- `Boolean <isNewDamage>k__BackingField`


## Properties

- `String desc`

- `Int32 damage`

- `Single bossHealthRatio`

- `Boolean isBossKilled`

- `Boolean isNewStar`

- `Boolean isNewDamage`


## Methods

- `String get_desc()`

- `Void set_desc(String)`

- `Int32 get_damage()`

- `Void set_damage(Int32)`

- `Single get_bossHealthRatio()`

- `Void set_bossHealthRatio(Single)`

- `Boolean get_isBossKilled()`

- `Void set_isBossKilled(Boolean)`

- `Boolean get_isNewStar()`

- `Void set_isNewStar(Boolean)`

- `Boolean get_isNewDamage()`

- `Void set_isNewDamage(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class BattleFinishDefenceMapModel : ActMultiV3BattleFinishMapModel
{
	private List`1 m_targetList; // 0x10
	private String <desc>k__BackingField; // 0x18
	private Int32 <damage>k__BackingField; // 0x20
	private Single <bossHealthRatio>k__BackingField; // 0x24
	private Boolean <isBossKilled>k__BackingField; // 0x28
	private Boolean <isNewStar>k__BackingField; // 0x29
	private Boolean <isNewDamage>k__BackingField; // 0x2a
	private static DelegateBridge __Hotfix0_get_desc; // 0x0
	private static DelegateBridge __Hotfix0_set_desc; // 0x8
	private static DelegateBridge __Hotfix0_get_damage; // 0x10
	private static DelegateBridge __Hotfix0_set_damage; // 0x18
	private static DelegateBridge __Hotfix0_get_bossHealthRatio; // 0x20
	private static DelegateBridge __Hotfix0_set_bossHealthRatio; // 0x28
	private static DelegateBridge __Hotfix0_get_isBossKilled; // 0x30
	private static DelegateBridge __Hotfix0_set_isBossKilled; // 0x38
	private static DelegateBridge __Hotfix0_get_isNewStar; // 0x40
	private static DelegateBridge __Hotfix0_set_isNewStar; // 0x48
	private static DelegateBridge __Hotfix0_get_isNewDamage; // 0x50
	private static DelegateBridge __Hotfix0_set_isNewDamage; // 0x58
	private static DelegateBridge __Hotfix0_get_targetList; // 0x60
	private static DelegateBridge __Hotfix0_get_modeType; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String desc { get; set; }
	public Int32 damage { get; set; }
	public Single bossHealthRatio { get; set; }
	public Boolean isBossKilled { get; set; }
	public Boolean isNewStar { get; set; }
	public Boolean isNewDamage { get; set; }
	public List`1 targetList { get; }
	public override ActMultiV3MapModeType modeType { get; }

	// RVA: 0x318acf8 VA: 0x75957a2cf8
	public String get_desc() { }
	// RVA: 0x318ad60 VA: 0x75957a2d60
	private Void set_desc(String value) { }
	// RVA: 0x317d658 VA: 0x7595795658
	public Int32 get_damage() { }
	// RVA: 0x318ade4 VA: 0x75957a2de4
	private Void set_damage(Int32 value) { }
	// RVA: 0x318ae60 VA: 0x75957a2e60
	public Single get_bossHealthRatio() { }
	// RVA: 0x318aec8 VA: 0x75957a2ec8
	private Void set_bossHealthRatio(Single value) { }
	// RVA: 0x318af44 VA: 0x75957a2f44
	public Boolean get_isBossKilled() { }
	// RVA: 0x318afac VA: 0x75957a2fac
	private Void set_isBossKilled(Boolean value) { }
	// RVA: 0x318b02c VA: 0x75957a302c
	public Boolean get_isNewStar() { }
	// RVA: 0x318b094 VA: 0x75957a3094
	private Void set_isNewStar(Boolean value) { }
	// RVA: 0x318b114 VA: 0x75957a3114
	public Boolean get_isNewDamage() { }
	// RVA: 0x318b17c VA: 0x75957a317c
	private Void set_isNewDamage(Boolean value) { }
	// RVA: 0x318b1fc VA: 0x75957a31fc
	public List`1 get_targetList() { }
	// RVA: 0x318b264 VA: 0x75957a3264
	public override ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x318b2cc VA: 0x75957a32cc
	public override Void LoadData(Input input) { }
	// RVA: 0x3189c9c VA: 0x75957a1c9c
	public Void .ctor() { }
}
```