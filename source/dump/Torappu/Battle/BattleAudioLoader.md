# BattleAudioLoader

**Namespace:** `Torappu.Battle`


## Methods

- `Void PreloadOthers(LevelData)`

- `Void PreloadCustomTrigger(String)`

- `Void PreloadProjectile(String)`

- `Void PreloadAbility(String)`

- `Void PreloadCharacter(VoiceQuery, Character)`

- `Void PreloadUnit(String, String, Unit)`

- `Void PreloadEnemy(String, Enemy, Boolean)`

- `Void PreloadSkill(String, BasicSkill)`

- `Void PreloadBuffs(IList`1)`

- `Void PreloadActionNodes(IList`1)`

- `Void PreloadEffect(Effect)`

- `Void PreloadEnvSystem(GlobalEnvSystem)`

- `Void PreloadSkin(UnitAnimator)`

- `Void PreloadOperaRes(List`1)`

- `Void UnloadPreloadedAssets()`

- `IEnumerator UnloadOtherPersistTags()`

- `Void _PreloadSignal(String, String)`

- `Void _PreloadBuffSource(IBuffSource)`

- `Void _PreloadSpineEventSignal(String, String, Unit)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleAudioLoader : MonoBehaviour, IHotfixable
{
	private static readonly CharWordShowType[] BATTLE_CHARWORD_TYPES; // 0x0
	private String[] _extraUISignals; // 0x18
	private List`1 m_sharedList; // 0x20
	private List`1 m_sharedAbilityList; // 0x28
	private List`1 m_sharedBuffList; // 0x30
	private static DelegateBridge __Hotfix0_PreloadOthers; // 0x8
	private static DelegateBridge __Hotfix0_PreloadCustomTrigger; // 0x10
	private static DelegateBridge __Hotfix0_PreloadProjectile; // 0x18
	private static DelegateBridge __Hotfix0_PreloadAbility; // 0x20
	private static DelegateBridge __Hotfix0_PreloadCharacter; // 0x28
	private static DelegateBridge __Hotfix0_PreloadUnit; // 0x30
	private static DelegateBridge __Hotfix0_PreloadEnemy; // 0x38
	private static DelegateBridge __Hotfix0_PreloadSkill; // 0x40
	private static DelegateBridge __Hotfix0_PreloadBuffs; // 0x48
	private static DelegateBridge __Hotfix0_PreloadActionNodes; // 0x50
	private static DelegateBridge __Hotfix0_PreloadEffect; // 0x58
	private static DelegateBridge __Hotfix0_PreloadEnvSystem; // 0x60
	private static DelegateBridge __Hotfix0_PreloadSkin; // 0x68
	private static DelegateBridge __Hotfix0_PreloadOperaRes; // 0x70
	private static DelegateBridge __Hotfix0_UnloadPreloadedAssets; // 0x78
	private static DelegateBridge __Hotfix0_UnloadOtherPersistTags; // 0x80
	private static DelegateBridge __Hotfix0__PreloadSignal; // 0x88
	private static DelegateBridge __Hotfix0__PreloadBuffSource; // 0x90
	private static DelegateBridge __Hotfix0__PreloadSpineEventSignal; // 0x98
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x40ba614 VA: 0x75966d2614
	public Void PreloadOthers(LevelData levelData) { }
	// RVA: 0x40bab0c VA: 0x75966d2b0c
	public Void PreloadCustomTrigger(String subSignal) { }
	// RVA: 0x40babb4 VA: 0x75966d2bb4
	public Void PreloadProjectile(String projectileId) { }
	// RVA: 0x40baccc VA: 0x75966d2ccc
	public Void PreloadAbility(String abilityId) { }
	// RVA: 0x40bade4 VA: 0x75966d2de4
	public Void PreloadCharacter(VoiceQuery voiceQuery, Character character) { }
	// RVA: 0x40baef4 VA: 0x75966d2ef4
	public Void PreloadUnit(String unitId, String tmplId, Unit unit) { }
	// RVA: 0x40bb970 VA: 0x75966d3970
	public Void PreloadEnemy(String enemyId, Enemy enemy, Boolean isBoss) { }
	// RVA: 0x40bbb0c VA: 0x75966d3b0c
	public Void PreloadSkill(String skillId, BasicSkill skill) { }
	// RVA: 0x40bbea4 VA: 0x75966d3ea4
	public Void PreloadBuffs(IList`1 buffs) { }
	// RVA: 0x40bc0dc VA: 0x75966d40dc
	public Void PreloadActionNodes(IList`1 actionNodes) { }
	// RVA: 0x40bc3a0 VA: 0x75966d43a0
	public Void PreloadEffect(Effect effect) { }
	// RVA: 0x40bc624 VA: 0x75966d4624
	public Void PreloadEnvSystem(GlobalEnvSystem envSystem) { }
	// RVA: 0x40bc89c VA: 0x75966d489c
	public Void PreloadSkin(UnitAnimator animator) { }
	// RVA: 0x40bcf88 VA: 0x75966d4f88
	public Void PreloadOperaRes(List`1 audioList) { }
	// RVA: 0x40bd08c VA: 0x75966d508c
	public Void UnloadPreloadedAssets() { }
	// RVA: 0x40bd174 VA: 0x75966d5174
	public IEnumerator UnloadOtherPersistTags() { }
	// RVA: 0x40baa34 VA: 0x75966d2a34
	private Void _PreloadSignal(String signal, String subSignal) { }
	// RVA: 0x40bb7f0 VA: 0x75966d37f0
	private Void _PreloadBuffSource(IBuffSource buffSource) { }
	// RVA: 0x40bb17c VA: 0x75966d317c
	private Void _PreloadSpineEventSignal(String signal, String id, Unit unit) { }
	// RVA: 0x40bd248 VA: 0x75966d5248
	private Void OnDestroy() { }
	// RVA: 0x40bd2c0 VA: 0x75966d52c0
	public Void .ctor() { }
	// RVA: 0x40bd470 VA: 0x75966d5470
	private static Void .cctor() { }
}
```