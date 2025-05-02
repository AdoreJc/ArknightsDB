# StageViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `LocalCache m_localCache`

- `String id`

- `String levelId`

- `String zoneId`

- `String stageCode`

- `String stageName`

- `LazyRichTextFromData stageDescRichText`

- `String hardStageId`

- `String sixStarStageId`

- `String dangerDesc`

- `StageType stageType`

- `StageDiffGroup stageDiffGroup`

- `StageDiffGroupTable diffGroupTable`

- `String normalDiffGroupStageId`

- `Boolean isActivity`

- `Boolean isCampaign`

- `Boolean isMainProgress`

- `String mainRewardItem`

- `String rewardCharId`

- `Boolean hasBoss`

- `Boolean isHilighted`

- `Boolean isCharacterPredefined`

- `Boolean isHardStageCharacterPredefined`

- `Boolean isStoryOnly`

- `Boolean isTraining`

- `AppearanceStyle appearanceStyle`

- `String timelyDropActiveFlag`

- `Boolean showApProtect`

- `Boolean canContinuousBattle`

- `Int32 apCost`

- `Int32 ptCost`

- `Int32 etCost`

- `String etItemId`

- `Boolean isUsingEt`

- `String etStartBattleStyle`

- `StageBattleDiffGroupInfo battleDiffGroupInfo`

- `OverrideDropInfo overrideDropInfo`

- `Boolean isUnlocked`

- `PlayerStageState stageState`

- `Difficulty stageDifficulty`

- `SpecialStageHandler m_specialStageHandler`

- `Boolean m_canPractice`

- `Boolean m_hasAutoBattleLog`

- `Boolean m_canBattleReplay`

- `Int32 m_continuousBattleTimes`

- `Boolean isRecentAutoBattle`

- `Int32 noCostCnt`

- `Int32 slProgress`

- `Boolean isSkillSelectablePredefined`

- `Boolean hasZoneRecordMission`

- `Boolean isZoneRecordMissionComplete`

- `String zoneRecordMissionDesc`

- `LazyReplayStoryInfo m_lazyReplayStoryInfo`

- `Boolean isStagePatch`

- `StageButtonInFogRenderType <stageButtonInFogRenderType>k__BackingField`


## Properties

- `LocalCache localCache`

- `Int32 apCostGroup`

- `Boolean canAutoBattle`

- `Int32 continuousBattleTimes`

- `Boolean shouldAutoBattleHidden`

- `Boolean canPractice`

- `String overrideBuffId`

- `Int32 styleCost`

- `Boolean isLastTimeAutoBattle`

- `String startBattleStyle`

- `Boolean hasHardToShow`

- `RankViewType StageRankViewType`

- `StageButtonInFogRenderType stageButtonInFogRenderType`

- `String stageDesc`

- `Boolean canReplayStory`


## Methods

- `Void set_localCache(LocalCache)`

- `Int32 get_apCostGroup()`

- `Boolean get_canAutoBattle()`

- `Int32 get_continuousBattleTimes()`

- `Void set_continuousBattleTimes(Int32)`

- `Boolean get_shouldAutoBattleHidden()`

- `Boolean get_canPractice()`

- `String get_overrideBuffId()`

- `Int32 get_styleCost()`

- `Boolean get_isLastTimeAutoBattle()`

- `String get_startBattleStyle()`

- `Boolean get_hasHardToShow()`

- `RankViewType get_StageRankViewType()`

- `StageButtonInFogRenderType get_stageButtonInFogRenderType()`

- `Void set_stageButtonInFogRenderType(StageButtonInFogRenderType)`

- `Boolean GetSpecialStageToShow(SpecialStageType)`

- `T GetSpecialStageInfo(SpecialStageType)`

- `String get_stageDesc()`

- `Boolean get_canReplayStory()`

- `Void SetPlayerData(PlayerStage)`

- `Void RefreshData(PlayerStage)`

- `LazyReplayStoryInfo _LazyGetReplayStoryInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageViewModel : IHotfixable
{
	private LocalCache m_localCache; // 0x10
	public String id; // 0x18
	public String levelId; // 0x20
	public String zoneId; // 0x28
	public String stageCode; // 0x30
	public String stageName; // 0x38
	public LazyRichTextFromData stageDescRichText; // 0x40
	public String hardStageId; // 0x50
	public String sixStarStageId; // 0x58
	public List`1 displayRewards; // 0x60
	public String dangerDesc; // 0x68
	public StageType stageType; // 0x70
	public StageDiffGroup stageDiffGroup; // 0x74
	public StageDiffGroupTable diffGroupTable; // 0x78
	public String normalDiffGroupStageId; // 0x80
	public Boolean isActivity; // 0x88
	public Boolean isCampaign; // 0x89
	public Boolean isMainProgress; // 0x8a
	public String mainRewardItem; // 0x90
	public String rewardCharId; // 0x98
	public Boolean hasBoss; // 0xa0
	public Boolean isHilighted; // 0xa1
	public Boolean isCharacterPredefined; // 0xa2
	public Boolean isHardStageCharacterPredefined; // 0xa3
	public Boolean isStoryOnly; // 0xa4
	public Boolean isTraining; // 0xa5
	public AppearanceStyle appearanceStyle; // 0xa8
	public String timelyDropActiveFlag; // 0xb0
	public Boolean showApProtect; // 0xb8
	public Boolean canContinuousBattle; // 0xb9
	public Int32 apCost; // 0xbc
	public Int32 ptCost; // 0xc0
	public Int32 etCost; // 0xc4
	public String etItemId; // 0xc8
	public Boolean isUsingEt; // 0xd0
	public String etStartBattleStyle; // 0xd8
	public StageBattleDiffGroupInfo battleDiffGroupInfo; // 0xe0
	public OverrideDropInfo overrideDropInfo; // 0xe8
	public Boolean isUnlocked; // 0xf0
	public PlayerStageState stageState; // 0xf4
	public Difficulty stageDifficulty; // 0xf8
	private SpecialStageHandler m_specialStageHandler; // 0x100
	private Boolean m_canPractice; // 0x108
	private Boolean m_hasAutoBattleLog; // 0x109
	private Boolean m_canBattleReplay; // 0x10a
	private Int32 m_continuousBattleTimes; // 0x10c
	public Boolean isRecentAutoBattle; // 0x110
	public Int32 noCostCnt; // 0x114
	public Int32 slProgress; // 0x118
	public Boolean isSkillSelectablePredefined; // 0x11c
	public Boolean hasZoneRecordMission; // 0x11d
	public Boolean isZoneRecordMissionComplete; // 0x11e
	public String zoneRecordMissionDesc; // 0x120
	private LazyReplayStoryInfo m_lazyReplayStoryInfo; // 0x128
	public List`1 sixStarGroupDisplayReward; // 0x138
	public Boolean isStagePatch; // 0x140
	private StageButtonInFogRenderType <stageButtonInFogRenderType>k__BackingField; // 0x144
	private static DelegateBridge __Hotfix0_set_localCache; // 0x0
	private static DelegateBridge __Hotfix0_get_apCostGroup; // 0x8
	private static DelegateBridge __Hotfix0_get_canAutoBattle; // 0x10
	private static DelegateBridge __Hotfix0_get_continuousBattleTimes; // 0x18
	private static DelegateBridge __Hotfix0_set_continuousBattleTimes; // 0x20
	private static DelegateBridge __Hotfix0_get_shouldAutoBattleHidden; // 0x28
	private static DelegateBridge __Hotfix0_get_canPractice; // 0x30
	private static DelegateBridge __Hotfix0_get_overrideBuffId; // 0x38
	private static DelegateBridge __Hotfix0_get_styleCost; // 0x40
	private static DelegateBridge __Hotfix0_get_isLastTimeAutoBattle; // 0x48
	private static DelegateBridge __Hotfix0_get_startBattleStyle; // 0x50
	private static DelegateBridge __Hotfix0_get_hasHardToShow; // 0x58
	private static DelegateBridge __Hotfix0_get_StageRankViewType; // 0x60
	private static DelegateBridge __Hotfix0_get_stageButtonInFogRenderType; // 0x68
	private static DelegateBridge __Hotfix0_set_stageButtonInFogRenderType; // 0x70
	private static DelegateBridge __Hotfix0_GetSpecialStageToShow; // 0x78
	private static DelegateBridge __Hotfix0_GetSpecialStageInfo; // 0x80
	private static DelegateBridge __Hotfix0_get_stageDesc; // 0x88
	private static DelegateBridge __Hotfix0_get_canReplayStory; // 0x90
	private static DelegateBridge __Hotfix0_get_replayStoryData; // 0x98
	private static DelegateBridge __Hotfix0_SetGameData; // 0xa0
	private static DelegateBridge __Hotfix0_SetPlayerData; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshData; // 0xb0
	private static DelegateBridge __Hotfix0__LazyGetReplayStoryInfo; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public LocalCache localCache { set; }
	public Int32 apCostGroup { get; }
	public Boolean canAutoBattle { get; }
	public Int32 continuousBattleTimes { get; set; }
	public Boolean shouldAutoBattleHidden { get; }
	public Boolean canPractice { get; }
	public String overrideBuffId { get; }
	public Int32 styleCost { get; }
	public Boolean isLastTimeAutoBattle { get; }
	public String startBattleStyle { get; }
	public Boolean hasHardToShow { get; }
	public RankViewType StageRankViewType { get; }
	public StageButtonInFogRenderType stageButtonInFogRenderType { get; set; }
	public String stageDesc { get; }
	public Boolean canReplayStory { get; }
	public List`1 replayStoryData { get; }

	// RVA: 0x2f7e3b0 VA: 0x75955963b0
	public Void set_localCache(LocalCache value) { }
	// RVA: 0x2f78280 VA: 0x7595590280
	public Int32 get_apCostGroup() { }
	// RVA: 0x2f7813c VA: 0x759559013c
	public Boolean get_canAutoBattle() { }
	// RVA: 0x2f77aec VA: 0x759558faec
	public Int32 get_continuousBattleTimes() { }
	// RVA: 0x2f7e668 VA: 0x7595596668
	public Void set_continuousBattleTimes(Int32 value) { }
	// RVA: 0x2f77ef4 VA: 0x759558fef4
	public Boolean get_shouldAutoBattleHidden() { }
	// RVA: 0x2f78334 VA: 0x7595590334
	public Boolean get_canPractice() { }
	// RVA: 0x2f7e6e4 VA: 0x75955966e4
	public String get_overrideBuffId() { }
	// RVA: 0x2f78010 VA: 0x7595590010
	public Int32 get_styleCost() { }
	// RVA: 0x2f78200 VA: 0x7595590200
	public Boolean get_isLastTimeAutoBattle() { }
	// RVA: 0x2f77f64 VA: 0x759558ff64
	public String get_startBattleStyle() { }
	// RVA: 0x2f77c00 VA: 0x759558fc00
	public Boolean get_hasHardToShow() { }
	// RVA: 0x2f7e778 VA: 0x7595596778
	public RankViewType get_StageRankViewType() { }
	// RVA: 0x2f7e7f0 VA: 0x75955967f0
	public StageButtonInFogRenderType get_stageButtonInFogRenderType() { }
	// RVA: 0x2f7e858 VA: 0x7595596858
	private Void set_stageButtonInFogRenderType(StageButtonInFogRenderType value) { }
	// RVA: 0x2f77c6c VA: 0x759558fc6c
	public Boolean GetSpecialStageToShow(SpecialStageType specialStageType) { }
	// RVA: 0x VA: 0x0
	public T GetSpecialStageInfo(SpecialStageType specialStageType) { }
	// RVA: 0x2f7e988 VA: 0x7595596988
	public String get_stageDesc() { }
	// RVA: 0x2f77b90 VA: 0x759558fb90
	public Boolean get_canReplayStory() { }
	// RVA: 0x2f7ec9c VA: 0x7595596c9c
	public List`1 get_replayStoryData() { }
	// RVA: 0x2f788f0 VA: 0x75955908f0
	public virtual Void SetGameData(StageData stageData, TimelyDropOptions timelyOptions, StageDiffGroupTable diffPart) { }
	// RVA: 0x2f7f10c VA: 0x759559710c
	public Void SetPlayerData(PlayerStage playerData) { }
	// RVA: 0x2f7df48 VA: 0x7595595f48
	public Void RefreshData(PlayerStage playerData) { }
	// RVA: 0x2f7e9f4 VA: 0x75955969f4
	private LazyReplayStoryInfo _LazyGetReplayStoryInfo() { }
	// RVA: 0x2f79298 VA: 0x7595591298
	public Void .ctor() { }
}
```