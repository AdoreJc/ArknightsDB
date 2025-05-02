# Act1ArcadeSettlementModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String actId`

- `ArcadeBadgeData curBattleBadge`

- `Int32 badgeTier`

- `Int32 newScore`

- `Boolean hasNewRecord`

- `Boolean hasNewRank`

- `Rank rank`

- `Int32 milestoneBefore`

- `Int32 milestoneAdd`

- `Boolean isMilestoneMax`

- `SquadItemStruct assistSquadData`

- `CharUISkinStruct randomSkin`

- `StageData stageData`

- `String playerName`

- `Int64 finishTs`


## Properties

- `Boolean hasNewUnlockBadge`


## Methods

- `Boolean get_hasNewUnlockBadge()`

- `Void InitModel()`

- `Void _InitBadgeData(String, ActArcadeData, PlayerArcadeActivity, String, ArcadeFinishBattleResponse)`

- `Void _InitScoreAndRank(String, String, ActArcadeData, ArcadeFinishBattleResponse)`

- `Void _InitMilestone(String, ActArcadeData, ArcadeFinishBattleResponse)`

- `TemplateActivityMileStoneItemModel GetMilestoneItemModel(Int32, out, out, Int32)`

- `Int32 _GetPrefLevelTokenNum(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementModel : IHotfixable
{
	public String actId; // 0x10
	public List`1 newUnlockBadges; // 0x18
	public ListDict`2 newStepBadges; // 0x20
	public ArcadeBadgeData curBattleBadge; // 0x28
	public Int32 badgeTier; // 0x30
	public Dictionary`2 hasNewStageZoneDict; // 0x38
	public Int32 newScore; // 0x40
	public Boolean hasNewRecord; // 0x44
	public Boolean hasNewRank; // 0x45
	public Rank rank; // 0x48
	public Int32 milestoneBefore; // 0x4c
	public Int32 milestoneAdd; // 0x50
	public Boolean isMilestoneMax; // 0x54
	public List`1 m_milestoneList; // 0x58
	public SquadItemStruct[] localSquads; // 0x60
	public SquadItemStruct assistSquadData; // 0x68
	public CharUISkinStruct randomSkin; // 0x78
	public StageData stageData; // 0x88
	public String playerName; // 0x90
	public Int64 finishTs; // 0x98
	private static DelegateBridge __Hotfix0_get_hasNewUnlockBadge; // 0x0
	private static DelegateBridge __Hotfix0_InitModel; // 0x8
	private static DelegateBridge __Hotfix0__InitBadgeData; // 0x10
	private static DelegateBridge __Hotfix0__InitScoreAndRank; // 0x18
	private static DelegateBridge __Hotfix0__InitMilestone; // 0x20
	private static DelegateBridge __Hotfix0_GetMilestoneItemModel; // 0x28
	private static DelegateBridge __Hotfix0__GetPrefLevelTokenNum; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean hasNewUnlockBadge { get; }

	// RVA: 0x3403b7c VA: 0x7595a1bb7c
	public Boolean get_hasNewUnlockBadge() { }
	// RVA: 0x3403c08 VA: 0x7595a1bc08
	public Void InitModel() { }
	// RVA: 0x340426c VA: 0x7595a1c26c
	private Void _InitBadgeData(String activityId, ActArcadeData arcadeData, PlayerArcadeActivity arcadePlayerData, String curZoneId, ArcadeFinishBattleResponse arcadeResponse) { }
	// RVA: 0x340493c VA: 0x7595a1c93c
	private Void _InitScoreAndRank(String activityId, String stageId, ActArcadeData arcadeData, ArcadeFinishBattleResponse arcadeResponse) { }
	// RVA: 0x3404b14 VA: 0x7595a1cb14
	private Void _InitMilestone(String activityId, ActArcadeData arcadeData, ArcadeFinishBattleResponse arcadeResponse) { }
	// RVA: 0x3404de8 VA: 0x7595a1cde8
	public TemplateActivityMileStoneItemModel GetMilestoneItemModel(Int32 milestoneTokenNum, out Int32 prefLevelTokenNum, out Boolean isReachMax, Int32 startFindIndex) { }
	// RVA: 0x3404fb8 VA: 0x7595a1cfb8
	private Int32 _GetPrefLevelTokenNum(Int32 curIndex) { }
	// RVA: 0x3405060 VA: 0x7595a1d060
	public Void .ctor() { }
}
```