# AttackWrapper

**Namespace:** ` `


## Fields

- `Enemy m_enemy`

- `Entity m_curTarget`

- `EnemySkill m_curSkill`

- `Ability m_curAbility`

- `Ability m_lastAbility`

- `EnemySkill m_lastSkill`


## Properties

- `Boolean isValid`

- `Ability mainAttack`

- `TargetTrigger mainTrigger`

- `Ability lastAbility`

- `EnemySkill lastSkill`


## Methods

- `Boolean get_isValid()`

- `Ability get_mainAttack()`

- `TargetTrigger get_mainTrigger()`

- `Ability get_lastAbility()`

- `EnemySkill get_lastSkill()`

- `Void Reset()`

- `Boolean SearchTarget()`

- `Boolean Cast(out, FinishCallbackDelegate, Boolean)`

- `Void _OnCastFinish(Ability, FinishReason, Boolean)`

- `Void AssignAbility(Ability, Entity, EnemySkill)`

- `EnemySkill TryGetFirstAttachedSkill(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttackWrapper : IHotfixable
{
	private Enemy m_enemy; // 0x10
	private Entity m_curTarget; // 0x18
	private EnemySkill m_curSkill; // 0x20
	private Ability m_curAbility; // 0x28
	private Ability m_lastAbility; // 0x30
	private EnemySkill m_lastSkill; // 0x38
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_mainAttack; // 0x8
	private static DelegateBridge __Hotfix0_get_mainTrigger; // 0x10
	private static DelegateBridge __Hotfix0_get_skills; // 0x18
	private static DelegateBridge __Hotfix0_get_lastAbility; // 0x20
	private static DelegateBridge __Hotfix0_get_lastSkill; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge __Hotfix0_SearchTarget; // 0x40
	private static DelegateBridge __Hotfix0_Cast; // 0x48
	private static DelegateBridge __Hotfix0__OnCastFinish; // 0x50
	private static DelegateBridge __Hotfix0_AssignAbility; // 0x58
	private static DelegateBridge __Hotfix0_TryGetFirstAttachedSkill; // 0x60

	public Boolean isValid { get; }
	protected Ability mainAttack { get; }
	protected TargetTrigger mainTrigger { get; }
	protected List`1 skills { get; }
	public Ability lastAbility { get; }
	public EnemySkill lastSkill { get; }

	// RVA: 0x1c15ce4 VA: 0x759422dce4
	public Boolean get_isValid() { }
	// RVA: 0x1c15d7c VA: 0x759422dd7c
	protected Ability get_mainAttack() { }
	// RVA: 0x1c15df8 VA: 0x759422ddf8
	protected TargetTrigger get_mainTrigger() { }
	// RVA: 0x1c15e74 VA: 0x759422de74
	protected List`1 get_skills() { }
	// RVA: 0x1c15ee8 VA: 0x759422dee8
	public Ability get_lastAbility() { }
	// RVA: 0x1c15f50 VA: 0x759422df50
	public EnemySkill get_lastSkill() { }
	// RVA: 0x1c15fb8 VA: 0x759422dfb8
	public Void Reset() { }
	// RVA: 0x1c16038 VA: 0x759422e038
	public Void .ctor(Enemy enemy) { }
	// RVA: 0x1c160cc VA: 0x759422e0cc
	public Boolean SearchTarget() { }
	// RVA: 0x1c0baa4 VA: 0x7594223aa4
	public Boolean Cast(out Ability ability, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1c16674 VA: 0x759422e674
	private Void _OnCastFinish(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1c167b4 VA: 0x759422e7b4
	public Void AssignAbility(Ability ability, Entity target, EnemySkill skill) { }
	// RVA: 0x1c16874 VA: 0x759422e874
	public EnemySkill TryGetFirstAttachedSkill(String skillName) { }
}
```