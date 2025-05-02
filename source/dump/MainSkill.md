# MainSkill

**Namespace:** ` `


## Fields

- `String skillId`

- `String overridePrefabKey`

- `String overrideTokenKey`

- `UnlockCondition initialUnlockCond`


## Methods

- `Boolean TryGetUnlockCondition(Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MainSkill
{
	public String skillId; // 0x10
	public String overridePrefabKey; // 0x18
	public String overrideTokenKey; // 0x20
	public SpecializeLevelData[] specializeLevelUpData; // 0x28
	public UnlockCondition initialUnlockCond; // 0x30


	// RVA: 0x33c9aa8 VA: 0x75959e1aa8
	public Boolean TryGetUnlockCondition(Int32 totalLvl, out UnlockCondition condition) { }
	// RVA: 0x33c9b70 VA: 0x75959e1b70
	public Void .ctor() { }
}
```