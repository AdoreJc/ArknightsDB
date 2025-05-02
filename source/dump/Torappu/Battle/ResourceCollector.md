# ResourceCollector

**Namespace:** `Torappu.Battle`


## Fields

- `BattleAudioLoader _audioLoader`

- `ResourceCollectHandler m_handler`


## Properties

- `BattleAudioLoader audioLoader`


## Methods

- `BattleAudioLoader get_audioLoader()`

- `IEnumerator Gather(LevelData, List`1, AbstractAssetLoader, Difficulty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ResourceCollector : MonoBehaviour, IHotfixable
{
	public const Int32 EFFECT_PRELOAD_DEFAULT_CNT; // 0x0
	public const Int32 ENEMY_PRELOAD_CNT; // 0x0
	private String[] _extraEffects; // 0x18
	private BattleAudioLoader _audioLoader; // 0x20
	private ResourceCollectHandler m_handler; // 0x28
	private static DelegateBridge __Hotfix0_get_audioLoader; // 0x0
	private static DelegateBridge __Hotfix0_Gather; // 0x8
	private static DelegateBridge __Hotfix0_GetPreloadConfigs; // 0x10
	private static DelegateBridge __Hotfix0_GetRuntimeLoadConfigs; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffectsFromBuff; // 0x20
	private static DelegateBridge __Hotfix0_GatherActionNodesFromBuff; // 0x28
	private static DelegateBridge __Hotfix0_PreloadSingleEffect; // 0x30
	private static DelegateBridge __Hotfix0_TryGetEquipSetting; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public BattleAudioLoader audioLoader { get; }

	// RVA: 0x40bfcb8 VA: 0x75966d7cb8
	public BattleAudioLoader get_audioLoader() { }
	// RVA: 0x40bfd20 VA: 0x75966d7d20
	public IEnumerator Gather(LevelData levelData, List`1 playerDataList, AbstractAssetLoader assetLoader, Difficulty difficulty) { }
	// RVA: 0x40bfe60 VA: 0x75966d7e60
	public ObjectConfig[] GetPreloadConfigs() { }
	// RVA: 0x40bff68 VA: 0x75966d7f68
	public List`1 GetRuntimeLoadConfigs() { }
	// RVA: 0x40c0050 VA: 0x75966d8050
	public static Void GatherEffectsFromBuff(List`1 effects, IBuffSource source) { }
	// RVA: 0x40c0270 VA: 0x75966d8270
	public static Void GatherActionNodesFromBuff(List`1 actions, IBuffSource source) { }
	// RVA: 0x40c0500 VA: 0x75966d8500
	public static Void PreloadSingleEffect(String effect, Boolean allowAutoReuse, Int32 preloadCnt) { }
	// RVA: 0x40c073c VA: 0x75966d873c
	public static Boolean TryGetEquipSetting(UniqueEquipPair query, out BattleUniEquipSetting equipSetting) { }
	// RVA: 0x40c09ac VA: 0x75966d89ac
	public Void .ctor() { }
}
```