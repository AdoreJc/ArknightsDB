# StageData

**Namespace:** `Torappu`


## Fields

- `StageType stageType`

- `Difficulty difficulty`

- `PerformanceStageFlag performanceStageFlag`

- `StageDiffGroup diffGroup`

- `String stageId`

- `String levelId`

- `String zoneId`

- `String code`

- `String name`

- `String description`

- `String hardStagedId`

- `String sixStarStageId`

- `String dangerLevel`

- `Single dangerPoint`

- `String loadingPicId`

- `Boolean canPractice`

- `Boolean canBattleReplay`

- `Int32 apCost`

- `Int32 apFailReturn`

- `String etItemId`

- `Int32 etCost`

- `Int32 etFailReturn`

- `String etButtonStyle`

- `Int32 apProtectTimes`

- `Int32 diamondOnceDrop`

- `Int32 practiceTicketCost`

- `Int32 dailyStageDifficulty`

- `Int32 expGain`

- `Int32 goldGain`

- `Int32 loseExpGain`

- `Int32 loseGoldGain`

- `Int32 passFavor`

- `Int32 completeFavor`

- `Int32 slProgress`

- `String displayMainItem`

- `Boolean hilightMark`

- `Boolean bossMark`

- `Boolean isPredefined`

- `Boolean isHardPredefined`

- `Boolean isSkillSelectablePredefined`

- `Boolean isStoryOnly`

- `AppearanceStyle appearanceStyle`

- `StageDropInfo stageDropInfo`

- `Boolean canUseCharm`

- `Boolean canUseTech`

- `Boolean canUseTrapTool`

- `Boolean canUseBattlePerformance`

- `Boolean canUseFirework`

- `Boolean canContinuousBattle`

- `String startButtonOverrideId`

- `Boolean isStagePatch`

- `String mainStageId`

- `String sixStarBaseDesc`


## Methods

- `Boolean isMain()`

- `Boolean IsCampaign()`

- `Boolean IsActivity()`

- `Boolean IsPredefinedButNotGuide()`

- `Boolean ShouldSerializeS_extraCondition()`

- `Boolean ShouldSerializeS_extraInfo()`

- `Boolean ShouldSerializecanUseCharm()`

- `Boolean ShouldSerializecanUseTech()`

- `Boolean ShouldSerializecanUseTrapTool()`

- `Boolean ShouldSerializecanUseBattlePerformance()`

- `Boolean ShouldSerializecanContinuousBattle()`

- `Boolean ShouldSerializecanUseFirework()`

- `Boolean ShouldSerializesixStarBaseDesc()`

- `Boolean ShouldSerializeadvancedRuneIdList1()`

- `Boolean ShouldSerializeadvancedRuneIdList2()`

- `Boolean ShouldSerializesixStarStageId()`

- `Boolean ShouldSerializesixStarDisplayRewardList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StageData
{
	public StageType stageType; // 0x10
	public Difficulty difficulty; // 0x14
	public PerformanceStageFlag performanceStageFlag; // 0x18
	public StageDiffGroup diffGroup; // 0x1c
	public List`1 unlockCondition; // 0x20
	public String stageId; // 0x28
	public String levelId; // 0x30
	public String zoneId; // 0x38
	public String code; // 0x40
	public String name; // 0x48
	public String description; // 0x50
	public String hardStagedId; // 0x58
	public String sixStarStageId; // 0x60
	public String dangerLevel; // 0x68
	public Single dangerPoint; // 0x70
	public String loadingPicId; // 0x78
	public Boolean canPractice; // 0x80
	public Boolean canBattleReplay; // 0x81
	public Int32 apCost; // 0x84
	public Int32 apFailReturn; // 0x88
	public String etItemId; // 0x90
	public Int32 etCost; // 0x98
	public Int32 etFailReturn; // 0x9c
	public String etButtonStyle; // 0xa0
	public Int32 apProtectTimes; // 0xa8
	public Int32 diamondOnceDrop; // 0xac
	public Int32 practiceTicketCost; // 0xb0
	public Int32 dailyStageDifficulty; // 0xb4
	public Int32 expGain; // 0xb8
	public Int32 goldGain; // 0xbc
	public Int32 loseExpGain; // 0xc0
	public Int32 loseGoldGain; // 0xc4
	public Int32 passFavor; // 0xc8
	public Int32 completeFavor; // 0xcc
	public Int32 slProgress; // 0xd0
	public String displayMainItem; // 0xd8
	public Boolean hilightMark; // 0xe0
	public Boolean bossMark; // 0xe1
	public Boolean isPredefined; // 0xe2
	public Boolean isHardPredefined; // 0xe3
	public Boolean isSkillSelectablePredefined; // 0xe4
	public Boolean isStoryOnly; // 0xe5
	public AppearanceStyle appearanceStyle; // 0xe8
	public StageDropInfo stageDropInfo; // 0xf0
	public Boolean canUseCharm; // 0xf8
	public Boolean canUseTech; // 0xf9
	public Boolean canUseTrapTool; // 0xfa
	public Boolean canUseBattlePerformance; // 0xfb
	public Boolean canUseFirework; // 0xfc
	public Boolean canContinuousBattle; // 0xfd
	public String startButtonOverrideId; // 0x100
	public Boolean isStagePatch; // 0x108
	public String mainStageId; // 0x110
	public List`1 S_extraCondition; // 0x118
	public List`1 S_extraInfo; // 0x120
	public String sixStarBaseDesc; // 0x128
	public List`1 sixStarDisplayRewardList; // 0x130
	public List`1 advancedRuneIdList1; // 0x138
	public List`1 advancedRuneIdList2; // 0x140


	// RVA: 0x34f671c VA: 0x7595b0e71c
	public Boolean isMain() { }
	// RVA: 0x34f672c VA: 0x7595b0e72c
	public Boolean IsCampaign() { }
	// RVA: 0x34f673c VA: 0x7595b0e73c
	public Boolean IsActivity() { }
	// RVA: 0x34f674c VA: 0x7595b0e74c
	public Boolean IsPredefinedButNotGuide() { }
	// RVA: 0x34f676c VA: 0x7595b0e76c
	public Boolean ShouldSerializeS_extraCondition() { }
	// RVA: 0x34f677c VA: 0x7595b0e77c
	public Boolean ShouldSerializeS_extraInfo() { }
	// RVA: 0x34f678c VA: 0x7595b0e78c
	public Boolean ShouldSerializecanUseCharm() { }
	// RVA: 0x34f6794 VA: 0x7595b0e794
	public Boolean ShouldSerializecanUseTech() { }
	// RVA: 0x34f679c VA: 0x7595b0e79c
	public Boolean ShouldSerializecanUseTrapTool() { }
	// RVA: 0x34f67a4 VA: 0x7595b0e7a4
	public Boolean ShouldSerializecanUseBattlePerformance() { }
	// RVA: 0x34f67ac VA: 0x7595b0e7ac
	public Boolean ShouldSerializecanContinuousBattle() { }
	// RVA: 0x34f67b4 VA: 0x7595b0e7b4
	public Boolean ShouldSerializecanUseFirework() { }
	// RVA: 0x34f67bc VA: 0x7595b0e7bc
	public Boolean ShouldSerializesixStarBaseDesc() { }
	// RVA: 0x34f67cc VA: 0x7595b0e7cc
	public Boolean ShouldSerializeadvancedRuneIdList1() { }
	// RVA: 0x34f67dc VA: 0x7595b0e7dc
	public Boolean ShouldSerializeadvancedRuneIdList2() { }
	// RVA: 0x34f67ec VA: 0x7595b0e7ec
	public Boolean ShouldSerializesixStarStageId() { }
	// RVA: 0x34f680c VA: 0x7595b0e80c
	public Boolean ShouldSerializesixStarDisplayRewardList() { }
	// RVA: 0x34f6840 VA: 0x7595b0e840
	public Void .ctor() { }
}
```