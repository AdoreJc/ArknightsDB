# VcConfig

**Namespace:** `Torappu`


## Fields

- `String controlVersion`

- `Boolean isLimitedGachaBanned`

- `Boolean isSiracusaMapBanned`

- `Boolean isVecBreakBanned`

- `Boolean isActMultiV3Banned`

- `Boolean isEnemyDuelBanned`

- `Boolean isRoguelikeTopicBanned`

- `Boolean isRoguelikeTopicChallengeModeBanned`

- `Boolean isSandboxPermBanned`

- `Boolean isSandboxV2Banned`

- `Boolean isDeepSeaRPBanned`

- `Boolean isCampSweepBanned`

- `Boolean isClassicGachaBanned`

- `Boolean isSpecialGachaBanned`

- `Boolean isGachaLogEntryBanned`

- `Boolean isRhineAreaResearchBanned`

- `Boolean isGroceryBanned`

- `Boolean isTuningBanned`

- `Boolean isCrisisV2Banned`

- `Boolean isCarvingBanned`

- `Boolean isFireworkBanned`

- `String targetPreMainMovie`

- `Boolean isDynAvatarBanned`


## Methods

- `Void AddAll(VcConfig)`

- `Void _AddRangeSafe(ref, List`1)`

- `Void _MergeStringConfig(ref, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class VcConfig
{
	public const String ACTFUN_COMMON_ID; // 0x0
	public String controlVersion; // 0x10
	public List`1 bannedCharIds; // 0x18
	public List`1 bannedStageIds; // 0x20
	public List`1 bannedItemIds; // 0x28
	public List`1 bannedSkinIds; // 0x30
	public List`1 bannedFurnIds; // 0x38
	public List`1 bannedFurniSetIds; // 0x40
	public List`1 bannedActIds; // 0x48
	public List`1 bannedEnemyIds; // 0x50
	public List`1 bannedGachaPoolIds; // 0x58
	public List`1 bannedShopRecommendTags; // 0x60
	public List`1 bannedShopCarousels; // 0x68
	public List`1 bannedShopFurnPackages; // 0x70
	public List`1 bannedShopFurnPackageIcons; // 0x78
	public List`1 bannedShopGiftPackages; // 0x80
	public List`1 bannedMonthlySubGroupId; // 0x88
	public List`1 bannedMainMissionEndImageId; // 0x90
	public List`1 bannedZoneIds; // 0x98
	public List`1 bannedChapterIds; // 0xa0
	public List`1 bannedCrisisSeasonId; // 0xa8
	public List`1 bannedCrisisV2SeasonId; // 0xb0
	public List`1 bannedCrisisV2StageLogoId; // 0xb8
	public List`1 bannedCrisisV2MapAreaBkgId; // 0xc0
	public List`1 bannedMultiV3SquadEffectIcons; // 0xc8
	public List`1 bannedMultiV3ModeIcons; // 0xd0
	public List`1 bannedMultiV3StagePreviewIcons; // 0xd8
	public List`1 bannedCrisisStageId; // 0xe0
	public List`1 bannedCrisisTrainingRotateId; // 0xe8
	public List`1 bannedMusicFolders; // 0xf0
	public List`1 bannedHandbookTeamIds; // 0xf8
	public List`1 bannedMedalIds; // 0x100
	public List`1 bannedMedalGroupIds; // 0x108
	public List`1 bannedStoryReviewIds; // 0x110
	public List`1 bannedMiniActTrialIds; // 0x118
	public List`1 bannedCampaignRegionIds; // 0x120
	public List`1 bannedCampaignRotateGroupIds; // 0x128
	public List`1 bannedCampaignTrainingGroupIds; // 0x130
	public List`1 bannedCampaignTrainingAllOpenGroupIds; // 0x138
	public List`1 bannedHandbookForceIds; // 0x140
	public List`1 bannedBattleMapRes; // 0x148
	public List`1 bannedSpecialEffectPrefix; // 0x150
	public List`1 bannedSpecialPlayerAudio; // 0x158
	public List`1 bannedTileKey; // 0x160
	public List`1 bannedTokenIds; // 0x168
	public List`1 bannedSkinResNames; // 0x170
	public List`1 bannedLevelIds; // 0x178
	public List`1 bannedLevelReplaceIds; // 0x180
	public List`1 bannedVoucherItemPic; // 0x188
	public List`1 bannedOptionalVoucherBgDecPic; // 0x190
	public List`1 bannedLMGTSBarType; // 0x198
	public List`1 bannedBuildingSkillIcons; // 0x1a0
	public List`1 bannedSkinGroupIds; // 0x1a8
	public List`1 bannedBrandIds; // 0x1b0
	public List`1 bannedKVImgIds; // 0x1b8
	public List`1 bannedStoryIds; // 0x1c0
	public List`1 bannedCharLogo; // 0x1c8
	public List`1 bannedRuneIcons; // 0x1d0
	public List`1 bannedAudioAssets; // 0x1d8
	public List`1 bannedLoadingPics; // 0x1e0
	public List`1 bannedCampaignWorldMapIds; // 0x1e8
	public List`1 bannedHandBookStorySetId; // 0x1f0
	public List`1 bannedHandBookStageId; // 0x1f8
	public List`1 bannedRetroIds; // 0x200
	public List`1 bannedRetroTrailIds; // 0x208
	public List`1 bannedTermDescId; // 0x210
	public List`1 bannedArchiveMusicIds; // 0x218
	public List`1 bannedArchivePicIds; // 0x220
	public List`1 bannedArchiveStoryIds; // 0x228
	public List`1 bannedArchiveAvgIds; // 0x230
	public List`1 bannedArchiveNewsIds; // 0x238
	public List`1 bannedActEntryKVIds; // 0x240
	public List`1 bannedDynActEntryIds; // 0x248
	public List`1 bannedRhineCollectionItemIconIds; // 0x250
	public List`1 bannedActMainlineBuffDynImgIds; // 0x258
	public List`1 bannedActMainlineBpDynImgIds; // 0x260
	public List`1 bannedMixStoryArtSprites; // 0x268
	public Boolean isLimitedGachaBanned; // 0x270
	public List`1 retroRelatedActIds; // 0x278
	public List`1 bannedSubProfIcon; // 0x280
	public List`1 bannedSubProfType; // 0x288
	public List`1 bannedUniEquipId; // 0x290
	public List`1 bannedVoiceLangJP; // 0x298
	public List`1 bannedVoiceLangCN; // 0x2a0
	public List`1 bannedVoiceLangEN; // 0x2a8
	public List`1 bannedVoiceLangKR; // 0x2b0
	public List`1 bannedVoiceLangCustom; // 0x2b8
	public List`1 bannedTimelyDropInfo; // 0x2c0
	public List`1 bannedHomeBackground; // 0x2c8
	public List`1 bannedHomeBackgroundLimit; // 0x2d0
	public List`1 bannedWSBonusIcon; // 0x2d8
	public List`1 bannedReturnV2MissionGroupImage; // 0x2e0
	public List`1 bannedReturnV2MissionGroupIcon; // 0x2e8
	public List`1 bannedMailSenderAvatarIcon; // 0x2f0
	public Boolean isSiracusaMapBanned; // 0x2f8
	public Boolean isVecBreakBanned; // 0x2f9
	public Boolean isActMultiV3Banned; // 0x2fa
	public Boolean isEnemyDuelBanned; // 0x2fb
	public Boolean isRoguelikeTopicBanned; // 0x2fc
	public Boolean isRoguelikeTopicChallengeModeBanned; // 0x2fd
	public List`1 bannedRoguelikeItem; // 0x300
	public List`1 bannedRoguelikeRecruitGroup; // 0x308
	public List`1 bannedRoguelikeMonthSquadRecord; // 0x310
	public List`1 bannedRoguelikeInitRelic; // 0x318
	public List`1 bannedRoguelikeCapsule; // 0x320
	public List`1 bannedRoguelikeTopicVariation; // 0x328
	public List`1 bannedRoguelikeTopicCharBuffIcon; // 0x330
	public List`1 bannedRoguelikeChallenge; // 0x338
	public List`1 bannedRoguelikeChallengeModeTopic; // 0x340
	public List`1 bannedRoguelikeHomeEntry; // 0x348
	public List`1 bannedRoguelikeTopic; // 0x350
	public List`1 bannedRoguelikeBPRewardPic; // 0x358
	public List`1 bannedRoguelikeArchivePicKV; // 0x360
	public List`1 bannedRoguelikeArchiveAvgIllust; // 0x368
	public List`1 bannedRoguelikeArchiveEndbookBgBlur; // 0x370
	public List`1 bannedRoguelikeArchiveEndbookCard; // 0x378
	public List`1 bannedRoguelikeArchiveMusicIcon; // 0x380
	public List`1 bannedRoguelikeMenuDifficultyIcon; // 0x388
	public List`1 bannedRoguelikeEndingStatsIcon; // 0x390
	public List`1 bannedRoguelikeBossNodeIcon; // 0x398
	public List`1 bannedRoguelikeBandEndingCompletetionIcon; // 0x3a0
	public List`1 bannedRoguelikeGameEndBg; // 0x3a8
	public List`1 bannedRoguelikeLevelBgPic; // 0x3b0
	public List`1 bannedRoguelikeScrollReportIcon; // 0x3b8
	public List`1 bannedRoguelikeZoneImage; // 0x3c0
	public List`1 bannedRoguelikeZoneTransitionBg; // 0x3c8
	public List`1 bannedHomeThemeId; // 0x3d0
	public List`1 bannedRoguelikeCommonOuterBuffIcons; // 0x3d8
	public List`1 bannedRoguelikeCommonOuterBuffDeco; // 0x3e0
	public List`1 bannedRoguelikeCommonOuterBuffLight; // 0x3e8
	public List`1 bannedRoguelikeActivity; // 0x3f0
	public Boolean isSandboxPermBanned; // 0x3f8
	public Boolean isSandboxV2Banned; // 0x3f9
	public List`1 bannedSandboxItemList; // 0x400
	public List`1 bannedSandboxEntryList; // 0x408
	public List`1 bannedSandboxV2List; // 0x410
	public List`1 bannedAVGCGs; // 0x418
	public List`1 bannedDynamicOnlySkin; // 0x420
	public List`1 bannedTowerIds; // 0x428
	public List`1 bannedTowerSeasonIds; // 0x430
	public List`1 bannedTowerGodCardIds; // 0x438
	public List`1 bannedGuidebooks; // 0x440
	public List`1 bannedPlayerAvatarIds; // 0x448
	public Boolean isDeepSeaRPBanned; // 0x450
	public List`1 bannedDeepSeaRPPic; // 0x458
	public List`1 bannedDeepSeaRPSpecialPic; // 0x460
	public List`1 voiceBasicChars; // 0x468
	public List`1 validActfunActs; // 0x470
	public Boolean isCampSweepBanned; // 0x478
	public Boolean isClassicGachaBanned; // 0x479
	public Boolean isSpecialGachaBanned; // 0x47a
	public Boolean isGachaLogEntryBanned; // 0x47b
	public Boolean isRhineAreaResearchBanned; // 0x47c
	public Boolean isGroceryBanned; // 0x47d
	public Boolean isTuningBanned; // 0x47e
	public Boolean isCrisisV2Banned; // 0x47f
	public List`1 bannedNameCardSkinIds; // 0x480
	public List`1 bannedNameCardModuleIds; // 0x488
	public List`1 bannedEmoticonThemeIds; // 0x490
	public List`1 bannedEmoticonEmojiPicIds; // 0x498
	public List`1 bannedMissionArchiveTopics; // 0x4a0
	public List`1 bannedTrainingCampStageIconIds; // 0x4a8
	public Boolean isCarvingBanned; // 0x4b0
	public Boolean isFireworkBanned; // 0x4b1
	public List`1 bannedShopGPTabIds; // 0x4b8
	public List`1 bannedShopGPTabIconIds; // 0x4c0
	public List`1 bannedShopGPTabMarkerIds; // 0x4c8
	public List`1 InUseHotUpdateMetaVideoIds; // 0x4d0
	public List`1 bannedHotUpdateMetaVideoIds; // 0x4d8
	public List`1 bannedHotUpdateMetaPicIds; // 0x4e0
	public List`1 bannedHotUpdateMetaPicIconIds; // 0x4e8
	public List`1 bannedBuildingEmojiIds; // 0x4f0
	public List`1 bannedMetaUIIds; // 0x4f8
	public String targetPreMainMovie; // 0x500
	public Boolean isDynAvatarBanned; // 0x508
	public List`1 bannedDynAvatarIds; // 0x510


	// RVA: 0x34fe94c VA: 0x7595b1694c
	public Void AddAll(VcConfig other) { }
	// RVA: 0x VA: 0x0
	private Void _AddRangeSafe(ref List`1 assignTo, List`1 assignFrom) { }
	// RVA: 0x34ff530 VA: 0x7595b17530
	private Void _MergeStringConfig(ref String assignTo, String assignFrom) { }
	// RVA: 0x34ff584 VA: 0x7595b17584
	public Void .ctor() { }
}
```