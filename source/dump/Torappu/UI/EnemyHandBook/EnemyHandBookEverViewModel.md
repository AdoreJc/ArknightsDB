# EnemyHandBookEverViewModel

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `InternalEnemyHBData enemyData`

- `EnemyHandBookData data`

- `String hp`

- `String moveSpeed`

- `String attack`

- `String def`

- `String magDef`

- `String attackSpeed`

- `String raceName`

- `String enemyDamageRes`

- `String enemyRes`

- `Boolean isSp`

- `Boolean invisible`

- `Boolean isInStage`

- `Boolean unlockType`


## Properties

- `Boolean frozenImmune`

- `Boolean levitateImmune`

- `Boolean stunImmune`

- `Boolean disarmImmune`

- `Boolean sleepImmune`

- `Boolean fearedImmune`

- `Int32 weight`


## Methods

- `Void _GenAttriParam()`

- `Boolean get_frozenImmune()`

- `Boolean get_levitateImmune()`

- `Boolean get_stunImmune()`

- `Boolean get_disarmImmune()`

- `Boolean get_sleepImmune()`

- `Boolean get_fearedImmune()`

- `Int32 get_weight()`

- `Void _RefreshAttribute(RangePair, String, Single, ref)`

- `Int32 CompareTo(EnemyHandBookEverViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookEverViewModel : IHotfixable, IComparable`1
{
	public InternalEnemyHBData enemyData; // 0x10
	public EnemyHandBookData data; // 0x18
	public String hp; // 0x20
	public String moveSpeed; // 0x28
	public String attack; // 0x30
	public String def; // 0x38
	public String magDef; // 0x40
	public String attackSpeed; // 0x48
	public String raceName; // 0x50
	public String enemyDamageRes; // 0x58
	public String enemyRes; // 0x60
	public Boolean isSp; // 0x68
	public Boolean invisible; // 0x69
	public List`1 linkEnemies; // 0x70
	public Boolean isInStage; // 0x78
	public Boolean unlockType; // 0x79
	private static DelegateBridge __Hotfix0__GenAttriParam; // 0x0
	private static DelegateBridge __Hotfix0_get_frozenImmune; // 0x8
	private static DelegateBridge __Hotfix0_get_levitateImmune; // 0x10
	private static DelegateBridge __Hotfix0_get_stunImmune; // 0x18
	private static DelegateBridge __Hotfix0_get_disarmImmune; // 0x20
	private static DelegateBridge __Hotfix0_get_sleepImmune; // 0x28
	private static DelegateBridge __Hotfix0_get_fearedImmune; // 0x30
	private static DelegateBridge __Hotfix0_get_weight; // 0x38
	private static DelegateBridge __Hotfix0__RefreshAttribute; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge _c__Hotfix1_ctor; // 0x50
	private static DelegateBridge __Hotfix0_CompareTo; // 0x58

	public Boolean frozenImmune { get; }
	public Boolean levitateImmune { get; }
	public Boolean stunImmune { get; }
	public Boolean disarmImmune { get; }
	public Boolean sleepImmune { get; }
	public Boolean fearedImmune { get; }
	public Int32 weight { get; }

	// RVA: 0x2939964 VA: 0x7594f51964
	private Void _GenAttriParam() { }
	// RVA: 0x2935bd8 VA: 0x7594f4dbd8
	public Boolean get_frozenImmune() { }
	// RVA: 0x2935c58 VA: 0x7594f4dc58
	public Boolean get_levitateImmune() { }
	// RVA: 0x2935d58 VA: 0x7594f4dd58
	public Boolean get_stunImmune() { }
	// RVA: 0x2935dd8 VA: 0x7594f4ddd8
	public Boolean get_disarmImmune() { }
	// RVA: 0x2935cd8 VA: 0x7594f4dcd8
	public Boolean get_sleepImmune() { }
	// RVA: 0x2935e58 VA: 0x7594f4de58
	public Boolean get_fearedImmune() { }
	// RVA: 0x2935b60 VA: 0x7594f4db60
	public Int32 get_weight() { }
	// RVA: 0x2939df8 VA: 0x7594f51df8
	private Void _RefreshAttribute(RangePair pair, String level, Single value, ref String text) { }
	// RVA: 0x2939ee8 VA: 0x7594f51ee8
	public Void .ctor(EnemyDataDbReference enemyBattleData, EnemyHandBookData enemyHandBookData, Boolean unlockType) { }
	// RVA: 0x293a0ac VA: 0x7594f520ac
	public Void .ctor(EnemyHandBookData enemyHandBookData, Boolean unlockType) { }
	// RVA: 0x293a258 VA: 0x7594f52258
	public Int32 CompareTo(EnemyHandBookEverViewModel other) { }
}
```