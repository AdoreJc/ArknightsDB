# Mainline14LrdeadP2Manager

**Namespace:** `Torappu.Battle`


## Fields

- `Single _enemyEffectStartCol`

- `Single _allyEffectStartCol`

- `Vector3 _enemyEffStartPointOffset`

- `Vector3 _allyEffStartPointOffset`

- `Vector3 _enemyStartEffOffset`

- `String _markBuffKey`

- `String _excludeBuffKey`

- `String _allyCrossHitEffectKey`

- `String _enemyCrossHitEffectKey`

- `String _enemyHitAllyEffectKey`

- `String _enemyStartEffectKey`

- `String _allyStartEffectKey`

- `String _allyOneShotStartEffectKey`

- `Single _allyStartEffectDelay`

- `Single _allyHitEffectXAxisOffset`

- `Single _enemyHitEffectXAxisOffset`

- `Single _hitEffectZAxisOffset`

- `Single _crossPositionXAxisOffset`

- `Int32 _row`

- `Boolean m_isEnemySkillActived`

- `Boolean m_isAllySkillActived`

- `Boolean m_isBossDead`

- `Single m_targetCenterXOffset`

- `Single m_allyExceedOffset`

- `Int32 m_allySkillTriggerCount`

- `Int32 m_enemySkillTriggerCount`

- `Single m_enemyEffectStartCol`

- `Single m_allyEffectStartCol`

- `Int32 m_curEnemyEffectLevel`

- `Int32 m_curAllyEffectLevel`

- `Int32 m_row`

- `PeriodicTimer m_allySkillTimer`

- `Single m_allyAtk`

- `Single m_allyAtkStep`

- `Single m_allyAtkBound`

- `Single m_atkScaleToBoss`

- `Single m_enemyAtk`

- `Single m_enemyAtkStep`

- `Single m_enemyAtkBound`

- `PeriodicTimer m_dmgTickTimer`

- `Single m_dmgInterval`

- `Boolean m_applyDamageToLrcores`


## Methods

- `Void TriggerSkill(Boolean)`

- `Void _StartTimer()`

- `Void LrdeadDead()`

- `Void _OnGameOver(Object)`

- `Void _OnGameGiveUp(Object)`

- `Void _ProcessBlackboard()`

- `Void _TriggerAudioSignal(Single, Boolean)`

- `Void GatherAudio(List`1)`

- `Void _ClearEffects()`

- `Void _CreateEffects(Int32, Boolean)`

- `Void _InitEffectPos(EffectWithLineRenderer, Int32, Boolean)`

- `Void _UpdateEnemyEffectDestination(Int32)`

- `Void _UpdateAllyEffectDestination(Int32)`

- `Void _UpdateEffectCrossCol()`

- `Void _HideEffect(Int32, Boolean)`

- `Void _UpdateEnemyStartEffect()`

- `Void _UpdateHitEffectCol()`

- `Void _CreateAllyOneShotStartEffect()`

- `Void _UpdateAllyStartEffect()`

- `Void _DealEnemyToAllyDamage(FP)`

- `Void _DealEnemyToLrcoreDamage(FP)`

- `Void _DealAllyToEnemyDamage(FP)`

- `Boolean _ValidEntityShoulTakeDamage(Entity, Boolean)`

- `Boolean _ValidateCharacter(Character)`

- `Boolean _ValidateEnemy(Enemy)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Mainline14LrdeadP2Manager : EnvManager, IBuffSource, IHotfixable, IAudioSource
{
	private const Int32 EFFECT_LEVEL; // 0x0
	private const Single ENEMY_EXCEED_OFFSET; // 0x0
	private const Single ENEMY_EXCEED_OFFSET_WHEN_SKILL_TRIGGERED; // 0x0
	private const Single ALLY_EXCEED_OFFSET; // 0x0
	private const Single ALLY_EXCEED_OFFSET_WHEN_BOSS_DEAD; // 0x0
	private const String ROW_KEY; // 0x0
	private const String LRDEAD_CUSTOM_KEY; // 0x0
	private const String LRCORE_MARK_KEY; // 0x0
	private const String ENEMY_AUDIO_START_LEVEL_1; // 0x0
	private const String ENEMY_AUDIO_START_LEVEL_2; // 0x0
	private const String ENEMY_AUDIO_START_LEVEL_3; // 0x0
	private const String ENEMY_AUDIO_END_LEVEL_1; // 0x0
	private const String ENEMY_AUDIO_END_LEVEL_2; // 0x0
	private const String ENEMY_AUDIO_END_LEVEL_3; // 0x0
	private const String ALLY_AUDIO; // 0x0
	private String[] _allyEffectKeys; // 0x28
	private String[] _enemyEffectKeys; // 0x30
	private Single _enemyEffectStartCol; // 0x38
	private Single _allyEffectStartCol; // 0x3c
	private Vector3 _enemyEffStartPointOffset; // 0x40
	private Vector3 _allyEffStartPointOffset; // 0x4c
	private Vector3 _enemyStartEffOffset; // 0x58
	private String _markBuffKey; // 0x68
	private String _excludeBuffKey; // 0x70
	private String _allyCrossHitEffectKey; // 0x78
	private String _enemyCrossHitEffectKey; // 0x80
	private String _enemyHitAllyEffectKey; // 0x88
	private String _enemyStartEffectKey; // 0x90
	private String _allyStartEffectKey; // 0x98
	private String _allyOneShotStartEffectKey; // 0xa0
	private Single _allyStartEffectDelay; // 0xa8
	private Single _allyHitEffectXAxisOffset; // 0xac
	private Single _enemyHitEffectXAxisOffset; // 0xb0
	private Single _hitEffectZAxisOffset; // 0xb4
	private Single _crossPositionXAxisOffset; // 0xb8
	private Int32 _row; // 0xbc
	private Boolean m_isEnemySkillActived; // 0xc0
	private Boolean m_isAllySkillActived; // 0xc1
	private Boolean m_isBossDead; // 0xc2
	private Single m_targetCenterXOffset; // 0xc4
	private Single m_allyExceedOffset; // 0xc8
	private Int32 m_allySkillTriggerCount; // 0xcc
	private Int32 m_enemySkillTriggerCount; // 0xd0
	private Single m_enemyEffectStartCol; // 0xd4
	private Single m_allyEffectStartCol; // 0xd8
	private List`1 m_difs; // 0xe0
	private List`1 m_offsets; // 0xe8
	private Int32 m_curEnemyEffectLevel; // 0xf0
	private Int32 m_curAllyEffectLevel; // 0xf4
	private Int32 m_row; // 0xf8
	private PeriodicTimer m_allySkillTimer; // 0x100
	private Single m_allyAtk; // 0x108
	private Single m_allyAtkStep; // 0x10c
	private Single m_allyAtkBound; // 0x110
	private Single m_atkScaleToBoss; // 0x114
	private Single m_enemyAtk; // 0x118
	private Single m_enemyAtkStep; // 0x11c
	private Single m_enemyAtkBound; // 0x120
	private PeriodicTimer m_dmgTickTimer; // 0x128
	private Single m_dmgInterval; // 0x130
	private Boolean m_applyDamageToLrcores; // 0x134
	private Dictionary`2 m_allyEffectsDict; // 0x138
	private Dictionary`2 m_enemyEffectsDict; // 0x140
	private List`1 m_enemyHitEffectsList; // 0x148
	private List`1 m_allyHitEffectsList; // 0x150
	private List`1 m_enemyStartEffectsList; // 0x158
	private List`1 m_allyStartEffectsList; // 0x160
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge __Hotfix0_TriggerSkill; // 0x20
	private static DelegateBridge __Hotfix0__StartTimer; // 0x28
	private static DelegateBridge __Hotfix0_LrdeadDead; // 0x30
	private static DelegateBridge __Hotfix0__OnGameOver; // 0x38
	private static DelegateBridge __Hotfix0__OnGameGiveUp; // 0x40
	private static DelegateBridge __Hotfix0__ProcessBlackboard; // 0x48
	private static DelegateBridge __Hotfix0__TriggerAudioSignal; // 0x50
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x58
	private static DelegateBridge __Hotfix0__ClearEffects; // 0x60
	private static DelegateBridge __Hotfix0__CreateEffects; // 0x68
	private static DelegateBridge __Hotfix0__InitEffectPos; // 0x70
	private static DelegateBridge __Hotfix0__UpdateEnemyEffectDestination; // 0x78
	private static DelegateBridge __Hotfix0__UpdateAllyEffectDestination; // 0x80
	private static DelegateBridge __Hotfix0__UpdateEffectCrossCol; // 0x88
	private static DelegateBridge __Hotfix0__HideEffect; // 0x90
	private static DelegateBridge __Hotfix0__UpdateEnemyStartEffect; // 0x98
	private static DelegateBridge __Hotfix0__UpdateHitEffectCol; // 0xa0
	private static DelegateBridge __Hotfix0__CreateAllyOneShotStartEffect; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateAllyStartEffect; // 0xb0
	private static DelegateBridge __Hotfix0__DealEnemyToAllyDamage; // 0xb8
	private static DelegateBridge __Hotfix0__DealEnemyToLrcoreDamage; // 0xc0
	private static DelegateBridge __Hotfix0__DealAllyToEnemyDamage; // 0xc8
	private static DelegateBridge __Hotfix0__ValidEntityShoulTakeDamage; // 0xd0
	private static DelegateBridge __Hotfix0__ValidateCharacter; // 0xd8
	private static DelegateBridge __Hotfix0__ValidateEnemy; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x404ed24 VA: 0x7596666d24
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x404ef30 VA: 0x7596666f30
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x40500e8 VA: 0x75966680e8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40522c0 VA: 0x759666a2c0
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x4052344 VA: 0x759666a344
	public Void TriggerSkill(Boolean isEnemy) { }
	// RVA: 0x4052594 VA: 0x759666a594
	private Void _StartTimer() { }
	// RVA: 0x4052654 VA: 0x759666a654
	public Void LrdeadDead() { }
	// RVA: 0x40526f4 VA: 0x759666a6f4
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x4052770 VA: 0x759666a770
	private Void _OnGameGiveUp(Object arg) { }
	// RVA: 0x404f188 VA: 0x7596667188
	private Void _ProcessBlackboard() { }
	// RVA: 0x4050824 VA: 0x7596668824
	private Void _TriggerAudioSignal(Single oldEffectOffset, Boolean isTriggeredByEnemy) { }
	// RVA: 0x40527ec VA: 0x759666a7ec
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x404f76c VA: 0x759666776c
	private Void _ClearEffects() { }
	// RVA: 0x40502c4 VA: 0x75966682c4
	private Void _CreateEffects(Int32 level, Boolean isAlly) { }
	// RVA: 0x4052b94 VA: 0x759666ab94
	private Void _InitEffectPos(EffectWithLineRenderer effectPair, Int32 row, Boolean isAlly) { }
	// RVA: 0x4052f68 VA: 0x759666af68
	private Void _UpdateEnemyEffectDestination(Int32 level) { }
	// RVA: 0x4053210 VA: 0x759666b210
	private Void _UpdateAllyEffectDestination(Int32 level) { }
	// RVA: 0x4050658 VA: 0x7596668658
	private Void _UpdateEffectCrossCol() { }
	// RVA: 0x4052d64 VA: 0x759666ad64
	private Void _HideEffect(Int32 level, Boolean isAlly) { }
	// RVA: 0x4050b24 VA: 0x7596668b24
	private Void _UpdateEnemyStartEffect() { }
	// RVA: 0x40534a0 VA: 0x759666b4a0
	private Void _UpdateHitEffectCol() { }
	// RVA: 0x4052478 VA: 0x759666a478
	private Void _CreateAllyOneShotStartEffect() { }
	// RVA: 0x4050f7c VA: 0x7596668f7c
	private Void _UpdateAllyStartEffect() { }
	// RVA: 0x4051384 VA: 0x7596669384
	private Void _DealEnemyToAllyDamage(FP deltaTime) { }
	// RVA: 0x4051870 VA: 0x7596669870
	private Void _DealEnemyToLrcoreDamage(FP deltaTime) { }
	// RVA: 0x4051dcc VA: 0x7596669dcc
	private Void _DealAllyToEnemyDamage(FP deltaTime) { }
	// RVA: 0x4053ed8 VA: 0x759666bed8
	private Boolean _ValidEntityShoulTakeDamage(Entity target, Boolean isAlly) { }
	// RVA: 0x4053de4 VA: 0x759666bde4
	private Boolean _ValidateCharacter(Character character) { }
	// RVA: 0x4054014 VA: 0x759666c014
	private Boolean _ValidateEnemy(Enemy enemy) { }
	// RVA: 0x4054118 VA: 0x759666c118
	public Void .ctor() { }
	// RVA: 0x4054368 VA: 0x759666c368
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4054370 VA: 0x759666c370
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4054378 VA: 0x759666c378
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4054380 VA: 0x759666c380
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```