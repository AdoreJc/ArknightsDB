# AttributesData

**Namespace:** `Torappu`


## Fields

- `ObscuredInt maxHp`

- `ObscuredInt atk`

- `ObscuredInt def`

- `ObscuredFloat magicResistance`

- `ObscuredInt cost`

- `ObscuredInt blockCnt`

- `ObscuredFloat moveSpeed`

- `ObscuredFloat attackSpeed`

- `ObscuredFloat baseAttackTime`

- `ObscuredInt respawnTime`

- `ObscuredFloat hpRecoveryPerSec`

- `ObscuredFloat spRecoveryPerSec`

- `ObscuredInt maxDeployCount`

- `ObscuredInt maxDeckStackCnt`

- `ObscuredInt tauntLevel`

- `ObscuredInt massLevel`

- `ObscuredInt baseForceLevel`

- `ObscuredFloat epDamageResistance`

- `ObscuredFloat epResistance`

- `ObscuredFloat damageHitratePhysical`

- `ObscuredFloat damageHitrateMagical`

- `ObscuredFloat abilityRangeForwardExtend`

- `ObscuredFloat defPenetrate`

- `ObscuredFloat magicResistPenetrate`

- `ObscuredFloat hpRecoveryPerSecByMaxHpRatio`

- `ObscuredFloat defPenetrateFixed`

- `ObscuredFloat oneMinusStatusResistance`

- `ObscuredFloat magicResistPenetrateFixed`

- `ObscuredInt maxEp`

- `ObscuredFloat epRecoveryPerSec`

- `ObscuredFloat spRecoverRatio`

- `Boolean stunImmune`

- `Boolean silenceImmune`

- `Boolean sleepImmune`

- `Boolean frozenImmune`

- `Boolean levitateImmune`

- `Boolean disarmedCombatImmune`

- `Boolean fearedImmune`


## Methods

- `Void Assign(AttributesData)`

- `Void ApplyDelta(AttributesData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AttributesData
{
	public static readonly AttributesData ZERO; // 0x0
	private static List`1 s_fieldMetas; // 0x8
	public ObscuredInt maxHp; // 0x10
	public ObscuredInt atk; // 0x24
	public ObscuredInt def; // 0x38
	public ObscuredFloat magicResistance; // 0x4c
	public ObscuredInt cost; // 0x64
	public ObscuredInt blockCnt; // 0x78
	public ObscuredFloat moveSpeed; // 0x8c
	public ObscuredFloat attackSpeed; // 0xa4
	public ObscuredFloat baseAttackTime; // 0xbc
	public ObscuredInt respawnTime; // 0xd4
	public ObscuredFloat hpRecoveryPerSec; // 0xe8
	public ObscuredFloat spRecoveryPerSec; // 0x100
	public ObscuredInt maxDeployCount; // 0x118
	public ObscuredInt maxDeckStackCnt; // 0x12c
	public ObscuredInt tauntLevel; // 0x140
	public ObscuredInt massLevel; // 0x154
	public ObscuredInt baseForceLevel; // 0x168
	public ObscuredFloat epDamageResistance; // 0x17c
	public ObscuredFloat epResistance; // 0x194
	public ObscuredFloat damageHitratePhysical; // 0x1ac
	public ObscuredFloat damageHitrateMagical; // 0x1c4
	private ObscuredFloat abilityRangeForwardExtend; // 0x1dc
	private ObscuredFloat defPenetrate; // 0x1f4
	private ObscuredFloat magicResistPenetrate; // 0x20c
	private ObscuredFloat hpRecoveryPerSecByMaxHpRatio; // 0x224
	private ObscuredFloat defPenetrateFixed; // 0x23c
	private ObscuredFloat oneMinusStatusResistance; // 0x254
	private ObscuredFloat magicResistPenetrateFixed; // 0x26c
	public ObscuredInt maxEp; // 0x284
	public ObscuredFloat epRecoveryPerSec; // 0x298
	private ObscuredFloat spRecoverRatio; // 0x2b0
	public Boolean stunImmune; // 0x2c8
	public Boolean silenceImmune; // 0x2c9
	public Boolean sleepImmune; // 0x2ca
	public Boolean frozenImmune; // 0x2cb
	public Boolean levitateImmune; // 0x2cc
	public Boolean disarmedCombatImmune; // 0x2cd
	public Boolean fearedImmune; // 0x2ce

	public static List`1 fieldMetas { get; }

	// RVA: 0x33bf7c0 VA: 0x75959d77c0
	public static List`1 get_fieldMetas() { }
	// RVA: 0x33bfccc VA: 0x75959d7ccc
	public Void Assign(AttributesData other) { }
	// RVA: 0x33c0618 VA: 0x75959d8618
	public Void ApplyDelta(AttributesData delta) { }
	// RVA: 0x33c07bc VA: 0x75959d87bc
	public static AttributesData Lerp(AttributesData a, AttributesData b, Single t) { }
	// RVA: 0x33c0010 VA: 0x75959d8010
	public static Single ReadAttributesField(Object fieldVal) { }
	// RVA: 0x33c023c VA: 0x75959d823c
	public static Boolean WriteAttributesField(FieldInfo field, AttributesData attr, Single value) { }
	// RVA: 0x33c0fc8 VA: 0x75959d8fc8
	public static Boolean WriteAttributesField(FieldInfo field, AttributesData attr, FP value) { }
	// RVA: 0x33c0a58 VA: 0x75959d8a58
	public Void .ctor() { }
	// RVA: 0x33c1080 VA: 0x75959d9080
	private static Void .cctor() { }
}
```