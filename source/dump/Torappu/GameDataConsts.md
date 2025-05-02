# GameDataConsts

**Namespace:** `Torappu`


## Fields

- `Int32 maxPlayerLevel`

- `Single completeGainBonus`

- `Int32 playerApRegenSpeed`

- `Int32 maxPracticeTicket`

- `Int32 advancedGachaCrystalCost`

- `Int32 completeCrystalBonus`

- `Int32 initPlayerGold`

- `Int32 initPlayerDiamondShard`

- `Int32 initCampaignTotalFee`

- `Single attackMax`

- `Single defMax`

- `Single hpMax`

- `Single reMax`

- `Int32 diamondToShdRate`

- `Int32 requestSameFriendCD`

- `Int32 baseMaxFriendNum`

- `Int32 hardDiamondDrop`

- `Int32 instFinDmdShdCost`

- `Int32 easyCrystalBonus`

- `Int32 diamondMaterialToShardExchangeRatio`

- `Int32 diamondHandbookStageGain`

- `Int32 apBuyCost`

- `Int32 apBuyThreshold`

- `Int32 creditLimit`

- `Int32 monthlySubRemainTimeLimitDays`

- `String mainlineCompatibleDesc`

- `String mainlineToughDesc`

- `String mainlineEasyDesc`

- `String mainlineNormalDesc`

- `Int64 rejectSpCharMission`

- `String addedRewardDisplayZone`

- `Int32 oneDiamondAp`

- `Int32 charRotationPresetMaxCnt`

- `Int32 charRotationSkinListMaxCnt`

- `String defaultCRPresetCharId`

- `String defaultCRPresetCharSkinId`

- `String defaultCRPresetBGId`

- `String defaultCRPresetThemeId`

- `String defaultCRPresetName`

- `Int64 charRotationPresetTrackTs`

- `Int64 uniequipArchiveSysTrackTs`

- `Int32 manufactPromptTime`

- `String mainGuideActivedStageId`

- `Int32 commonPotentialLvlUpCount`

- `String weeklyOverrideDesc`

- `Int32 voucherDiv`

- `Int32 recruitPoolVersion`

- `Int64 v006RecruitTimeStep1Refresh`

- `Int64 v006RecruitTimeStep2Check`

- `Int64 v006RecruitTimeStep2Flush`

- `Boolean buyApTimeNoLimitFlag`

- `Boolean isLMGTSEnabled`

- `Int64 legacyTime`

- `Int32 useAssistSocialPt`

- `Int32 useAssistSocialPtMaxCount`

- `Int32 pushForceZeroIndex`

- `Int32 pullForceZeroIndex`

- `Int32 LMTGSToEPGSRatio`

- `Int32 newBeeGiftEPGS`

- `String lMTGSDescConstOne`

- `String lMTGSDescConstTwo`

- `String defCDPrimColor`

- `String defCDSecColor`

- `Int64 monthlySubWarningTime`

- `Int64 UnlimitSkinOutOfTime`

- `Int64 replicateShopStartTime`

- `Int64 operatorRecordsStartTime`

- `Boolean isDynIllustEnabled`

- `Boolean isDynIllustStartEnabled`

- `Boolean isClassicQCShopEnabled`

- `Boolean isRoguelikeTopicFuncEnabled`

- `Boolean isSandboxPermFuncEnabled`

- `Boolean isRoguelikeAvgAchieveFuncEnabled`

- `Boolean isClassicPotentialItemFuncEnabled`

- `Boolean isClassicGachaPoolFuncEnabled`

- `Boolean isSpecialGachaPoolFuncEnabled`

- `Boolean isVoucherClassicItemDistinguishable`

- `Int32 voucherSkinRedeem`

- `String voucherSkinDesc`

- `Int32 charmEquipCount`

- `String storyReviewUnlockItemLackTip`

- `String dataVersion`

- `String resPrefVersion`

- `String announceWebBusType`

- `String videoPlayerWebBusType`

- `String gachaLogBusType`

- `Int32 defaultMinContinuousBattleTimes`

- `Int32 defaultMaxContinuousBattleTimes`

- `Boolean continuousActionOpen`

- `String birthdaySettingDesc`

- `String birthdaySettingConfirmDesc`

- `String birthdaySettingLeapConfirmDesc`

- `Int32 leapBirthdayRewardMonth`

- `Int32 leapBirthdayRewardDay`

- `String birthdaySettingShowStageId`

- `Boolean isBirthdayFuncEnabled`


## Methods

- `Boolean ShouldSerializeisDynIllustStartEnabled()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GameDataConsts
{
	public Int32 maxPlayerLevel; // 0x10
	public Int32[] playerExpMap; // 0x18
	public Int32[] playerApMap; // 0x20
	public Int32[][] maxLevel; // 0x28
	public Int32[][] characterExpMap; // 0x30
	public Int32[][] characterUpgradeCostMap; // 0x38
	public Int32[][] evolveGoldCost; // 0x40
	public Single completeGainBonus; // 0x48
	public Int32 playerApRegenSpeed; // 0x4c
	public Int32 maxPracticeTicket; // 0x50
	public Int32 advancedGachaCrystalCost; // 0x54
	public Int32 completeCrystalBonus; // 0x58
	public Int32 initPlayerGold; // 0x5c
	public Int32 initPlayerDiamondShard; // 0x60
	public Int32 initCampaignTotalFee; // 0x64
	public Int32[] initRecruitTagList; // 0x68
	public String[] initCharIdList; // 0x70
	public Single attackMax; // 0x78
	public Single defMax; // 0x7c
	public Single hpMax; // 0x80
	public Single reMax; // 0x84
	public Int32 diamondToShdRate; // 0x88
	public Int32 requestSameFriendCD; // 0x8c
	public Int32 baseMaxFriendNum; // 0x90
	public Int32 hardDiamondDrop; // 0x94
	public Int32 instFinDmdShdCost; // 0x98
	public Int32 easyCrystalBonus; // 0x9c
	public Int32 diamondMaterialToShardExchangeRatio; // 0xa0
	public Int32 diamondHandbookStageGain; // 0xa4
	public Int32 apBuyCost; // 0xa8
	public Int32 apBuyThreshold; // 0xac
	public Int32 creditLimit; // 0xb0
	public Int32 monthlySubRemainTimeLimitDays; // 0xb4
	public List`1 friendAssistRarityLimit; // 0xb8
	public String mainlineCompatibleDesc; // 0xc0
	public String mainlineToughDesc; // 0xc8
	public String mainlineEasyDesc; // 0xd0
	public String mainlineNormalDesc; // 0xd8
	public Int64 rejectSpCharMission; // 0xe0
	public String addedRewardDisplayZone; // 0xe8
	public Int32 oneDiamondAp; // 0xf0
	public Int32 charRotationPresetMaxCnt; // 0xf4
	public Int32 charRotationSkinListMaxCnt; // 0xf8
	public String defaultCRPresetCharId; // 0x100
	public String defaultCRPresetCharSkinId; // 0x108
	public String defaultCRPresetBGId; // 0x110
	public String defaultCRPresetThemeId; // 0x118
	public String defaultCRPresetName; // 0x120
	public Int64 charRotationPresetTrackTs; // 0x128
	public Int64 uniequipArchiveSysTrackTs; // 0x130
	public Int32 manufactPromptTime; // 0x138
	public String mainGuideActivedStageId; // 0x140
	public Dictionary`2 richTextStyles; // 0x148
	public List`1 charAssistRefreshTime; // 0x150
	public List`1 normalRecruitLockedString; // 0x158
	public Int32 commonPotentialLvlUpCount; // 0x160
	public String weeklyOverrideDesc; // 0x168
	public Int32 voucherDiv; // 0x170
	public Int32 recruitPoolVersion; // 0x174
	public Int64 v006RecruitTimeStep1Refresh; // 0x178
	public Int64 v006RecruitTimeStep2Check; // 0x180
	public Int64 v006RecruitTimeStep2Flush; // 0x188
	public Boolean buyApTimeNoLimitFlag; // 0x190
	public Boolean isLMGTSEnabled; // 0x191
	public Int64 legacyTime; // 0x198
	public ItemBundle[] legacyItemList; // 0x1a0
	public Int32 useAssistSocialPt; // 0x1a8
	public Int32 useAssistSocialPtMaxCount; // 0x1ac
	public ListDict`2 assistBeUsedSocialPt; // 0x1b0
	public Single[] pushForces; // 0x1b8
	public Int32 pushForceZeroIndex; // 0x1c0
	public Int32[] normalGachaUnlockPrice; // 0x1c8
	public Single[] pullForces; // 0x1d0
	public Int32 pullForceZeroIndex; // 0x1d8
	public String[] multiInComeByRank; // 0x1e0
	public Int32 LMTGSToEPGSRatio; // 0x1e8
	public Int32 newBeeGiftEPGS; // 0x1ec
	public String lMTGSDescConstOne; // 0x1f0
	public String lMTGSDescConstTwo; // 0x1f8
	public String defCDPrimColor; // 0x200
	public String defCDSecColor; // 0x208
	public List`1 mailBannerType; // 0x210
	public Int64 monthlySubWarningTime; // 0x218
	public Int64 UnlimitSkinOutOfTime; // 0x220
	public Int64 replicateShopStartTime; // 0x228
	public Int64 operatorRecordsStartTime; // 0x230
	public Boolean isDynIllustEnabled; // 0x238
	public Boolean isDynIllustStartEnabled; // 0x239
	public Boolean isClassicQCShopEnabled; // 0x23a
	public Boolean isRoguelikeTopicFuncEnabled; // 0x23b
	public Boolean isSandboxPermFuncEnabled; // 0x23c
	public Boolean isRoguelikeAvgAchieveFuncEnabled; // 0x23d
	public Boolean isClassicPotentialItemFuncEnabled; // 0x23e
	public Boolean isClassicGachaPoolFuncEnabled; // 0x23f
	public Boolean isSpecialGachaPoolFuncEnabled; // 0x240
	public Boolean isVoucherClassicItemDistinguishable; // 0x241
	public Int32 voucherSkinRedeem; // 0x244
	public String voucherSkinDesc; // 0x248
	public Int32 charmEquipCount; // 0x250
	public Dictionary`2 termDescriptionDict; // 0x258
	public String storyReviewUnlockItemLackTip; // 0x260
	public String dataVersion; // 0x268
	public String resPrefVersion; // 0x270
	public String announceWebBusType; // 0x278
	public String videoPlayerWebBusType; // 0x280
	public String gachaLogBusType; // 0x288
	public Int32 defaultMinContinuousBattleTimes; // 0x290
	public Int32 defaultMaxContinuousBattleTimes; // 0x294
	public Boolean continuousActionOpen; // 0x298
	public Dictionary`2 subProfessionDamageTypePairs; // 0x2a0
	public List`1 classicProtectChar; // 0x2a8
	public String birthdaySettingDesc; // 0x2b0
	public String birthdaySettingConfirmDesc; // 0x2b8
	public String birthdaySettingLeapConfirmDesc; // 0x2c0
	public Int32 leapBirthdayRewardMonth; // 0x2c8
	public Int32 leapBirthdayRewardDay; // 0x2cc
	public String birthdaySettingShowStageId; // 0x2d0
	public Boolean isBirthdayFuncEnabled; // 0x2d8


	// RVA: 0x34a2b98 VA: 0x7595abab98
	public Boolean ShouldSerializeisDynIllustStartEnabled() { }
	// RVA: 0x34a2ba0 VA: 0x7595ababa0
	public Void .ctor() { }
}
```