# SandboxV2DungeonCrossDayDailyModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean showLongAnim`

- `Boolean showHasRead`

- `Boolean showHasSave`

- `Boolean showSeasonChangeInfo`

- `SandboxV2SeasonType seasonType`

- `String seasonTitle`

- `String seasonDesc`

- `Color seasonCol`

- `Int32 circleDayBefore`

- `Int32 circleDayAfter`

- `Boolean showDayCircleSeasonInfo`

- `Single circleSeasonBeforeAngle`

- `Single circleSeasonAfterAngle`

- `Int32 circleMaxApDotCount`

- `Boolean showCircleDayText`

- `String circleDayTitleText`

- `Boolean showCircleDaySaveFilePic`

- `Boolean showCircleDayRiftPic`

- `Boolean showCircleDayRiftTotal`

- `Int32 circleDayRiftTotal`

- `Boolean showCircleDayChallengePic`

- `Boolean showBaseProductPart`

- `Boolean showExpeditionPart`

- `Boolean isRift`

- `Boolean isChallenge`

- `Boolean isFirstDay`


## Methods

- `Void LoadData(SandboxV2Data, Status, Dungeon)`

- `Void _GetSortedReportItemList(ref, List`1, Dictionary`2)`

- `Int32 _ItemSort(SandboxV2DungeonCrossDayReportItemModel, SandboxV2DungeonCrossDayReportItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayDailyModel : IHotfixable
{
	public Boolean showLongAnim; // 0x10
	public Boolean showHasRead; // 0x11
	public Boolean showHasSave; // 0x12
	public Boolean showSeasonChangeInfo; // 0x13
	public SandboxV2SeasonType seasonType; // 0x14
	public String seasonTitle; // 0x18
	public String seasonDesc; // 0x20
	public Color seasonCol; // 0x28
	public Int32 circleDayBefore; // 0x38
	public Int32 circleDayAfter; // 0x3c
	public Boolean showDayCircleSeasonInfo; // 0x40
	public Single circleSeasonBeforeAngle; // 0x44
	public Single circleSeasonAfterAngle; // 0x48
	public Int32 circleMaxApDotCount; // 0x4c
	public Boolean showCircleDayText; // 0x50
	public String circleDayTitleText; // 0x58
	public Boolean showCircleDaySaveFilePic; // 0x60
	public Boolean showCircleDayRiftPic; // 0x61
	public Boolean showCircleDayRiftTotal; // 0x62
	public Int32 circleDayRiftTotal; // 0x64
	public Boolean showCircleDayChallengePic; // 0x68
	public Boolean showBaseProductPart; // 0x69
	public Boolean showExpeditionPart; // 0x6a
	public Boolean isRift; // 0x6b
	public Boolean isChallenge; // 0x6c
	public Boolean isFirstDay; // 0x6d
	private List`1 m_expeditionSquadData; // 0x70
	private List`1 m_expeditionRewardItemList; // 0x78
	private List`1 m_baseProductItemList; // 0x80
	private static DelegateBridge __Hotfix0_get_expeditionSquadData; // 0x0
	private static DelegateBridge __Hotfix0_get_expeditionRewardItemList; // 0x8
	private static DelegateBridge __Hotfix0_get_baseProductItemList; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__GetSortedReportItemList; // 0x20
	private static DelegateBridge __Hotfix0__ItemSort; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 expeditionSquadData { get; }
	public List`1 expeditionRewardItemList { get; }
	public List`1 baseProductItemList { get; }

	// RVA: 0x2525484 VA: 0x7594b3d484
	public List`1 get_expeditionSquadData() { }
	// RVA: 0x25254ec VA: 0x7594b3d4ec
	public List`1 get_expeditionRewardItemList() { }
	// RVA: 0x2525554 VA: 0x7594b3d554
	public List`1 get_baseProductItemList() { }
	// RVA: 0x252415c VA: 0x7594b3c15c
	public Void LoadData(SandboxV2Data topicDetailData, Status playerStatus, Dungeon playerDungeonData) { }
	// RVA: 0x25255bc VA: 0x7594b3d5bc
	private Void _GetSortedReportItemList(ref List`1 resultList, List`1 reportGainItems, Dictionary`2 sandboxPermItemData) { }
	// RVA: 0x2525a4c VA: 0x7594b3da4c
	private Int32 _ItemSort(SandboxV2DungeonCrossDayReportItemModel a, SandboxV2DungeonCrossDayReportItemModel b) { }
	// RVA: 0x2524014 VA: 0x7594b3c014
	public Void .ctor() { }
}
```