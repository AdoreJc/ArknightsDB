# SandboxV2DungeonViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String topicId`

- `String mapId`

- `String centerNodeId`

- `String monthModeNodeId`

- `Single centerNodeEnterAnimDelay`

- `SandboxV2MapConfig mapConfig`

- `SandboxV2DungeonGameflowViewModel gameflowViewModel`

- `SandboxV2DungeonMiscViewModel miscViewModel`

- `ChallengeState challengeState`

- `Boolean needPlayEnterAnim`

- `Boolean fastModeWhenDungeonChange`

- `Boolean hasQuestTracker`

- `Int32 otherTrackerCount`

- `Boolean isBasementEmergency`

- `Boolean hasEmergencyEnemyRush`

- `String selectedNodeId`

- `String selectedPathId`

- `String selectedFloatGroupNodeId`

- `FocusParam focusParam`

- `NodeRegisterParam registerParam`

- `EnterAnimParam enterAnimParam`


## Methods

- `Void _IncreaseSequenceNum(SequenceNumFlag)`

- `Int32 _GetSequenceNum(SequenceNumFlag)`

- `Void LoadData(String, LoadDataParam)`

- `Void _LoadData(SandboxV2Data, PlayerSandboxV2, Dungeon, LoadDataParam)`

- `Void _UpdateData(SandboxV2Data, PlayerSandboxV2, Dungeon)`

- `Void _UpdatePathData(SandboxV2DungeonFloatViewModel)`

- `Void _UpdateEnemyRushData(SandboxV2Data, Dungeon)`

- `Void _UpdateRareAnimalData(SandboxV2Data, Dungeon)`

- `Void _UpdateRiftFloatData(SandboxV2Data, PlayerSandboxV2)`

- `Void _UpdateNodeFloatData()`

- `Void _UpdateQuestData(SandboxV2Data, PlayerSandboxV2)`

- `Boolean _HasQuest(SandboxV2Data, PlayerSandboxV2)`

- `Boolean _HasRiftQuest(SandboxV2Data)`

- `ChallengeState _GetCurrChallengeState(Status, Dungeon)`

- `SandboxV2DungeonNodeViewModel GetNodeViewModel(String)`

- `Boolean CheckNodeSelected(String)`

- `Boolean HasBossEnemyRush()`

- `Boolean CanSelectNode(String)`

- `Boolean SetSelectedNode(String)`

- `Boolean CancelSelectedNode()`

- `Boolean SetSelectedPath(String)`

- `Boolean CancelSelectedPath()`

- `Boolean SetSelectedFloatGroup(String)`

- `Boolean CancelSelectedFloatGroup()`

- `Boolean FocusNode(String, SandboxV2DungeonNodeFocusType, Boolean, Single, Ease)`

- `Boolean FocusZone(String, Boolean, Single, Ease)`

- `Boolean Zoom(ZoomType, String, Single, Ease)`

- `Boolean SetEnterAnimStatus(Boolean, Boolean)`

- `Boolean TutorialOnly_RegisterNode(String)`

- `String TutorialOnly_GetNodeIdByEnemyRushGroupKey(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonViewModel : IHotfixable
{
	private const String LINE_ID_FORMAT; // 0x0
	private const String PATH_ID_FORMAT; // 0x0
	private Dictionary`2 m_sequenceNums; // 0x10
	public String topicId; // 0x18
	public String mapId; // 0x20
	public String centerNodeId; // 0x28
	public String monthModeNodeId; // 0x30
	public Single centerNodeEnterAnimDelay; // 0x38
	public SandboxV2MapConfig mapConfig; // 0x40
	public SandboxV2DungeonGameflowViewModel gameflowViewModel; // 0x48
	public SandboxV2DungeonMiscViewModel miscViewModel; // 0x50
	public Dictionary`2 zones; // 0x58
	public Dictionary`2 nodes; // 0x60
	public Dictionary`2 lines; // 0x68
	public Dictionary`2 pathLines; // 0x70
	public List`1 nodeList; // 0x78
	public List`1 enemyRushList; // 0x80
	public ChallengeState challengeState; // 0x88
	public Boolean needPlayEnterAnim; // 0x8c
	public Boolean fastModeWhenDungeonChange; // 0x8d
	public Boolean hasQuestTracker; // 0x8e
	public Int32 otherTrackerCount; // 0x90
	public Boolean isBasementEmergency; // 0x94
	public Boolean hasEmergencyEnemyRush; // 0x95
	public String selectedNodeId; // 0x98
	public String selectedPathId; // 0xa0
	public String selectedFloatGroupNodeId; // 0xa8
	public FocusParam focusParam; // 0xb0
	public NodeRegisterParam registerParam; // 0xd8
	public EnterAnimParam enterAnimParam; // 0xe0
	private static DelegateBridge __Hotfix0__IncreaseSequenceNum; // 0x0
	private static DelegateBridge __Hotfix0__GetSequenceNum; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__LoadData; // 0x18
	private static DelegateBridge __Hotfix0__UpdateData; // 0x20
	private static DelegateBridge __Hotfix0__UpdatePathData; // 0x28
	private static DelegateBridge __Hotfix0__UpdateEnemyRushData; // 0x30
	private static DelegateBridge __Hotfix0__UpdateRareAnimalData; // 0x38
	private static DelegateBridge __Hotfix0__UpdateRiftFloatData; // 0x40
	private static DelegateBridge __Hotfix0__UpdateNodeFloatData; // 0x48
	private static DelegateBridge __Hotfix0__UpdateQuestData; // 0x50
	private static DelegateBridge __Hotfix0__HasQuest; // 0x58
	private static DelegateBridge __Hotfix0__HasRiftQuest; // 0x60
	private static DelegateBridge __Hotfix0__GetCurrChallengeState; // 0x68
	private static DelegateBridge __Hotfix0_GetNodeViewModel; // 0x70
	private static DelegateBridge __Hotfix0_CheckNodeSelected; // 0x78
	private static DelegateBridge __Hotfix0_HasBossEnemyRush; // 0x80
	private static DelegateBridge __Hotfix0_CanSelectNode; // 0x88
	private static DelegateBridge __Hotfix0_SetSelectedNode; // 0x90
	private static DelegateBridge __Hotfix0_CancelSelectedNode; // 0x98
	private static DelegateBridge __Hotfix0_SetSelectedPath; // 0xa0
	private static DelegateBridge __Hotfix0_CancelSelectedPath; // 0xa8
	private static DelegateBridge __Hotfix0_SetSelectedFloatGroup; // 0xb0
	private static DelegateBridge __Hotfix0_CancelSelectedFloatGroup; // 0xb8
	private static DelegateBridge __Hotfix0_FocusNode; // 0xc0
	private static DelegateBridge __Hotfix0_FocusZone; // 0xc8
	private static DelegateBridge __Hotfix0_Zoom; // 0xd0
	private static DelegateBridge __Hotfix0_SetEnterAnimStatus; // 0xd8
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterNode; // 0xe0
	private static DelegateBridge __Hotfix0_TutorialOnly_GetNodeIdByEnemyRushGroupKey; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0


	// RVA: 0x25c2a60 VA: 0x7594bdaa60
	private Void _IncreaseSequenceNum(SequenceNumFlag flag) { }
	// RVA: 0x25c2b30 VA: 0x7594bdab30
	private Int32 _GetSequenceNum(SequenceNumFlag flag) { }
	// RVA: 0x25c2bcc VA: 0x7594bdabcc
	public Void LoadData(String topic, LoadDataParam param) { }
	// RVA: 0x25c2ee4 VA: 0x7594bdaee4
	private Void _LoadData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData, Dungeon playerDungeonData, LoadDataParam param) { }
	// RVA: 0x25c4160 VA: 0x7594bdc160
	private Void _UpdateData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData, Dungeon playerDungeonData) { }
	// RVA: 0x25c5a10 VA: 0x7594bdda10
	private Void _UpdatePathData(SandboxV2DungeonFloatViewModel floatViewModel) { }
	// RVA: 0x25c4d50 VA: 0x7594bdcd50
	private Void _UpdateEnemyRushData(SandboxV2Data topicDetailData, Dungeon playerDungeonData) { }
	// RVA: 0x25c5290 VA: 0x7594bdd290
	private Void _UpdateRareAnimalData(SandboxV2Data topicDetailData, Dungeon playerDungeonData) { }
	// RVA: 0x25c5584 VA: 0x7594bdd584
	private Void _UpdateRiftFloatData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData) { }
	// RVA: 0x25c56e8 VA: 0x7594bdd6e8
	private Void _UpdateNodeFloatData() { }
	// RVA: 0x25c594c VA: 0x7594bdd94c
	private Void _UpdateQuestData(SandboxV2Data topicDetailData, PlayerSandboxV2 playerSandboxData) { }
	// RVA: 0x25c5fa0 VA: 0x7594bddfa0
	private Boolean _HasQuest(SandboxV2Data topicDetailData, PlayerSandboxV2 playerSandboxData) { }
	// RVA: 0x25c5e84 VA: 0x7594bdde84
	private Boolean _HasRiftQuest(SandboxV2Data topicDetailData) { }
	// RVA: 0x25c2e1c VA: 0x7594bdae1c
	private ChallengeState _GetCurrChallengeState(Status playerStatus, Dungeon playerDungeonData) { }
	// RVA: 0x25c4918 VA: 0x7594bdc918
	public SandboxV2DungeonNodeViewModel GetNodeViewModel(String nodeId) { }
	// RVA: 0x25c6158 VA: 0x7594bde158
	public Boolean CheckNodeSelected(String nodeId) { }
	// RVA: 0x25c6200 VA: 0x7594bde200
	public Boolean HasBossEnemyRush() { }
	// RVA: 0x25c62fc VA: 0x7594bde2fc
	public Boolean CanSelectNode(String nodeId) { }
	// RVA: 0x25c63b8 VA: 0x7594bde3b8
	public Boolean SetSelectedNode(String nodeId) { }
	// RVA: 0x25c49d8 VA: 0x7594bdc9d8
	public Boolean CancelSelectedNode() { }
	// RVA: 0x25c64b0 VA: 0x7594bde4b0
	public Boolean SetSelectedPath(String pathId) { }
	// RVA: 0x25c4a78 VA: 0x7594bdca78
	public Boolean CancelSelectedPath() { }
	// RVA: 0x25c6560 VA: 0x7594bde560
	public Boolean SetSelectedFloatGroup(String nodeId) { }
	// RVA: 0x25c4afc VA: 0x7594bdcafc
	public Boolean CancelSelectedFloatGroup() { }
	// RVA: 0x25c4b80 VA: 0x7594bdcb80
	public Boolean FocusNode(String nodeId, SandboxV2DungeonNodeFocusType focusType, Boolean fastMode, Single duration, Ease easeType) { }
	// RVA: 0x25c6608 VA: 0x7594bde608
	public Boolean FocusZone(String zoneId, Boolean fastMode, Single duration, Ease easeType) { }
	// RVA: 0x25c672c VA: 0x7594bde72c
	public Boolean Zoom(ZoomType zoomType, String nodeId, Single duration, Ease easeType) { }
	// RVA: 0x25c4cb0 VA: 0x7594bdccb0
	public Boolean SetEnterAnimStatus(Boolean playEnterAnim, Boolean fastMode) { }
	// RVA: 0x25c6828 VA: 0x7594bde828
	public Boolean TutorialOnly_RegisterNode(String nodeId) { }
	// RVA: 0x25c68d0 VA: 0x7594bde8d0
	public String TutorialOnly_GetNodeIdByEnemyRushGroupKey(String enemyRushGroupKey) { }
	// RVA: 0x25c6a04 VA: 0x7594bdea04
	public Void .ctor() { }
}
```