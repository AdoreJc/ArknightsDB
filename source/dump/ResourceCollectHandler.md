# ResourceCollectHandler

**Namespace:** ` `


## Fields

- `AbstractAssetLoader m_assetLoader`

- `BattleAudioLoader m_audioLoader`

- `Int32 m_yieldCnt`

- `Single m_startTime`


## Properties

- `Boolean m_isComplete`


## Methods

- `Boolean get_m_isComplete()`

- `IEnumerator Gather(MonoBehaviour, BattleAudioLoader, LevelData, List`1, AbstractAssetLoader, Difficulty)`

- `Void _GetOperaPreloadRes(String, String, List`1, List`1)`

- `IEnumerator GatherEnemy(EnemyData, TaskWrapper)`

- `IEnumerator GatherCharacter(BattleCharacterData, TaskWrapper)`

- `IEnumerator GatherToken(BattleCharacterData, TaskWrapper)`

- `IEnumerator GatherSkin(CharSkinData)`

- `Void GatherUniEquip(List`1)`

- `Void GatherExtraEnemyFromTalent(List`1, Int32)`

- `IEnumerator GatherSkill(SkillData)`

- `IEnumerator GatherSkillRelatedEffectBlacklist(SkillData)`

- `IEnumerator GatherEffect(String, TaskWrapper)`

- `IEnumerator GatherProjectile(String, TaskWrapper)`

- `IEnumerator GatherDynamicAbility(List`1, TaskWrapper)`

- `Void GatherExtraEffects()`

- `Void _GatherEpBreakBuffEffects()`

- `IEnumerator GatherEnvSystem(String, TaskWrapper)`

- `IEnumerator GatherGlobalBuff(String, TaskWrapper)`

- `Void GatherAssetsFromGameMode()`

- `Void GatherInputAndLevelRunes(LevelData)`

- `Void GatherAssetsInternal(T)`

- `Void _GatherEffectsFromBuffsRecursively(Int32, ref, ref)`

- `Void GatherAssetsInsideEffect(Effect)`

- `Void GatherFromEffectSource(IEffectSource)`

- `Void GatherFromProjectileSource(IProjectileSource)`

- `Boolean AppendRes(ObjectConfig, Boolean, Boolean)`

- `Void _CreateTask(PreloadType, Object)`

- `Void _StartPreloadTask(MonoBehaviour)`

- `Void <GatherInputAndLevelRunes>b__47_0(RuneData)`

- `Void <GatherInputAndLevelRunes>b__47_1(RuneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ResourceCollectHandler : IHotfixable
{
	private const Int32 PROJECTILE_PRELOAD_CNT; // 0x0
	private const Int32 EFFECT_AUTO_REUSE_CAPACITY; // 0x0
	private const Int32 DYNAMIC_ABILITY_CNT; // 0x0
	private const Int32 ENV_SYSTEM_CNT; // 0x0
	private const Int32 GLOBAL_BUFF_CNT; // 0x0
	private const String BUFF_TEMPLATE_EMPTY_KEY; // 0x0
	private static List`1 s_sharedBuffList; // 0x0
	private static List`1 s_sharedActionList; // 0x8
	private AbstractAssetLoader m_assetLoader; // 0x10
	private List`1 m_preloadConfigs; // 0x18
	private List`1 m_runtimeLoadConfigs; // 0x20
	private HashSet`1 m_hashSet; // 0x28
	private Queue`1 m_paddingTasks; // 0x30
	private List`1 m_runningTasks; // 0x38
	private List`1 m_effectBlackList; // 0x40
	private List`1 m_effectBlackListIncludeSkin; // 0x48
	private BattleAudioLoader m_audioLoader; // 0x50
	private Int32 m_yieldCnt; // 0x58
	private Single m_startTime; // 0x5c
	private static DelegateBridge __Hotfix0_get_m_isComplete; // 0x10
	private static DelegateBridge __Hotfix0_Gather; // 0x18
	private static DelegateBridge __Hotfix0__GetOperaPreloadRes; // 0x20
	private static DelegateBridge __Hotfix0_GetPreloadConfigs; // 0x28
	private static DelegateBridge __Hotfix0_GetRuntimeLoadConfigs; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffectsFromBuff; // 0x38
	private static DelegateBridge __Hotfix0__GatherEffectsFromBuff; // 0x40
	private static DelegateBridge __Hotfix0__GatherEffectsFromSingleBuff; // 0x48
	private static DelegateBridge __Hotfix0__GatherEffectsInsideTemplate; // 0x50
	private static DelegateBridge __Hotfix0_GatherActionNodesFromBuff; // 0x58
	private static DelegateBridge __Hotfix1_GatherActionNodesFromBuff; // 0x60
	private static DelegateBridge __Hotfix0_GatherEnemy; // 0x68
	private static DelegateBridge __Hotfix0_GatherCharacter; // 0x70
	private static DelegateBridge __Hotfix0_GatherToken; // 0x78
	private static DelegateBridge __Hotfix0_GatherSkin; // 0x80
	private static DelegateBridge __Hotfix0_GatherUniEquip; // 0x88
	private static DelegateBridge __Hotfix0_GatherExtraEnemyFromTalent; // 0x90
	private static DelegateBridge __Hotfix0_GatherSkill; // 0x98
	private static DelegateBridge __Hotfix0_GatherSkillRelatedEffectBlacklist; // 0xa0
	private static DelegateBridge __Hotfix0_GatherEffect; // 0xa8
	private static DelegateBridge __Hotfix0_GatherProjectile; // 0xb0
	private static DelegateBridge __Hotfix0_GatherDynamicAbility; // 0xb8
	private static DelegateBridge __Hotfix0_GatherExtraEffects; // 0xc0
	private static DelegateBridge __Hotfix0__GatherEpBreakBuffEffects; // 0xc8
	private static DelegateBridge __Hotfix0_GatherEnvSystem; // 0xd0
	private static DelegateBridge __Hotfix0_GatherGlobalBuff; // 0xd8
	private static DelegateBridge __Hotfix0_GatherAssetsFromGameMode; // 0xe0
	private static DelegateBridge __Hotfix0_GatherInputAndLevelRunes; // 0xe8
	private static DelegateBridge __Hotfix0_GatherAssetsInternal; // 0xf0
	private static DelegateBridge __Hotfix0__GatherEffectsFromBuffsRecursively; // 0xf8
	private static DelegateBridge __Hotfix0_GatherAssetsInsideEffect; // 0x100
	private static DelegateBridge __Hotfix0_GatherFromEffectSource; // 0x108
	private static DelegateBridge __Hotfix0_GatherFromProjectileSource; // 0x110
	private static DelegateBridge __Hotfix0_AppendRes; // 0x118
	private static DelegateBridge __Hotfix0__CreateTask; // 0x120
	private static DelegateBridge __Hotfix0__CreateConfig; // 0x128
	private static DelegateBridge __Hotfix0_PreloadSingleEffect; // 0x130
	private static DelegateBridge __Hotfix0_TryGetEquipSetting; // 0x138
	private static DelegateBridge __Hotfix0__StartPreloadTask; // 0x140
	private static DelegateBridge _c__Hotfix0_ctor; // 0x148

	private Boolean m_isComplete { get; }

	// RVA: 0x40c0cd0 VA: 0x75966d8cd0
	private Boolean get_m_isComplete() { }
	// RVA: 0x40c0e70 VA: 0x75966d8e70
	public IEnumerator Gather(MonoBehaviour host, BattleAudioLoader audioLoader, LevelData levelData, List`1 playerDataList, AbstractAssetLoader assetLoader, Difficulty difficulty) { }
	// RVA: 0x40c0ff4 VA: 0x75966d8ff4
	private Void _GetOperaPreloadRes(String key, String configPath, List`1 operaAudioList, List`1 operaEffectList) { }
	// RVA: 0x40bfed0 VA: 0x75966d7ed0
	public ObjectConfig[] GetPreloadConfigs() { }
	// RVA: 0x40bffd8 VA: 0x75966d7fd8
	public List`1 GetRuntimeLoadConfigs() { }
	// RVA: 0x40c00f4 VA: 0x75966d80f4
	public static Void GatherEffectsFromBuff(List`1 effects, IBuffSource source) { }
	// RVA: 0x40c1388 VA: 0x75966d9388
	private static Void _GatherEffectsFromBuff(List`1 effects, List`1 buffs) { }
	// RVA: 0x40c14b4 VA: 0x75966d94b4
	private static Void _GatherEffectsFromSingleBuff(List`1 effects, BuffData buffData, Boolean searchInside) { }
	// RVA: 0x40c16bc VA: 0x75966d96bc
	private static Void _GatherEffectsInsideTemplate(List`1 effects, BuffTemplate template) { }
	// RVA: 0x40c0314 VA: 0x75966d8314
	public static Void GatherActionNodesFromBuff(List`1 actions, IBuffSource source) { }
	// RVA: 0x40c1898 VA: 0x75966d9898
	protected static Void GatherActionNodesFromBuff(List`1 actions, BuffData buff) { }
	// RVA: 0x40c19ec VA: 0x75966d99ec
	protected IEnumerator GatherEnemy(EnemyData enemyData, TaskWrapper task) { }
	// RVA: 0x40c1b0c VA: 0x75966d9b0c
	protected IEnumerator GatherCharacter(BattleCharacterData characterData, TaskWrapper task) { }
	// RVA: 0x40c1c2c VA: 0x75966d9c2c
	protected IEnumerator GatherToken(BattleCharacterData characterData, TaskWrapper task) { }
	// RVA: 0x40c1d4c VA: 0x75966d9d4c
	protected IEnumerator GatherSkin(CharSkinData skinData) { }
	// RVA: 0x40c1e54 VA: 0x75966d9e54
	protected Void GatherUniEquip(List`1 settings) { }
	// RVA: 0x40c20e0 VA: 0x75966da0e0
	protected Void GatherExtraEnemyFromTalent(List`1 talentDataList, Int32 mainSkillIndex) { }
	// RVA: 0x40c2a88 VA: 0x75966daa88
	protected IEnumerator GatherSkill(SkillData skillData) { }
	// RVA: 0x40c2b90 VA: 0x75966dab90
	protected IEnumerator GatherSkillRelatedEffectBlacklist(SkillData skillData) { }
	// RVA: 0x40c2c98 VA: 0x75966dac98
	protected IEnumerator GatherEffect(String effectKey, TaskWrapper taskWrapper) { }
	// RVA: 0x40c2db8 VA: 0x75966dadb8
	protected IEnumerator GatherProjectile(String projectileKey, TaskWrapper task) { }
	// RVA: 0x40c2ed8 VA: 0x75966daed8
	protected IEnumerator GatherDynamicAbility(List`1 abilityName, TaskWrapper task) { }
	// RVA: 0x40c2ff8 VA: 0x75966daff8
	protected Void GatherExtraEffects() { }
	// RVA: 0x40c3100 VA: 0x75966db100
	private Void _GatherEpBreakBuffEffects() { }
	// RVA: 0x40c3d0c VA: 0x75966dbd0c
	protected IEnumerator GatherEnvSystem(String envSystemPrefab, TaskWrapper task) { }
	// RVA: 0x40c3e2c VA: 0x75966dbe2c
	protected IEnumerator GatherGlobalBuff(String globalBuffPrefab, TaskWrapper task) { }
	// RVA: 0x40c3f4c VA: 0x75966dbf4c
	protected Void GatherAssetsFromGameMode() { }
	// RVA: 0x40c4668 VA: 0x75966dc668
	protected Void GatherInputAndLevelRunes(LevelData levelData) { }
	// RVA: 0x VA: 0x0
	protected Void GatherAssetsInternal(T obj) { }
	// RVA: 0x40c3460 VA: 0x75966db460
	private Void _GatherEffectsFromBuffsRecursively(Int32 depth, ref List`1 buffList, ref List`1 assetList) { }
	// RVA: 0x40c4a60 VA: 0x75966dca60
	protected Void GatherAssetsInsideEffect(Effect effect) { }
	// RVA: 0x40c1f40 VA: 0x75966d9f40
	protected Void GatherFromEffectSource(IEffectSource source) { }
	// RVA: 0x40c4ba0 VA: 0x75966dcba0
	protected Void GatherFromProjectileSource(IProjectileSource source) { }
	// RVA: 0x40c4d40 VA: 0x75966dcd40
	protected Boolean AppendRes(ObjectConfig config, Boolean alreadyInHashSet, Boolean preload) { }
	// RVA: 0x40c26b8 VA: 0x75966da6b8
	private Void _CreateTask(PreloadType type, Object arg) { }
	// RVA: 0x40c4f4c VA: 0x75966dcf4c
	private static ObjectConfig _CreateConfig(String path, Options options) { }
	// RVA: 0x40c05b0 VA: 0x75966d85b0
	public static Void PreloadSingleEffect(String effect, Boolean allowAutoReuse, Int32 preloadCnt) { }
	// RVA: 0x40c07ec VA: 0x75966d87ec
	public static Boolean TryGetEquipSetting(UniqueEquipPair query, out BattleUniEquipSetting equipSetting) { }
	// RVA: 0x40c504c VA: 0x75966dd04c
	private Void _StartPreloadTask(MonoBehaviour host) { }
	// RVA: 0x40c0a58 VA: 0x75966d8a58
	public Void .ctor() { }
	// RVA: 0x40c51fc VA: 0x75966dd1fc
	private static Void .cctor() { }
	// RVA: 0x40c52e8 VA: 0x75966dd2e8
	private Void <GatherInputAndLevelRunes>b__47_0(RuneData rune) { }
	// RVA: 0x40c549c VA: 0x75966dd49c
	private Void <GatherInputAndLevelRunes>b__47_1(RuneData rune) { }
}
```