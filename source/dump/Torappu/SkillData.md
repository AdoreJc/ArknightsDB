# SkillData

**Namespace:** `Torappu`


## Fields

- `String name`

- `String skillId`

- `String rangeId`

- `String iconId`

- `Int32 level`

- `String description`

- `SkillType skillType`

- `SkillDurationType durationType`

- `SpData spData`

- `String prefabKey`

- `Single duration`

- `Blackboard blackboard`

- `Boolean isPrefabKeyOverridden`

- `Boolean m_inited`


## Properties

- `Boolean isValid`

- `Boolean needToDisplay`

- `Int32 spCost`

- `Int32 maxSp`


## Methods

- `Boolean get_isValid()`

- `Boolean get_needToDisplay()`

- `Int32 get_spCost()`

- `Int32 get_maxSp()`

- `Void InitIfNot()`

- `String GetSkillId()`

- `String GetIconId()`

- `SkillData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SkillData : ISkillData, IHotfixable
{
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

	public Boolean isValid { get; }
	public Boolean needToDisplay { get; }
	public Int32 spCost { get; }
	public Int32 maxSp { get; }

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