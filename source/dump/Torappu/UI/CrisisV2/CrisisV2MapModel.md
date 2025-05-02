# CrisisV2MapModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_mapId`

- `String m_seasonId`

- `Int32 m_highestScore`

- `CrisisV2SlotDetailViewModel m_slotDetailViewModel`

- `CrisisV2BagDetailViewModel m_bagDetailViewModel`

- `CrisisV2MapDetailData m_mapDetailData`

- `CrisisV2MapStageData m_mapStageData`

- `CrisisV2SeasonConstData m_constData`

- `CrisisV2RuneDetailViewModel m_mapRuneDetailViewModel`

- `CrisisV2SeasonInfo m_seasonInfo`

- `Int32 m_bgmHardPoint`

- `Int32 m_hardStyleScoreThreshold`

- `CrisisV2MissionProgress m_missionProgress`

- `String m_avgJumpRuneNodeId`

- `String m_avgJumpTreasureNodeId`

- `String m_avgJumpKeypointNodeId`

- `String m_avgJumpBagId`

- `Int32 m_switchViewSeqNum`

- `ViewType m_viewType`

- `Int32 m_jumpSeqNum`

- `Single m_jumpPos`

- `Boolean m_isDimensionListShow`

- `CrisisV2FocusModel m_focusModel`

- `CrisisV2PreviewModel m_previewModel`


## Properties

- `Boolean isDimensionListShow`

- `CrisisV2SlotDetailViewModel slotDetailViewModel`

- `CrisisV2BagDetailViewModel bagDetailViewModel`

- `CrisisV2RuneDetailViewModel mapRuneDetailViewModel`

- `ViewType viewType`

- `CrisisV2StageType mapType`

- `String seasonId`

- `CrisisV2MapStageData mapStageData`

- `String currentMapId`

- `String focusNodeId`

- `Int32 switchSeqNum`

- `Int32 jumpSeqNum`

- `Single jumpPos`

- `String avgJumpRuneNodeId`

- `String avgJumpBagId`

- `String avgJumpTreasureId`

- `String avgJumpKeypontId`

- `String areaBgId`

- `Int32 interactId`

- `Int32 tipsSeqNum`

- `Int32 highestScore`

- `CrisisV2MissionProgress missionProgress`

- `Int32 hidePreviewSeqNum`


## Methods

- `Boolean get_isDimensionListShow()`

- `Void set_isDimensionListShow(Boolean)`

- `CrisisV2SlotDetailViewModel get_slotDetailViewModel()`

- `CrisisV2BagDetailViewModel get_bagDetailViewModel()`

- `CrisisV2RuneDetailViewModel get_mapRuneDetailViewModel()`

- `ViewType get_viewType()`

- `CrisisV2StageType get_mapType()`

- `String get_seasonId()`

- `CrisisV2MapStageData get_mapStageData()`

- `String get_currentMapId()`

- `String get_focusNodeId()`

- `Int32 get_switchSeqNum()`

- `Int32 get_jumpSeqNum()`

- `Single get_jumpPos()`

- `String get_avgJumpRuneNodeId()`

- `String get_avgJumpBagId()`

- `String get_avgJumpTreasureId()`

- `String get_avgJumpKeypontId()`

- `String get_areaBgId()`

- `Int32 get_interactId()`

- `Int32 get_tipsSeqNum()`

- `Int32 get_highestScore()`

- `CrisisV2MissionProgress get_missionProgress()`

- `Int32 get_hidePreviewSeqNum()`

- `Void UpdateFocus(TargetType, String, ActionType)`

- `Void UpdatePreviewWithNode(String)`

- `Void UpdatePreviewWithBag(String)`

- `Int32 HidePreview()`

- `Boolean IsInPreview()`

- `CrisisV2PreviewInfo GetPreviewInfo()`

- `Boolean NeedHighLight(String)`

- `Boolean IsBagFocus(String)`

- `Boolean IsNodeFocus(String)`

- `Boolean TryGetTipsInfo(out)`

- `Boolean TryGetExpireTime(Int64, out)`

- `Void LoadMap(String)`

- `Void _LoadMapSelectSlotFromLocalCache(String, String)`

- `Void SaveSelectSlotToLocalCache()`

- `Boolean IsHardScore(Int32)`

- `Void _CalcCurrentScoreList()`

- `Int32 CalcSelectTotalScore()`

- `Void UpdatePlayerData()`

- `Void _UpdateMissionStatus()`

- `Void _UpdateHighestScoreList(BasicMapInfo)`

- `Void _UpdateNode(BasicMapInfo)`

- `Void _UpdateBag(BasicMapInfo)`

- `Void _UpdateStartNodeSet()`

- `Void _UpdateAvailNodeSet()`

- `Void _AddAvailNodeImpl(Queue`1, HashSet`1)`

- `CrisisV2Progress CalcBagScoreProgress(String)`

- `Boolean IsBagAllSelected(String)`

- `CrisisV2MapBagStatus GetBagStatus(String)`

- `CrisisV2MapNodeStatus GetNodeStatus(String)`

- `Boolean _IsHighlightBag(String)`

- `String GetSlotViewBagTutorialKey(String)`

- `Void GetBagViewBagTutorialKey(String, out, out, out)`

- `String GetNodeSlotTutorialKey(String, CrisisV2NodeSlotType)`

- `Boolean _IsNodeSelected(String)`

- `Boolean _IsNodeAvail(String)`

- `Boolean _IsNodeReachable(String)`

- `CrisisV2MapRoadStatus GetRoadStatus(String)`

- `Boolean _IsNodeAutoSelectInBag(String)`

- `Void SelectBag(String)`

- `Void UnselectBag(String)`

- `Void SelectNode(String)`

- `Void _RefreshRuneSelectDetailList()`

- `Void _SelectNode(String)`

- `Void _SelectNodeImpl(Queue`1)`

- `Void UnselectNode(String)`

- `Void _UnselectNode(String)`

- `Void SwitchViewType(Single)`

- `Int32 ChangeViewType(ViewType)`

- `Int32 _ChangeViewType(ViewType)`

- `Void ClearSelectNodes()`

- `Void _ValidationSelectSet()`

- `Void _CalcValidNodeSetImpl(Queue`1, HashSet`1)`

- `Int32 JumpToNode(ViewType, String)`

- `Int32 JumpToBag(ViewType, String)`

- `Int32 _JumpToDetailViewNearestBag(ViewType, ViewType, Single)`

- `Int32 _JumpToNode(ViewType, String)`

- `Int32 _JumpToBag(ViewType, String)`

- `Int32 _JumpToPos(ViewType, Single)`

- `CrisisV2MapRoadStatus _GetNodeRoadStatus(String, String)`

- `CrisisV2MapRoadStatus _GetTreasureRoadStatus(String, String)`

- `CrisisV2MapRoadStatus _GetBagRoadStatus(String)`

- `Void _LoadExclusionGroup(CrisisV2MapDetailData)`

- `Void _LoadHighLightSlot(CrisisV2SeasonConstData)`

- `Void _LoadBag(CrisisV2MapDetailData)`

- `Void _LoadNode(CrisisV2MapDetailData)`

- `Void _LoadRoad(CrisisV2MapDetailData)`

- `Boolean IsNodeExclusion(String)`

- `String _GetExlucsionSelectNodeId(String)`

- `CrisisV2RoadPointStyle GetRoadPointStyle(CrisisV2MapRoadPointData)`

- `Boolean CheckIfCurMapHasBagView()`

- `Boolean _CheckIfCurMapHasBagView()`

- `Void _RefreshSlotRuneSingleViewList()`

- `Void _RefreshSlotRunePackViewList()`

- `String GetOverrideCrisisV2PermBgmEvent()`

- `BattleStageInfo GenerateBattleStageInfo()`

- `Void _RefreshRuneDetailFocusBySelect(TargetType, String, ActionType)`

- `Void _RefreshRuneDetailFocusBySwitch(ViewType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapModel : IHotfixable
{
	private String m_mapId; // 0x10
	private String m_seasonId; // 0x18
	private HashSet`1 m_selectNodeSet; // 0x20
	private HashSet`1 m_startNodeSet; // 0x28
	private HashSet`1 m_availNodeSet; // 0x30
	private List`1 m_currentScoreList; // 0x38
	private List`1 m_highestScoreList; // 0x40
	private Int32 m_highestScore; // 0x48
	private List`1 m_maxScoreList; // 0x50
	private Queue`1 m_tempNodeQueue; // 0x58
	private HashSet`1 m_tempNodeSet; // 0x60
	private HashSet`1 m_tempBagWaitingSet; // 0x68
	private HashSet`1 m_tempBagSuccessSet; // 0x70
	private Dictionary`2 m_roadModelMap; // 0x78
	private Dictionary`2 m_nodeModelMap; // 0x80
	private Dictionary`2 m_bagModelMap; // 0x88
	private Dictionary`2 m_exclusionModelMap; // 0x90
	private CrisisV2SlotDetailViewModel m_slotDetailViewModel; // 0x98
	private CrisisV2BagDetailViewModel m_bagDetailViewModel; // 0xa0
	private CrisisV2MapDetailData m_mapDetailData; // 0xa8
	private CrisisV2MapStageData m_mapStageData; // 0xb0
	private CrisisV2SeasonConstData m_constData; // 0xb8
	private CrisisV2RuneDetailViewModel m_mapRuneDetailViewModel; // 0xc0
	private CrisisV2SeasonInfo m_seasonInfo; // 0xc8
	private Int32 m_bgmHardPoint; // 0xd0
	private Int32 m_hardStyleScoreThreshold; // 0xd4
	private CrisisV2MissionProgress m_missionProgress; // 0xd8
	private String m_avgJumpRuneNodeId; // 0xe8
	private String m_avgJumpTreasureNodeId; // 0xf0
	private String m_avgJumpKeypointNodeId; // 0xf8
	private String m_avgJumpBagId; // 0x100
	private Int32 m_switchViewSeqNum; // 0x108
	private ViewType m_viewType; // 0x10c
	private Int32 m_jumpSeqNum; // 0x110
	private Single m_jumpPos; // 0x114
	private Boolean m_isDimensionListShow; // 0x118
	private CrisisV2FocusModel m_focusModel; // 0x120
	private CrisisV2PreviewModel m_previewModel; // 0x128
	private static DelegateBridge __Hotfix0_get_isDimensionListShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isDimensionListShow; // 0x8
	private static DelegateBridge __Hotfix0_get_maxScoreList; // 0x10
	private static DelegateBridge __Hotfix0_get_highestScoreList; // 0x18
	private static DelegateBridge __Hotfix0_get_roadModelMap; // 0x20
	private static DelegateBridge __Hotfix0_get_nodeModelMap; // 0x28
	private static DelegateBridge __Hotfix0_get_bagModelMap; // 0x30
	private static DelegateBridge __Hotfix0_get_slotDetailViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_bagDetailViewModel; // 0x40
	private static DelegateBridge __Hotfix0_get_mapRuneDetailViewModel; // 0x48
	private static DelegateBridge __Hotfix0_get_viewType; // 0x50
	private static DelegateBridge __Hotfix0_get_currentScoreList; // 0x58
	private static DelegateBridge __Hotfix0_get_mapType; // 0x60
	private static DelegateBridge __Hotfix0_get_seasonId; // 0x68
	private static DelegateBridge __Hotfix0_get_mapStageData; // 0x70
	private static DelegateBridge __Hotfix0_get_currentMapId; // 0x78
	private static DelegateBridge __Hotfix0_get_focusNodeId; // 0x80
	private static DelegateBridge __Hotfix0_get_switchSeqNum; // 0x88
	private static DelegateBridge __Hotfix0_get_jumpSeqNum; // 0x90
	private static DelegateBridge __Hotfix0_get_jumpPos; // 0x98
	private static DelegateBridge __Hotfix0_get_avgJumpRuneNodeId; // 0xa0
	private static DelegateBridge __Hotfix0_get_avgJumpBagId; // 0xa8
	private static DelegateBridge __Hotfix0_get_avgJumpTreasureId; // 0xb0
	private static DelegateBridge __Hotfix0_get_avgJumpKeypontId; // 0xb8
	private static DelegateBridge __Hotfix0_get_areaBgId; // 0xc0
	private static DelegateBridge __Hotfix0_get_interactId; // 0xc8
	private static DelegateBridge __Hotfix0_get_tipsSeqNum; // 0xd0
	private static DelegateBridge __Hotfix0_get_highestScore; // 0xd8
	private static DelegateBridge __Hotfix0_get_missionProgress; // 0xe0
	private static DelegateBridge __Hotfix0_get_hidePreviewSeqNum; // 0xe8
	private static DelegateBridge __Hotfix0_UpdateFocus; // 0xf0
	private static DelegateBridge __Hotfix0_UpdatePreviewWithNode; // 0xf8
	private static DelegateBridge __Hotfix0_UpdatePreviewWithBag; // 0x100
	private static DelegateBridge __Hotfix0_HidePreview; // 0x108
	private static DelegateBridge __Hotfix0_IsInPreview; // 0x110
	private static DelegateBridge __Hotfix0_GetPreviewInfo; // 0x118
	private static DelegateBridge __Hotfix0_NeedHighLight; // 0x120
	private static DelegateBridge __Hotfix0_IsBagFocus; // 0x128
	private static DelegateBridge __Hotfix0_IsNodeFocus; // 0x130
	private static DelegateBridge __Hotfix0_TryGetTipsInfo; // 0x138
	private static DelegateBridge __Hotfix0_TryGetExpireTime; // 0x140
	private static DelegateBridge __Hotfix0_LoadMap; // 0x148
	private static DelegateBridge __Hotfix0__LoadMapSelectSlotFromLocalCache; // 0x150
	private static DelegateBridge __Hotfix0_SaveSelectSlotToLocalCache; // 0x158
	private static DelegateBridge __Hotfix0_IsHardScore; // 0x160
	private static DelegateBridge __Hotfix0__CalcCurrentScoreList; // 0x168
	private static DelegateBridge __Hotfix0_CalcSelectTotalScore; // 0x170
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x178
	private static DelegateBridge __Hotfix0__UpdateMissionStatus; // 0x180
	private static DelegateBridge __Hotfix0__UpdateHighestScoreList; // 0x188
	private static DelegateBridge __Hotfix0__UpdateNode; // 0x190
	private static DelegateBridge __Hotfix0__UpdateBag; // 0x198
	private static DelegateBridge __Hotfix0__UpdateStartNodeSet; // 0x1a0
	private static DelegateBridge __Hotfix0__UpdateAvailNodeSet; // 0x1a8
	private static DelegateBridge __Hotfix0__AddAvailNodeImpl; // 0x1b0
	private static DelegateBridge __Hotfix0_CalcBagScoreProgress; // 0x1b8
	private static DelegateBridge __Hotfix0_IsBagAllSelected; // 0x1c0
	private static DelegateBridge __Hotfix0_GetBagStatus; // 0x1c8
	private static DelegateBridge __Hotfix0_GetNodeStatus; // 0x1d0
	private static DelegateBridge __Hotfix0__IsHighlightBag; // 0x1d8
	private static DelegateBridge __Hotfix0_GetSlotViewBagTutorialKey; // 0x1e0
	private static DelegateBridge __Hotfix0_GetBagViewBagTutorialKey; // 0x1e8
	private static DelegateBridge __Hotfix0_GetNodeSlotTutorialKey; // 0x1f0
	private static DelegateBridge __Hotfix0__IsNodeSelected; // 0x1f8
	private static DelegateBridge __Hotfix0__IsNodeAvail; // 0x200
	private static DelegateBridge __Hotfix0__IsNodeReachable; // 0x208
	private static DelegateBridge __Hotfix0_GetRoadStatus; // 0x210
	private static DelegateBridge __Hotfix0__IsNodeAutoSelectInBag; // 0x218
	private static DelegateBridge __Hotfix0_SelectBag; // 0x220
	private static DelegateBridge __Hotfix0_UnselectBag; // 0x228
	private static DelegateBridge __Hotfix0_SelectNode; // 0x230
	private static DelegateBridge __Hotfix0__RefreshRuneSelectDetailList; // 0x238
	private static DelegateBridge __Hotfix0__SelectNode; // 0x240
	private static DelegateBridge __Hotfix0__SelectNodeImpl; // 0x248
	private static DelegateBridge __Hotfix0_UnselectNode; // 0x250
	private static DelegateBridge __Hotfix0__UnselectNode; // 0x258
	private static DelegateBridge __Hotfix0_SwitchViewType; // 0x260
	private static DelegateBridge __Hotfix0_ChangeViewType; // 0x268
	private static DelegateBridge __Hotfix0__ChangeViewType; // 0x270
	private static DelegateBridge __Hotfix0_ClearSelectNodes; // 0x278
	private static DelegateBridge __Hotfix0__ValidationSelectSet; // 0x280
	private static DelegateBridge __Hotfix0__CalcValidNodeSetImpl; // 0x288
	private static DelegateBridge __Hotfix0_JumpToNode; // 0x290
	private static DelegateBridge __Hotfix0_JumpToBag; // 0x298
	private static DelegateBridge __Hotfix0__JumpToDetailViewNearestBag; // 0x2a0
	private static DelegateBridge __Hotfix0__JumpToNode; // 0x2a8
	private static DelegateBridge __Hotfix0__JumpToBag; // 0x2b0
	private static DelegateBridge __Hotfix0__JumpToPos; // 0x2b8
	private static DelegateBridge __Hotfix0__GetNodeRoadStatus; // 0x2c0
	private static DelegateBridge __Hotfix0__GetTreasureRoadStatus; // 0x2c8
	private static DelegateBridge __Hotfix0__GetBagRoadStatus; // 0x2d0
	private static DelegateBridge __Hotfix0__LoadExclusionGroup; // 0x2d8
	private static DelegateBridge __Hotfix0__LoadHighLightSlot; // 0x2e0
	private static DelegateBridge __Hotfix0__LoadBag; // 0x2e8
	private static DelegateBridge __Hotfix0__LoadNode; // 0x2f0
	private static DelegateBridge __Hotfix0__LoadRoad; // 0x2f8
	private static DelegateBridge __Hotfix0_IsNodeExclusion; // 0x300
	private static DelegateBridge __Hotfix0__GetExlucsionSelectNodeId; // 0x308
	private static DelegateBridge __Hotfix0_GetRoadPointStyle; // 0x310
	private static DelegateBridge __Hotfix0_CheckIfCurMapHasBagView; // 0x318
	private static DelegateBridge __Hotfix0__CheckIfCurMapHasBagView; // 0x320
	private static DelegateBridge __Hotfix0__RefreshSlotRuneSingleViewList; // 0x328
	private static DelegateBridge __Hotfix0__RefreshSlotRunePackViewList; // 0x330
	private static DelegateBridge __Hotfix0_GetOverrideCrisisV2PermBgmEvent; // 0x338
	private static DelegateBridge __Hotfix0_GetSelectedRuneSlotList; // 0x340
	private static DelegateBridge __Hotfix0_GetPackedRuneData; // 0x348
	private static DelegateBridge __Hotfix0_GenerateBattleStageInfo; // 0x350
	private static DelegateBridge __Hotfix0__RefreshRuneDetailFocusBySelect; // 0x358
	private static DelegateBridge __Hotfix0__RefreshRuneDetailFocusBySwitch; // 0x360
	private static DelegateBridge _c__Hotfix0_ctor; // 0x368

	public Boolean isDimensionListShow { get; set; }
	public List`1 maxScoreList { get; }
	public List`1 highestScoreList { get; }
	public Dictionary`2 roadModelMap { get; }
	public Dictionary`2 nodeModelMap { get; }
	public Dictionary`2 bagModelMap { get; }
	public CrisisV2SlotDetailViewModel slotDetailViewModel { get; }
	public CrisisV2BagDetailViewModel bagDetailViewModel { get; }
	public CrisisV2RuneDetailViewModel mapRuneDetailViewModel { get; }
	public ViewType viewType { get; }
	public List`1 currentScoreList { get; }
	public CrisisV2StageType mapType { get; }
	public String seasonId { get; }
	public CrisisV2MapStageData mapStageData { get; }
	public String currentMapId { get; }
	public String focusNodeId { get; }
	public Int32 switchSeqNum { get; }
	public Int32 jumpSeqNum { get; }
	public Single jumpPos { get; }
	public String avgJumpRuneNodeId { get; }
	public String avgJumpBagId { get; }
	public String avgJumpTreasureId { get; }
	public String avgJumpKeypontId { get; }
	public String areaBgId { get; }
	public Int32 interactId { get; }
	public Int32 tipsSeqNum { get; }
	public Int32 highestScore { get; }
	public CrisisV2MissionProgress missionProgress { get; }
	public Int32 hidePreviewSeqNum { get; }

	// RVA: 0x2be9048 VA: 0x7595201048
	public Boolean get_isDimensionListShow() { }
	// RVA: 0x2be90b0 VA: 0x75952010b0
	public Void set_isDimensionListShow(Boolean value) { }
	// RVA: 0x2be9130 VA: 0x7595201130
	public List`1 get_maxScoreList() { }
	// RVA: 0x2be9198 VA: 0x7595201198
	public List`1 get_highestScoreList() { }
	// RVA: 0x2be9200 VA: 0x7595201200
	public Dictionary`2 get_roadModelMap() { }
	// RVA: 0x2be9268 VA: 0x7595201268
	public Dictionary`2 get_nodeModelMap() { }
	// RVA: 0x2be92d0 VA: 0x75952012d0
	public Dictionary`2 get_bagModelMap() { }
	// RVA: 0x2be9338 VA: 0x7595201338
	public CrisisV2SlotDetailViewModel get_slotDetailViewModel() { }
	// RVA: 0x2be93a0 VA: 0x75952013a0
	public CrisisV2BagDetailViewModel get_bagDetailViewModel() { }
	// RVA: 0x2be9408 VA: 0x7595201408
	public CrisisV2RuneDetailViewModel get_mapRuneDetailViewModel() { }
	// RVA: 0x2be9470 VA: 0x7595201470
	public ViewType get_viewType() { }
	// RVA: 0x2be94d8 VA: 0x75952014d8
	public List`1 get_currentScoreList() { }
	// RVA: 0x2be9540 VA: 0x7595201540
	public CrisisV2StageType get_mapType() { }
	// RVA: 0x2be95b8 VA: 0x75952015b8
	public String get_seasonId() { }
	// RVA: 0x2be9620 VA: 0x7595201620
	public CrisisV2MapStageData get_mapStageData() { }
	// RVA: 0x2be9688 VA: 0x7595201688
	public String get_currentMapId() { }
	// RVA: 0x2be96f0 VA: 0x75952016f0
	public String get_focusNodeId() { }
	// RVA: 0x2be98f0 VA: 0x75952018f0
	public Int32 get_switchSeqNum() { }
	// RVA: 0x2be9958 VA: 0x7595201958
	public Int32 get_jumpSeqNum() { }
	// RVA: 0x2be99c0 VA: 0x75952019c0
	public Single get_jumpPos() { }
	// RVA: 0x2be9a28 VA: 0x7595201a28
	public String get_avgJumpRuneNodeId() { }
	// RVA: 0x2be9a90 VA: 0x7595201a90
	public String get_avgJumpBagId() { }
	// RVA: 0x2be9af8 VA: 0x7595201af8
	public String get_avgJumpTreasureId() { }
	// RVA: 0x2be9b60 VA: 0x7595201b60
	public String get_avgJumpKeypontId() { }
	// RVA: 0x2be9bc8 VA: 0x7595201bc8
	public String get_areaBgId() { }
	// RVA: 0x2be9c3c VA: 0x7595201c3c
	public Int32 get_interactId() { }
	// RVA: 0x2be9d14 VA: 0x7595201d14
	public Int32 get_tipsSeqNum() { }
	// RVA: 0x2be9dec VA: 0x7595201dec
	public Int32 get_highestScore() { }
	// RVA: 0x2be9e54 VA: 0x7595201e54
	public CrisisV2MissionProgress get_missionProgress() { }
	// RVA: 0x2be9ec0 VA: 0x7595201ec0
	public Int32 get_hidePreviewSeqNum() { }
	// RVA: 0x2be9f98 VA: 0x7595201f98
	public Void UpdateFocus(TargetType targetType, String targetId, ActionType actionType) { }
	// RVA: 0x2bea1dc VA: 0x75952021dc
	public Void UpdatePreviewWithNode(String previewNodeId) { }
	// RVA: 0x2bea4b8 VA: 0x75952024b8
	public Void UpdatePreviewWithBag(String previewBagId) { }
	// RVA: 0x2beaab8 VA: 0x7595202ab8
	public Int32 HidePreview() { }
	// RVA: 0x2beabfc VA: 0x7595202bfc
	public Boolean IsInPreview() { }
	// RVA: 0x2beacdc VA: 0x7595202cdc
	public CrisisV2PreviewInfo GetPreviewInfo() { }
	// RVA: 0x2beae28 VA: 0x7595202e28
	public Boolean NeedHighLight(String nodeOrBagId) { }
	// RVA: 0x2beaf88 VA: 0x7595202f88
	public Boolean IsBagFocus(String bagId) { }
	// RVA: 0x2beb0f4 VA: 0x75952030f4
	public Boolean IsNodeFocus(String nodeId) { }
	// RVA: 0x2beb1e4 VA: 0x75952031e4
	public Boolean TryGetTipsInfo(out CrisisV2TipsInfo tipsInfo) { }
	// RVA: 0x2beb3fc VA: 0x75952033fc
	public Boolean TryGetExpireTime(Int64 currentTs, out String timeStr) { }
	// RVA: 0x2beb594 VA: 0x7595203594
	public Void LoadMap(String mapId) { }
	// RVA: 0x2bec558 VA: 0x7595204558
	private Void _LoadMapSelectSlotFromLocalCache(String seasonId, String mapId) { }
	// RVA: 0x2becf94 VA: 0x7595204f94
	public Void SaveSelectSlotToLocalCache() { }
	// RVA: 0x2bed1ec VA: 0x75952051ec
	public Boolean IsHardScore(Int32 score) { }
	// RVA: 0x2bec778 VA: 0x7595204778
	private Void _CalcCurrentScoreList() { }
	// RVA: 0x2bed5b4 VA: 0x75952055b4
	public Int32 CalcSelectTotalScore() { }
	// RVA: 0x2bec3b4 VA: 0x75952043b4
	public Void UpdatePlayerData() { }
	// RVA: 0x2bedf2c VA: 0x7595205f2c
	private Void _UpdateMissionStatus() { }
	// RVA: 0x2bed6ac VA: 0x75952056ac
	private Void _UpdateHighestScoreList(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2bed85c VA: 0x759520585c
	private Void _UpdateNode(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2bed968 VA: 0x7595205968
	private Void _UpdateBag(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2beda68 VA: 0x7595205a68
	private Void _UpdateStartNodeSet() { }
	// RVA: 0x2bedbe4 VA: 0x7595205be4
	private Void _UpdateAvailNodeSet() { }
	// RVA: 0x2bee4bc VA: 0x75952064bc
	private Void _AddAvailNodeImpl(Queue`1 nodeQueue, HashSet`1 availNodeSet) { }
	// RVA: 0x2bed270 VA: 0x7595205270
	public CrisisV2Progress CalcBagScoreProgress(String bagId) { }
	// RVA: 0x2bee95c VA: 0x759520695c
	public Boolean IsBagAllSelected(String bagId) { }
	// RVA: 0x2beea04 VA: 0x7595206a04
	public CrisisV2MapBagStatus GetBagStatus(String bagId) { }
	// RVA: 0x2bee71c VA: 0x759520671c
	public CrisisV2MapNodeStatus GetNodeStatus(String nodeId) { }
	// RVA: 0x2beee58 VA: 0x7595206e58
	private Boolean _IsHighlightBag(String bagId) { }
	// RVA: 0x2beeedc VA: 0x7595206edc
	public String GetSlotViewBagTutorialKey(String bagId) { }
	// RVA: 0x2beef9c VA: 0x7595206f9c
	public Void GetBagViewBagTutorialKey(String bagId, out String bagTutorialKey, out String titleTutorialKey, out String detailTutorialKey) { }
	// RVA: 0x2bef114 VA: 0x7595207114
	public String GetNodeSlotTutorialKey(String nodeId, CrisisV2NodeSlotType slotType) { }
	// RVA: 0x2beec34 VA: 0x7595206c34
	private Boolean _IsNodeSelected(String nodeId) { }
	// RVA: 0x2bef250 VA: 0x7595207250
	private Boolean _IsNodeAvail(String nodeId) { }
	// RVA: 0x2beed00 VA: 0x7595206d00
	private Boolean _IsNodeReachable(String nodeId) { }
	// RVA: 0x2bef2f0 VA: 0x75952072f0
	public CrisisV2MapRoadStatus GetRoadStatus(String roadId) { }
	// RVA: 0x2bee80c VA: 0x759520680c
	private Boolean _IsNodeAutoSelectInBag(String nodeId) { }
	// RVA: 0x2bef90c VA: 0x759520790c
	public Void SelectBag(String bagId) { }
	// RVA: 0x2beff68 VA: 0x7595207f68
	public Void UnselectBag(String bagId) { }
	// RVA: 0x2bf0184 VA: 0x7595208184
	public Void SelectNode(String nodeId) { }
	// RVA: 0x2bec6e0 VA: 0x75952046e0
	private Void _RefreshRuneSelectDetailList() { }
	// RVA: 0x2befd34 VA: 0x7595207d34
	private Void _SelectNode(String nodeId) { }
	// RVA: 0x2bf0330 VA: 0x7595208330
	private Void _SelectNodeImpl(Queue`1 nodeQueue) { }
	// RVA: 0x2bf06dc VA: 0x75952086dc
	public Void UnselectNode(String nodeId) { }
	// RVA: 0x2bf00ac VA: 0x75952080ac
	private Void _UnselectNode(String nodeId) { }
	// RVA: 0x2bf076c VA: 0x759520876c
	public Void SwitchViewType(Single jumpPos) { }
	// RVA: 0x2bf0a40 VA: 0x7595208a40
	public Int32 ChangeViewType(ViewType viewType) { }
	// RVA: 0x2bf0ac0 VA: 0x7595208ac0
	private Int32 _ChangeViewType(ViewType viewType) { }
	// RVA: 0x2bf0b68 VA: 0x7595208b68
	public Void ClearSelectNodes() { }
	// RVA: 0x2becc50 VA: 0x7595204c50
	private Void _ValidationSelectSet() { }
	// RVA: 0x2bf0c24 VA: 0x7595208c24
	private Void _CalcValidNodeSetImpl(Queue`1 nodeQueue, HashSet`1 validNodeSet) { }
	// RVA: 0x2bf0e48 VA: 0x7595208e48
	public Int32 JumpToNode(ViewType currentView, String nodeId) { }
	// RVA: 0x2bf0fc0 VA: 0x7595208fc0
	public Int32 JumpToBag(ViewType currentView, String bagId) { }
	// RVA: 0x2bf0814 VA: 0x7595208814
	private Int32 _JumpToDetailViewNearestBag(ViewType srcView, ViewType dstView, Single curPos) { }
	// RVA: 0x2bf0ed4 VA: 0x7595208ed4
	private Int32 _JumpToNode(ViewType currentView, String nodeId) { }
	// RVA: 0x2bf104c VA: 0x759520904c
	private Int32 _JumpToBag(ViewType currentView, String bagId) { }
	// RVA: 0x2bf133c VA: 0x759520933c
	private Int32 _JumpToPos(ViewType currentView, Single targetPos) { }
	// RVA: 0x2bef550 VA: 0x7595207550
	private CrisisV2MapRoadStatus _GetNodeRoadStatus(String startNodeId, String endNodeId) { }
	// RVA: 0x2bef7f0 VA: 0x75952077f0
	private CrisisV2MapRoadStatus _GetTreasureRoadStatus(String bagId, String nodeId) { }
	// RVA: 0x2bef60c VA: 0x759520760c
	private CrisisV2MapRoadStatus _GetBagRoadStatus(String roadId) { }
	// RVA: 0x2bec008 VA: 0x7595204008
	private Void _LoadExclusionGroup(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bec1bc VA: 0x75952041bc
	private Void _LoadHighLightSlot(CrisisV2SeasonConstData constData) { }
	// RVA: 0x2bebe3c VA: 0x7595203e3c
	private Void _LoadBag(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bebc74 VA: 0x7595203c74
	private Void _LoadNode(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bebad4 VA: 0x7595203ad4
	private Void _LoadRoad(CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf1b5c VA: 0x7595209b5c
	public Boolean IsNodeExclusion(String nodeId) { }
	// RVA: 0x2bf1c60 VA: 0x7595209c60
	private String _GetExlucsionSelectNodeId(String groupId) { }
	// RVA: 0x2bf1db4 VA: 0x7595209db4
	public CrisisV2RoadPointStyle GetRoadPointStyle(CrisisV2MapRoadPointData targetData) { }
	// RVA: 0x2bf1e98 VA: 0x7595209e98
	public Boolean CheckIfCurMapHasBagView() { }
	// RVA: 0x2beba54 VA: 0x7595203a54
	private Boolean _CheckIfCurMapHasBagView() { }
	// RVA: 0x2bf0214 VA: 0x7595208214
	private Void _RefreshSlotRuneSingleViewList() { }
	// RVA: 0x2bf02ac VA: 0x75952082ac
	private Void _RefreshSlotRunePackViewList() { }
	// RVA: 0x2bf1f00 VA: 0x7595209f00
	public String GetOverrideCrisisV2PermBgmEvent() { }
	// RVA: 0x2bf2000 VA: 0x759520a000
	public List`1 GetSelectedRuneSlotList() { }
	// RVA: 0x2bf229c VA: 0x759520a29c
	public List`1 GetPackedRuneData() { }
	// RVA: 0x2bf261c VA: 0x759520a61c
	public BattleStageInfo GenerateBattleStageInfo() { }
	// RVA: 0x2bea114 VA: 0x7595202114
	private Void _RefreshRuneDetailFocusBySelect(TargetType targetType, String targetId, ActionType actionType) { }
	// RVA: 0x2bf13e4 VA: 0x75952093e4
	private Void _RefreshRuneDetailFocusBySwitch(ViewType currentViewType, String targetId) { }
	// RVA: 0x2bf2798 VA: 0x759520a798
	public Void .ctor() { }
}
```