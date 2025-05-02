# RoguelikeTopicDetail

**Namespace:** `Torappu`


## Fields

- `RoguelikeArchiveComponentData archiveComp`

- `RoguelikeArchiveUnlockCondData archiveUnlockCond`

- `RoguelikeTopicDetailConst detailConst`

- `RoguelikeGameConst gameConst`

- `RoguelikeGameShopDialogData shopDialogData`

- `RoguelikePredefinedConstStyleData styleConfig`

- `RoguelikeActivityData activity`


## Methods

- `Boolean ShouldSerializestyles()`

- `Boolean ShouldSerializestyleConfig()`

- `Boolean ShouldSerializeexploreTools()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicDetail
{
	public List`1 updates; // 0x10
	public Dictionary`2 enrolls; // 0x18
	public List`1 milestones; // 0x20
	public List`1 milestoneUpdates; // 0x28
	public List`1 grandPrizes; // 0x30
	public List`1 monthMission; // 0x38
	public Dictionary`2 monthSquad; // 0x40
	public Dictionary`2 challenges; // 0x48
	public List`1 difficulties; // 0x50
	public List`1 bankRewards; // 0x58
	public RoguelikeArchiveComponentData archiveComp; // 0x60
	public RoguelikeArchiveUnlockCondData archiveUnlockCond; // 0x68
	public RoguelikeTopicDetailConst detailConst; // 0x70
	public List`1 init; // 0x78
	public Dictionary`2 stages; // 0x80
	public Dictionary`2 zones; // 0x88
	public Dictionary`2 variation; // 0x90
	public Dictionary`2 traps; // 0x98
	public Dictionary`2 recruitTickets; // 0xa0
	public Dictionary`2 upgradeTickets; // 0xa8
	public Dictionary`2 customTickets; // 0xb0
	public Dictionary`2 relics; // 0xb8
	public Dictionary`2 relicParams; // 0xc0
	public Dictionary`2 recruitGrps; // 0xc8
	public Dictionary`2 choices; // 0xd0
	public Dictionary`2 choiceScenes; // 0xd8
	public Dictionary`2 nodeTypeData; // 0xe0
	public List`1 subTypeData; // 0xe8
	public Dictionary`2 variationData; // 0xf0
	public Dictionary`2 charBuffData; // 0xf8
	public Dictionary`2 squadBuffData; // 0x100
	public Dictionary`2 taskData; // 0x108
	public RoguelikeGameConst gameConst; // 0x110
	public RoguelikeGameShopDialogData shopDialogData; // 0x118
	public Dictionary`2 capsuleDict; // 0x120
	public Dictionary`2 endings; // 0x128
	public Dictionary`2 failEndings; // 0x130
	public Dictionary`2 battleSummeryDescriptions; // 0x138
	public List`1 battleLoadingTips; // 0x140
	public Dictionary`2 items; // 0x148
	public Dictionary`2 bandRef; // 0x150
	public List`1 endingDetailList; // 0x158
	public List`1 endingRelicDetailList; // 0x160
	public Dictionary`2 treasures; // 0x168
	public Dictionary`2 difficultyUpgradeRelicGroups; // 0x170
	public Dictionary`2 styles; // 0x178
	public RoguelikePredefinedConstStyleData styleConfig; // 0x180
	public Dictionary`2 exploreTools; // 0x188
	public Dictionary`2 rollNodeData; // 0x190
	public RoguelikeActivityData activity; // 0x198


	// RVA: 0x34a96ec VA: 0x7595ac16ec
	public Boolean ShouldSerializestyles() { }
	// RVA: 0x34a9740 VA: 0x7595ac1740
	public Boolean ShouldSerializestyleConfig() { }
	// RVA: 0x34a9750 VA: 0x7595ac1750
	public Boolean ShouldSerializeexploreTools() { }
	// RVA: 0x34a97a4 VA: 0x7595ac17a4
	public Void .ctor() { }
}
```