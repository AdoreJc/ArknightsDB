# PlayerDataModel

**Namespace:** `Torappu`


## Fields

- `PlayerEvents events`

- `PlayerPushFlags pushFlags`

- `PlayerStatus status`

- `PlayerTroop troop`

- `PlayerDungeon dungeon`

- `PlayerCheckIn checkIn`

- `PlayerOpenServer openServer`

- `PlayerActivity activity`

- `PlayerTemplateTrap templateTrap`

- `PlayerRetro retro`

- `PlayerDexNav dexNav`

- `PlayerSkins skin`

- `PlayerMedal medal`

- `PlayerAvatar PlayerAvatar`

- `PlayerCollection collectionReward`

- `PlayerEquipment equipment`

- `PlayerShop shop`

- `PlayerRecruit recruit`

- `PlayerCarousel carousel`

- `PlayerGacha gacha`

- `PlayerSocial social`

- `MissionPlayerData mission`

- `PlayerBuilding building`

- `PlayerCrisis crisis`

- `PlayerCrisisV2 crisisV2`

- `PlayerStoryReview storyreview`

- `PlayerRoguelike roguelike`

- `PlayerRoguelikeV2 rlv2`

- `PlayerReturnData backflow`

- `PlayerCampaign campaign`

- `CharmStatus charm`

- `PlayerDeepSea deepSea`

- `PlayerCartInfo car`

- `PlayerTower tower`

- `PlayerSiracusaMap siracusaMap`

- `PlayerFirework firework`

- `PlayerSandboxPerm sandboxPerm`

- `PlayerEmoticon emoticon`

- `PlayerCrossAppShare share`

- `PlayerTrainingCamp trainingGround`

- `PlayerHomeBackground playerHomeBackground`

- `PlayerHomeTheme playerHomeTheme`

- `PlayerNameCardStyle playerNameCardStyle`

- `PlayerSetting playerSetting`

- `PlayerAprilFool playerAprilFool`

- `PlayerCharRotation charRotation`

- `PlayerMainlineRecord playerMainlineRecord`

- `PlayerLimitedDropBuff limitedBuff`

- `PlayerPerformanceStory performanceStory`


## Methods

- `String Serialize()`

- `Boolean HasFlag(String)`

- `Boolean HasVariantStoryUnlocked(String)`

- `PlayerDataModel ShallowClone()`

- `Boolean TryGetStageStateForAVGTrigger(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerDataModel
{
	public const String ACTIVITY_FIELD; // 0x0
	public const String SANDBOX_PERM_FIELD; // 0x0
	public const String SANDBOX_PERM_TEMPLATE_FIELD; // 0x0
	public PlayerEvents events; // 0x10
	public PlayerPushFlags pushFlags; // 0x18
	public PlayerStatus status; // 0x20
	public Dictionary`2 monthlySub; // 0x28
	public PlayerTroop troop; // 0x30
	public PlayerDungeon dungeon; // 0x38
	public PlayerCheckIn checkIn; // 0x40
	public PlayerOpenServer openServer; // 0x48
	public PlayerActivity activity; // 0x50
	public PlayerTemplateTrap templateTrap; // 0x58
	public PlayerRetro retro; // 0x60
	public PlayerDexNav dexNav; // 0x68
	public PlayerSkins skin; // 0x70
	public PlayerMedal medal; // 0x78
	public PlayerAvatar PlayerAvatar; // 0x80
	public PlayerCollection collectionReward; // 0x88
	public PlayerEquipment equipment; // 0x90
	public Dictionary`2 inventory; // 0x98
	public Dictionary`2 consumable; // 0xa0
	public Dictionary`2 ticket; // 0xa8
	public PlayerShop shop; // 0xb0
	public Dictionary`2 tshop; // 0xb8
	public PlayerRecruit recruit; // 0xc0
	public PlayerCarousel carousel; // 0xc8
	public PlayerGacha gacha; // 0xd0
	public PlayerSocial social; // 0xd8
	public MissionPlayerData mission; // 0xe0
	public PlayerBuilding building; // 0xe8
	public PlayerCrisis crisis; // 0xf0
	public PlayerCrisisV2 crisisV2; // 0xf8
	public PlayerStoryReview storyreview; // 0x100
	public PlayerRoguelike roguelike; // 0x108
	public PlayerRoguelikeV2 rlv2; // 0x110
	public PlayerReturnData backflow; // 0x118
	public PlayerCampaign campaign; // 0x120
	public CharmStatus charm; // 0x128
	public PlayerDeepSea deepSea; // 0x130
	public PlayerCartInfo car; // 0x138
	public PlayerTower tower; // 0x140
	public PlayerSiracusaMap siracusaMap; // 0x148
	public PlayerFirework firework; // 0x150
	public PlayerSandboxPerm sandboxPerm; // 0x158
	public PlayerEmoticon emoticon; // 0x160
	public PlayerCrossAppShare share; // 0x168
	public PlayerTrainingCamp trainingGround; // 0x170
	public PlayerHomeBackground playerHomeBackground; // 0x178
	public PlayerHomeTheme playerHomeTheme; // 0x180
	public PlayerNameCardStyle playerNameCardStyle; // 0x188
	public PlayerSetting playerSetting; // 0x190
	public PlayerAprilFool playerAprilFool; // 0x198
	public Dictionary`2 npcAudio; // 0x1a0
	public PlayerCharRotation charRotation; // 0x1a8
	public PlayerMainlineRecord playerMainlineRecord; // 0x1b0
	public PlayerLimitedDropBuff limitedBuff; // 0x1b8
	public PlayerPerformanceStory performanceStory; // 0x1c0


	// RVA: 0x33afb5c VA: 0x75959c7b5c
	public String Serialize() { }
	// RVA: 0x33afc7c VA: 0x75959c7c7c
	public Boolean HasFlag(String flag) { }
	// RVA: 0x33afcfc VA: 0x75959c7cfc
	public Boolean HasVariantStoryUnlocked(String storyId) { }
	// RVA: 0x33afd68 VA: 0x75959c7d68
	public PlayerDataModel ShallowClone() { }
	// RVA: 0x33afdec VA: 0x75959c7dec
	public Boolean TryGetStageStateForAVGTrigger(String stageId, out PlayerStageState state) { }
	// RVA: 0x33afec4 VA: 0x75959c7ec4
	public Void .ctor() { }
}
```