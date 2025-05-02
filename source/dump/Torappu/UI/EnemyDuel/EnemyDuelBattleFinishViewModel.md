# EnemyDuelBattleFinishViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `Int32 settlePicNum`

- `String modeId`

- `String sceneId`

- `String modeTitle`

- `EnemyDuelModeType duelMode`

- `Boolean isQuit`

- `Boolean isSolo`

- `Boolean isRoom`

- `Boolean isRoomOwner`

- `Int32 playerScore`

- `ChoiceCntInfo operationInfo`

- `Single countDownSeconds`

- `String nickName`

- `String nickNumber`

- `String commentText`

- `Boolean isBest`

- `Int32 rank`

- `Int32 selfIndex`

- `Boolean isTopRank`

- `AvatarInfo avatarInfo`

- `Int32 rewardDailyMission`

- `Int32 currDailyMission`

- `Int32 fullDailyMission`

- `Int32 rewardBpDailyComplete`

- `Int32 rewardBp`

- `MileStoneInfo prevMileStone`

- `MileStoneInfo currMileStone`

- `String m_commentId`

- `String m_uid`


## Methods

- `Void LoadData()`

- `MileStoneInfo GetMileStoneInfoByPoint(Int32)`

- `Void _LoadBattleInOut()`

- `Void _LoadSingleModeData(ActivityEnemyDuelData)`

- `Void _LoadMultiModeData(ActivityEnemyDuelData)`

- `Void _LoadDailyMissionAndBp(ActivityEnemyDuelData)`

- `Void _LoadRankList(ActivityEnemyDuelData, List`1)`

- `String _LoadCommentText(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleFinishViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 settlePicNum; // 0x18
	public String modeId; // 0x20
	public String sceneId; // 0x28
	public String modeTitle; // 0x30
	public EnemyDuelModeType duelMode; // 0x38
	public Boolean isQuit; // 0x3c
	public Boolean isSolo; // 0x3d
	public Boolean isRoom; // 0x3e
	public Boolean isRoomOwner; // 0x3f
	public Int32 playerScore; // 0x40
	public ChoiceCntInfo operationInfo; // 0x48
	public Single countDownSeconds; // 0x50
	public String nickName; // 0x58
	public String nickNumber; // 0x60
	public String commentText; // 0x68
	public Boolean isBest; // 0x70
	public Int32 rank; // 0x74
	public Int32 selfIndex; // 0x78
	public Boolean isTopRank; // 0x7c
	public AvatarInfo avatarInfo; // 0x80
	public Int32 rewardDailyMission; // 0x88
	public Int32 currDailyMission; // 0x8c
	public Int32 fullDailyMission; // 0x90
	public Int32 rewardBpDailyComplete; // 0x94
	public Int32 rewardBp; // 0x98
	public MileStoneInfo prevMileStone; // 0x9c
	public MileStoneInfo currMileStone; // 0xb8
	private List`1 m_mileStoneList; // 0xd8
	private String m_commentId; // 0xe0
	private String m_uid; // 0xe8
	public List`1 m_rankList; // 0xf0
	private static DelegateBridge __Hotfix0_get_rankList; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_GetMileStoneInfoByPoint; // 0x10
	private static DelegateBridge __Hotfix0__LoadBattleInOut; // 0x18
	private static DelegateBridge __Hotfix0__LoadSingleModeData; // 0x20
	private static DelegateBridge __Hotfix0__LoadMultiModeData; // 0x28
	private static DelegateBridge __Hotfix0__LoadDailyMissionAndBp; // 0x30
	private static DelegateBridge __Hotfix0__LoadRankList; // 0x38
	private static DelegateBridge __Hotfix0__LoadCommentText; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 rankList { get; }

	// RVA: 0x293eee0 VA: 0x7594f56ee0
	public List`1 get_rankList() { }
	// RVA: 0x293fdc4 VA: 0x7594f57dc4
	public Void LoadData() { }
	// RVA: 0x2940308 VA: 0x7594f58308
	public MileStoneInfo GetMileStoneInfoByPoint(Int32 point) { }
	// RVA: 0x2941968 VA: 0x7594f59968
	private Void _LoadBattleInOut() { }
	// RVA: 0x2941bc0 VA: 0x7594f59bc0
	private Void _LoadSingleModeData(ActivityEnemyDuelData actData) { }
	// RVA: 0x2941d28 VA: 0x7594f59d28
	private Void _LoadMultiModeData(ActivityEnemyDuelData actData) { }
	// RVA: 0x2941f68 VA: 0x7594f59f68
	private Void _LoadDailyMissionAndBp(ActivityEnemyDuelData actData) { }
	// RVA: 0x29422ac VA: 0x7594f5a2ac
	private Void _LoadRankList(ActivityEnemyDuelData actData, List`1 playerList) { }
	// RVA: 0x2941e90 VA: 0x7594f59e90
	private String _LoadCommentText(ListDict`2 commentDict) { }
	// RVA: 0x2941124 VA: 0x7594f59124
	public Void .ctor() { }
}
```