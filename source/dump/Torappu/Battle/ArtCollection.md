# ArtCollection

**Namespace:** `Torappu.Battle`


## Fields

- `Sprite _defaultIcon`

- `Image _defaultIllust`

- `Assets m_assetLoader`

- `AutoPackSpriteHub m_avatarHub`

- `AutoPackSpriteHub m_skillIconHub`

- `AutoPackSpriteHub m_enemyIconHub`

- `SpriteHub m_enemyBossHpIconHub`

- `AutoPackSpriteHub m_subPrefessionIconHub`

- `AutoPackSpriteHub m_equipDirectionSpriteHub`

- `Assets m_sharedAssetLoader`


## Properties

- `Assets assetLoader`

- `ILoadAsset sharedAssetLoader`


## Methods

- `Assets get_assetLoader()`

- `ILoadAsset get_sharedAssetLoader()`

- `Sprite GetAvatar(BattleCharacterData)`

- `Sprite GetAvatar(String)`

- `Sprite GetSubProfessionlIcon(String, out)`

- `Sprite GetSkillIcon(ISkillData)`

- `Sprite GetEnemyIcon(String)`

- `Sprite GetEnemyBossHpIcon(String)`

- `Image GetIllust(BattleCharacterData)`

- `Boolean TryGetEquipDirectionSprite(UniEquipData, out)`

- `Sprite GetCampIcon(String)`

- `Sprite LoadEtIcon(String)`

- `Void PreloadIllustrations(BattlePlayerData, LevelData, Difficulty)`

- `GameObject LoadActivityGameObject(String)`

- `GameObject LoadUIBattlePlugin(String)`

- `GameObject LoadBattleMetaUIPlugin(String)`

- `GameObject LoadActivityDependentUIBattlePlugin(String)`

- `RectTransform LoadCardEffectPlugin(String)`

- `SpriteRenderData LoadCharPortrait(String)`

- `Boolean _TryLoadIllust(CharQuery, EvolvePhase, out)`

- `Boolean _TryLoadIllust(BattleCharacterData, out)`

- `Boolean _TryLoadIllust(CharQuery, CharUISkinStruct, out)`

- `Sprite GetContentPictureFunLiveModeOnly(String)`

- `Sprite GetEmojiPictureFunLiveModeOnly(String)`

- `Sprite GetAct5FunNpcIconAct5FunModeOnly(String)`

- `Sprite GetSquadSpecialEffectIconCoopModeOnly(String)`

- `Void Start()`

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Void UnloadAsset(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ArtCollection : SingletonMonoBehaviour`1, ILoadAsset
{
	private Sprite _defaultIcon; // 0x18
	private Image _defaultIllust; // 0x20
	private Assets m_assetLoader; // 0x28
	private AutoPackSpriteHub m_avatarHub; // 0x30
	private AutoPackSpriteHub m_skillIconHub; // 0x38
	private AutoPackSpriteHub m_enemyIconHub; // 0x40
	private SpriteHub m_enemyBossHpIconHub; // 0x48
	private AutoPackSpriteHub m_subPrefessionIconHub; // 0x50
	private AutoPackSpriteHub m_equipDirectionSpriteHub; // 0x58
	private Assets m_sharedAssetLoader; // 0x60
	private readonly Int32 SYSTEM_MEMORY_LIMIT_FOR_BATTLE_ILLUST; // 0x68
	private readonly Int32 SYSTEM_MEMORY_LIMIT_FOR_BATTLE_ILLUST_MULTIPLAYER_ONLY; // 0x6c
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_get_sharedAssetLoader; // 0x8
	private static DelegateBridge __Hotfix0_GetAvatar; // 0x10
	private static DelegateBridge __Hotfix1_GetAvatar; // 0x18
	private static DelegateBridge __Hotfix0_GetSubProfessionlIcon; // 0x20
	private static DelegateBridge __Hotfix0_GetSkillIcon; // 0x28
	private static DelegateBridge __Hotfix0_GetEnemyIcon; // 0x30
	private static DelegateBridge __Hotfix0_GetEnemyBossHpIcon; // 0x38
	private static DelegateBridge __Hotfix0_GetIllust; // 0x40
	private static DelegateBridge __Hotfix0_TryGetEquipDirectionSprite; // 0x48
	private static DelegateBridge __Hotfix0_GetCampIcon; // 0x50
	private static DelegateBridge __Hotfix0_LoadEtIcon; // 0x58
	private static DelegateBridge __Hotfix0__TryLoadSpriteFromAutoPackHub; // 0x60
	private static DelegateBridge __Hotfix0_PreloadIllustrations; // 0x68
	private static DelegateBridge __Hotfix0_LoadActivityGameObject; // 0x70
	private static DelegateBridge __Hotfix0_LoadUIBattlePlugin; // 0x78
	private static DelegateBridge __Hotfix0_LoadBattleMetaUIPlugin; // 0x80
	private static DelegateBridge __Hotfix0_LoadActivityDependentUIBattlePlugin; // 0x88
	private static DelegateBridge __Hotfix0_LoadCardEffectPlugin; // 0x90
	private static DelegateBridge __Hotfix0_LoadCharPortrait; // 0x98
	private static DelegateBridge __Hotfix0__TryLoadIllust; // 0xa0
	private static DelegateBridge __Hotfix1__TryLoadIllust; // 0xa8
	private static DelegateBridge __Hotfix2__TryLoadIllust; // 0xb0
	private static DelegateBridge __Hotfix0_GetContentPictureFunLiveModeOnly; // 0xb8
	private static DelegateBridge __Hotfix0_GetEmojiPictureFunLiveModeOnly; // 0xc0
	private static DelegateBridge __Hotfix0_GetAct5FunNpcIconAct5FunModeOnly; // 0xc8
	private static DelegateBridge __Hotfix0_GetSquadSpecialEffectIconCoopModeOnly; // 0xd0
	private static DelegateBridge __Hotfix0_Start; // 0xd8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0xe8
	private static DelegateBridge __Hotfix1_LoadAsset; // 0xf0
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public Assets assetLoader { get; }
	public ILoadAsset sharedAssetLoader { get; }

	// RVA: 0x3f62538 VA: 0x759657a538
	public Assets get_assetLoader() { }
	// RVA: 0x3f625d0 VA: 0x759657a5d0
	public ILoadAsset get_sharedAssetLoader() { }
	// RVA: 0x3f62670 VA: 0x759657a670
	public Sprite GetAvatar(BattleCharacterData data) { }
	// RVA: 0x3f62704 VA: 0x759657a704
	public Sprite GetAvatar(String avatarId) { }
	// RVA: 0x3f627f0 VA: 0x759657a7f0
	public Sprite GetSubProfessionlIcon(String subProfessionId, out Boolean isDefaultIcon) { }
	// RVA: 0x3f62908 VA: 0x759657a908
	public Sprite GetSkillIcon(ISkillData skillData) { }
	// RVA: 0x3f62a80 VA: 0x759657aa80
	public Sprite GetEnemyIcon(String enemyId) { }
	// RVA: 0x3f62b8c VA: 0x759657ab8c
	public Sprite GetEnemyBossHpIcon(String enemyId) { }
	// RVA: 0x3f62c94 VA: 0x759657ac94
	public Image GetIllust(BattleCharacterData data) { }
	// RVA: 0x3f62e74 VA: 0x759657ae74
	public Boolean TryGetEquipDirectionSprite(UniEquipData data, out Sprite sprite) { }
	// RVA: 0x3f62f94 VA: 0x759657af94
	public Sprite GetCampIcon(String campId) { }
	// RVA: 0x3f630f8 VA: 0x759657b0f8
	public Sprite LoadEtIcon(String iconId) { }
	// RVA: 0x3f6327c VA: 0x759657b27c
	private static Sprite _TryLoadSpriteFromAutoPackHub(String hubPath, String spriteId, Assets loader) { }
	// RVA: 0x3f63398 VA: 0x759657b398
	public Void PreloadIllustrations(BattlePlayerData playerData, LevelData levelData, Difficulty difficulty) { }
	// RVA: 0x3f63698 VA: 0x759657b698
	public GameObject LoadActivityGameObject(String assetId) { }
	// RVA: 0x3f63808 VA: 0x759657b808
	public GameObject LoadUIBattlePlugin(String assetId) { }
	// RVA: 0x3f63908 VA: 0x759657b908
	public GameObject LoadBattleMetaUIPlugin(String assetId) { }
	// RVA: 0x3f63a08 VA: 0x759657ba08
	public GameObject LoadActivityDependentUIBattlePlugin(String activityId) { }
	// RVA: 0x3f63b14 VA: 0x759657bb14
	public RectTransform LoadCardEffectPlugin(String assetId) { }
	// RVA: 0x3f63c74 VA: 0x759657bc74
	public SpriteRenderData LoadCharPortrait(String portraitId) { }
	// RVA: 0x3f63578 VA: 0x759657b578
	private Boolean _TryLoadIllust(CharQuery charQuery, EvolvePhase evolvePhase, out Image illust) { }
	// RVA: 0x3f62d2c VA: 0x759657ad2c
	private Boolean _TryLoadIllust(BattleCharacterData charData, out Image illust) { }
	// RVA: 0x3f63f44 VA: 0x759657bf44
	private Boolean _TryLoadIllust(CharQuery charQuery, CharUISkinStruct skin, out Image illust) { }
	// RVA: 0x3f64260 VA: 0x759657c260
	public Sprite GetContentPictureFunLiveModeOnly(String picId) { }
	// RVA: 0x3f64388 VA: 0x759657c388
	public Sprite GetEmojiPictureFunLiveModeOnly(String emojiId) { }
	// RVA: 0x3f644b0 VA: 0x759657c4b0
	public Sprite GetAct5FunNpcIconAct5FunModeOnly(String npcId) { }
	// RVA: 0x3f645d8 VA: 0x759657c5d8
	public Sprite GetSquadSpecialEffectIconCoopModeOnly(String iconId) { }
	// RVA: 0x3f64668 VA: 0x759657c668
	private Void Start() { }
	// RVA: 0x3f64844 VA: 0x759657c844
	protected override Void OnDestroy() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x3f64918 VA: 0x759657c918
	public Object LoadAsset(String path) { }
	// RVA: 0x3f649bc VA: 0x759657c9bc
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x3f64a4c VA: 0x759657ca4c
	public Void .ctor() { }
}
```