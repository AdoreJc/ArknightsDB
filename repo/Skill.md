# Skill 技能

>All code below from `Assembly-CSharp.dll`, if not, will mark the dll name.

>以下所有代码都在`Assembly-CSharp.dll`，其他dll会标注出来。

## PlayerCharSkill
```C#
// Namespace: Torappu
[Serializable]
public class PlayerCharSkill
{
	public Boolean unlock; // 0x10
	public String skillId; // 0x18
	public Int32 specializeLevel; // 0x20
}
```

## SkillData
```C#
// Dll : Assembly-CSharp.dll
// Namespace: Torappu.DB.Test
[Serializable]
public class SkillData
{
	public String key; // 0x10
	public Int32 sortID; // 0x18
	public String name; // 0x20
	public String info; // 0x28
	public String animationKey; // 0x30
	public Int32 maxLvl; // 0x38
	public Dictionary`2 lvlInfo; // 0x40
	public Dictionary`2 lvlBuffData; // 0x48
	public String childSkillId; // 0x50
	public String preSkillId; // 0x58
	public Single scale; // 0x60
	public ElementInfo elementInfo; // 0x68
	public String actualSkillId; // 0x70
}
```

```C#
// Dll : Assembly-CSharp.dll
// Namespace: Torappu
[Serializable]
public class SkillData : ISkillData, IHotfixable
{
	// Fields
	public String name; // 0x10
	public String skillId; // 0x18
	public String rangeId; // 0x20
	public String iconId; // 0x28
	public Int32 level; // 0x30
	public String description; // 0x38
	public SkillType skillType; // 0x40
	public SkillDurationType durationType; // 0x44
	public SpData spData; // 0x48
	public String prefabKey; // 0x50
	public Single duration; // 0x58
	public Blackboard blackboard; // 0x60
	public Boolean isPrefabKeyOverridden; // 0x68
	private Boolean m_inited; // 0x69
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_needToDisplay; // 0x8
	private static DelegateBridge __Hotfix0_get_spCost; // 0x10
	private static DelegateBridge __Hotfix0_get_maxSp; // 0x18
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_CreateInvalid; // 0x28
	private static DelegateBridge __Hotfix0_GetSkillId; // 0x30
	private static DelegateBridge __Hotfix0_GetIconId; // 0x38
	private static DelegateBridge __Hotfix0_Duplicate; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	// Properties
	public Boolean isValid { get; }
	public Boolean needToDisplay { get; }
	public Int32 spCost { get; }
	public Int32 maxSp { get; }

	// Methods
	// RVA: 0x34f5150 VA: 0x7595b0d150
	public Boolean get_isValid() { }
	// RVA: 0x34f51c8 VA: 0x7595b0d1c8
	public Boolean get_needToDisplay() { }
	// RVA: 0x34f5240 VA: 0x7595b0d240
	public Int32 get_spCost() { }
	// RVA: 0x34f530c VA: 0x7595b0d30c
	public Int32 get_maxSp() { }
	// RVA: 0x34f53d0 VA: 0x7595b0d3d0
	public Void InitIfNot() { }
	// RVA: 0x34f54d8 VA: 0x7595b0d4d8
	public static SkillData CreateInvalid() { }
	// RVA: 0x34f5650 VA: 0x7595b0d650
	public String GetSkillId() { }
	// RVA: 0x34f56b8 VA: 0x7595b0d6b8
	public String GetIconId() { }
	// RVA: 0x34f5720 VA: 0x7595b0d720
	public SkillData Duplicate() { }
	// RVA: 0x34f5550 VA: 0x7595b0d550
	public Void .ctor() { }
}
```

## SkillType

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SkillType
{
	// Fields
	public Int32 value__; // 0x10
	public const SkillType PASSIVE = 0; // 0x0
	public const SkillType MANUAL = 1; // 0x0
	public const SkillType AUTO = 2; // 0x0
}
```

## SkillDurationType

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SkillDurationType
{
	// Fields
	public Int32 value__; // 0x10
	public const SkillDurationType NONE = 0; // 0x0
	public const SkillDurationType AMMO = 1; // 0x0

	// Properties

	// Methods
}
```

## Sp 技力

```C#
// Dll : Assembly-CSharp.dll
// Namespace: Torappu
[Serializable]
public class SpData : IHotfixable
{
	// Fields
	private static readonly SpData DEFAULT; // 0x0
	public SpType spType; // 0x10
	public ItemBundle[] levelUpCost; // 0x18
	public ObscuredInt maxChargeTime; // 0x20
	public ObscuredInt spCost; // 0x34
	public ObscuredInt initSp; // 0x48
	public ObscuredFloat increment; // 0x5c
	private Single[] m_incrementsForAllSpTypes; // 0x78
	private static DelegateBridge __Hotfix0_GetDefault; // 0x8
	private static DelegateBridge __Hotfix0_get_maxSp; // 0x10
	private static DelegateBridge __Hotfix0_get_inited; // 0x18
	private static DelegateBridge __Hotfix0_get_incrementsForAllSpTypes; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_CreateFrom; // 0x30
	private static DelegateBridge __Hotfix0_Duplicate; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	// Properties
	public ObscuredInt maxSp { get; }
	public Boolean inited { get; }
	public Single[] incrementsForAllSpTypes { get; }

	// Methods
	// RVA: 0x34f4830 VA: 0x7595b0c830
	public static SpData GetDefault() { }
	// RVA: 0x34f4ac8 VA: 0x7595b0cac8
	public ObscuredInt get_maxSp() { }
	// RVA: 0x34f4be8 VA: 0x7595b0cbe8
	public Boolean get_inited() { }
	// RVA: 0x34f4c68 VA: 0x7595b0cc68
	public Single[] get_incrementsForAllSpTypes() { }
	// RVA: 0x34f48d4 VA: 0x7595b0c8d4
	public Void Init(Blackboard blackboard) { }
	// RVA: 0x34f4ce0 VA: 0x7595b0cce0
	public static SpData CreateFrom(ESpData eSpData, Blackboard blackboard) { }
	// RVA: 0x34f500c VA: 0x7595b0d00c
	public SpData Duplicate() { }
	// RVA: 0x34f4ea4 VA: 0x7595b0cea4
	public Void .ctor() { }
	// RVA: 0x34f50e4 VA: 0x7595b0d0e4
	private static Void .cctor() { }
}
```

### SpTypeIndex
|enum|name|description|
|----|----|----|
|0|INCREASE_WITH_TIME|自动回复|
|1|INCREASE_WHEN_ATTACK|攻击回复|
|2|INCREASE_WHEN_TAKEN_DAMAGE|受击回复|
|3|NEVER_USE|不使用？|
|4|E_NUM|？？|

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SpTypeIndex
{
	public Int32 value__; // 0x10
	public const SpTypeIndex INCREASE_WITH_TIME = 0; // 0x0
	public const SpTypeIndex INCREASE_WHEN_ATTACK = 1; // 0x0
	public const SpTypeIndex INCREASE_WHEN_TAKEN_DAMAGE = 2; // 0x0
	public const SpTypeIndex NEVER_USE = 3; // 0x0
	public const SpTypeIndex E_NUM = 4; // 0x0
}
```
### SpType
|enum|name|description|
|----|----|----|
|0|INCREASE_WITH_TIME|自动回复|
|1|INCREASE_WHEN_ATTACK|攻击回复|
|2|INCREASE_WHEN_TAKEN_DAMAGE|受击回复|
|6|NEVER_USE|不使用？|
|7|E_NUM|？？|

```C#
// Dll : Torappu.Common.dll
// Namespace: Torappu
public enum SpType
{
	public Int32 value__; // 0x10
	public const SpType NONE = 0; // 0x0
	public const SpType INCREASE_WITH_TIME = 1; // 0x0
	public const SpType INCREASE_WHEN_ATTACK = 2; // 0x0
	public const SpType INCREASE_WHEN_TAKEN_DAMAGE = 4; // 0x0
	public const SpType ATTACK_OR_DAMAGE = 6; // 0x0
	public const SpType ALL = 7; // 0x0
}
```