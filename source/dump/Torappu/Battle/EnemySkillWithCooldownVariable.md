# EnemySkillWithCooldownVariable

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_currentIndex`


## Methods

- `Void _CollectCooldownList()`

- `Void <>xLuaBaseProxy_AssignData(ESkillData, Enemy)`

- `Void <>xLuaBaseProxy_ResetSkillCooldownIfNeeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemySkillWithCooldownVariable : EnemySkill
{
	private List`1 m_cooldownSequenceList; // 0x90
	private Int32 m_currentIndex; // 0x98
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0__CollectCooldownList; // 0x8
	private static DelegateBridge __Hotfix0_ResetSkillCooldownIfNeeded; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3fbe310 VA: 0x75965d6310
	public override Void AssignData(ESkillData data, Enemy owner) { }
	// RVA: 0x3fbe3d0 VA: 0x75965d63d0
	private Void _CollectCooldownList() { }
	// RVA: 0x3fbe574 VA: 0x75965d6574
	public override Void ResetSkillCooldownIfNeeded() { }
	// RVA: 0x3fbe6a4 VA: 0x75965d66a4
	public Void .ctor() { }
	// RVA: 0x3fbe764 VA: 0x75965d6764
	private Void <>xLuaBaseProxy_AssignData(ESkillData P0, Enemy P1) { }
	// RVA: 0x3fbe768 VA: 0x75965d6768
	private Void <>xLuaBaseProxy_ResetSkillCooldownIfNeeded() { }
}
```