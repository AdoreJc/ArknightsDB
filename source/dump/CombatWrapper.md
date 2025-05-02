# CombatWrapper

**Namespace:** ` `


## Fields

- `Enemy m_enemy`

- `Ability m_pickedAbility`

- `EnemySkill m_pickedSkill`

- `Boolean m_combatAbilityPicked`

- `Boolean m_isCombatInterrupted`

- `Ability m_lastAbility`

- `EnemySkill m_lastSkill`


## Properties

- `Boolean isValid`

- `Boolean isCombatInterrupted`

- `Ability mainCombat`

- `Ability lastAbility`

- `EnemySkill lastSkill`


## Methods

- `Boolean get_isValid()`

- `Boolean get_isCombatInterrupted()`

- `Void set_isCombatInterrupted(Boolean)`

- `Boolean PickCombatAbility()`

- `Ability get_mainCombat()`

- `Ability get_lastAbility()`

- `EnemySkill get_lastSkill()`

- `Void Reset()`

- `Character GetTarget()`

- `Void NextCombatOrExit(Boolean)`

- `Boolean StartCombat(Boolean)`

- `Void CombatFinishCallback(Ability, FinishReason, Boolean)`

- `Boolean CastToTarget(Entity, out, FinishCallbackDelegate, Boolean)`

- `Void AssignAbility(Ability)`

- `Boolean CastWithAssignedSkill(Ability, Entity, EnemySkill)`

- `Boolean _DoCast(Ability, Entity, EnemySkill, FinishCallbackDelegate, Boolean)`

- `Boolean _EarlyPickAbility()`

- `Boolean _PickAbility(out, out)`

- `Void _OnCastFinish(Ability, FinishReason, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CombatWrapper : IHotfixable
{
	private Enemy m_enemy; // 0x10
	private Ability m_pickedAbility; // 0x18
	private EnemySkill m_pickedSkill; // 0x20
	private Boolean m_combatAbilityPicked; // 0x28
	private Boolean m_isCombatInterrupted; // 0x29
	private Ability m_lastAbility; // 0x30
	private EnemySkill m_lastSkill; // 0x38
	private static DelegateBridge __Hotfix0_get_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_isCombatInterrupted; // 0x8
	private static DelegateBridge __Hotfix0_set_isCombatInterrupted; // 0x10
	private static DelegateBridge __Hotfix0_PickCombatAbility; // 0x18
	private static DelegateBridge __Hotfix0_get_skills; // 0x20
	private static DelegateBridge __Hotfix0_get_mainCombat; // 0x28
	private static DelegateBridge __Hotfix0_get_lastAbility; // 0x30
	private static DelegateBridge __Hotfix0_get_lastSkill; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0_GetTarget; // 0x50
	private static DelegateBridge __Hotfix0_NextCombatOrExit; // 0x58
	private static DelegateBridge __Hotfix0_StartCombat; // 0x60
	private static DelegateBridge __Hotfix0_CombatFinishCallback; // 0x68
	private static DelegateBridge __Hotfix0_CastToTarget; // 0x70
	private static DelegateBridge __Hotfix0_AssignAbility; // 0x78
	private static DelegateBridge __Hotfix0_CastWithAssignedSkill; // 0x80
	private static DelegateBridge __Hotfix0__DoCast; // 0x88
	private static DelegateBridge __Hotfix0__EarlyPickAbility; // 0x90
	private static DelegateBridge __Hotfix0__PickAbility; // 0x98
	private static DelegateBridge __Hotfix0__OnCastFinish; // 0xa0

	public Boolean isValid { get; }
	public Boolean isCombatInterrupted { get; set; }
	protected List`1 skills { get; }
	public Ability mainCombat { get; }
	public Ability lastAbility { get; }
	public EnemySkill lastSkill { get; }

	// RVA: 0x1c16a04 VA: 0x759422ea04
	public Boolean get_isValid() { }
	// RVA: 0x1c16aa4 VA: 0x759422eaa4
	public Boolean get_isCombatInterrupted() { }
	// RVA: 0x1c16b0c VA: 0x759422eb0c
	public Void set_isCombatInterrupted(Boolean value) { }
	// RVA: 0x1c0dcc0 VA: 0x7594225cc0
	public Boolean PickCombatAbility() { }
	// RVA: 0x1c16c08 VA: 0x759422ec08
	protected List`1 get_skills() { }
	// RVA: 0x1c16c7c VA: 0x759422ec7c
	public Ability get_mainCombat() { }
	// RVA: 0x1c16cf8 VA: 0x759422ecf8
	public Ability get_lastAbility() { }
	// RVA: 0x1c16d60 VA: 0x759422ed60
	public EnemySkill get_lastSkill() { }
	// RVA: 0x1c16dc8 VA: 0x759422edc8
	public Void Reset() { }
	// RVA: 0x1c16e70 VA: 0x759422ee70
	public Void .ctor(Enemy enemy) { }
	// RVA: 0x1c0dc4c VA: 0x7594225c4c
	public Character GetTarget() { }
	// RVA: 0x1c0dd78 VA: 0x7594225d78
	public Void NextCombatOrExit(Boolean firstAttack) { }
	// RVA: 0x1c16f04 VA: 0x759422ef04
	public Boolean StartCombat(Boolean firstAttack) { }
	// RVA: 0x1c170f8 VA: 0x759422f0f8
	private Void CombatFinishCallback(Ability ability, FinishReason reason, Boolean resetCd) { }
	// RVA: 0x1c17000 VA: 0x759422f000
	public Boolean CastToTarget(Entity target, out Ability ability, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1c179fc VA: 0x759422f9fc
	public Void AssignAbility(Ability ability) { }
	// RVA: 0x1c17a88 VA: 0x759422fa88
	public Boolean CastWithAssignedSkill(Ability ability, Entity target, EnemySkill skill) { }
	// RVA: 0x1c172dc VA: 0x759422f2dc
	private Boolean _DoCast(Ability ability, Entity target, EnemySkill skill, FinishCallbackDelegate finishCb, Boolean firstAttack) { }
	// RVA: 0x1c16b8c VA: 0x759422eb8c
	private Boolean _EarlyPickAbility() { }
	// RVA: 0x1c17584 VA: 0x759422f584
	private Boolean _PickAbility(out Ability ability, out EnemySkill skill) { }
	// RVA: 0x1c17b80 VA: 0x759422fb80
	private Void _OnCastFinish(Ability ability, FinishReason reason, Boolean resetCd) { }
}
```