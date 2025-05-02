# SiracusaMapViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String m_groupId`

- `Boolean m_isRetro`

- `Act21SideData m_actData`

- `SiracusaData m_siracusaData`

- `Int64 m_enterTimeStamp`

- `SiracusaMapMapNodeViewModel m_selectedNodeViewModel`


## Properties

- `SpecialStageType stageSelectedType`

- `SiracusaMapMapNodeViewModel selectedNodeViewModel`

- `StageViewModel selectedStageHard`

- `StageViewModel selectedStageNormal`

- `StageViewModel selectedStage`


## Methods

- `Void Init(InitParam)`

- `Void UpdateModelWithPlayerData(PlayerSiracusaMap)`

- `Void ReBuildNodeViewModels(UpdateParam)`

- `Boolean SelectPoint(String, Boolean)`

- `Boolean IsSelectingNormal()`

- `NormalStageRelation GetNormalStageRelation(String)`

- `String TryGetCurPointIdWithStageId(String)`

- `Void _LoadGameDataZoneInfo()`

- `Void _LoadValidStageData()`

- `Void _UpdateShowAreaAndPoints(PlayerSiracusaMap)`

- `Void _LoadStageInfoFromPlayer()`

- `Void _ReloadZoneInfoMap()`

- `Void _CalcTaskNodesWhenRebuild(UpdateParam, ref, ref, out)`

- `Void _ReloadNodeViewModelWithPointInfo(List`1, List`1, Dictionary`2)`

- `String _GetCornerIconIdFromZone(StageViewModel)`

- `SpecialStageType get_stageSelectedType()`

- `SiracusaMapMapNodeViewModel get_selectedNodeViewModel()`

- `StageViewModel FindNormalStageFromSpecialStage(String, SpecialStageType)`

- `StageViewModel FindSpecialStageFromNormal(String, SpecialStageType)`

- `StageViewModel GetStageByType(SpecialStageType)`

- `StageViewModel get_selectedStageHard()`

- `StageViewModel get_selectedStageNormal()`

- `StageViewModel get_selectedStage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapViewModel : IHotfixable, IStageSelectHandler
{
	private String m_groupId; // 0x10
	private Boolean m_isRetro; // 0x18
	private Act21SideData m_actData; // 0x20
	private SiracusaData m_siracusaData; // 0x28
	private Int64 m_enterTimeStamp; // 0x30
	private Dictionary`2 m_mapZoneInfoDict; // 0x38
	private List`1 m_normalStageList; // 0x40
	private List`1 m_taskStageList; // 0x48
	private ListDict`2 m_stageViewModels; // 0x50
	private Dictionary`2 m_lockedAreaMap; // 0x58
	private List`1 m_showPointIdList; // 0x60
	private ListDict`2 m_pointNormalStageInfoMap; // 0x68
	private Dictionary`2 m_normalStageRelations; // 0x70
	private ListDict`2 m_pointTaskStageInfoMap; // 0x78
	private Dictionary`2 m_zoneStageInfoMap; // 0x80
	private List`1 m_taskPointIds; // 0x88
	private Dictionary`2 m_nodeViewModels; // 0x90
	private SiracusaMapMapNodeViewModel m_selectedNodeViewModel; // 0x98
	private static DelegateBridge __Hotfix0_get_mapZoneInfoViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_zoneStageInfoMap; // 0x8
	private static DelegateBridge __Hotfix0_get_lockedAreaMap; // 0x10
	private static DelegateBridge __Hotfix0_get_nodeViewModels; // 0x18
	private static DelegateBridge __Hotfix0_get_curTaskPointIds; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_UpdateModelWithPlayerData; // 0x30
	private static DelegateBridge __Hotfix0_ReBuildNodeViewModels; // 0x38
	private static DelegateBridge __Hotfix0_SelectPoint; // 0x40
	private static DelegateBridge __Hotfix0_IsSelectingNormal; // 0x48
	private static DelegateBridge __Hotfix0_GetNormalStageRelation; // 0x50
	private static DelegateBridge __Hotfix0_TranverseNormalStages; // 0x58
	private static DelegateBridge __Hotfix0_TryGetCurPointIdWithStageId; // 0x60
	private static DelegateBridge __Hotfix0__LoadGameDataZoneInfo; // 0x68
	private static DelegateBridge __Hotfix0__LoadValidStageData; // 0x70
	private static DelegateBridge __Hotfix0__UpdateShowAreaAndPoints; // 0x78
	private static DelegateBridge __Hotfix0__LoadStageInfoFromPlayer; // 0x80
	private static DelegateBridge __Hotfix0__ReloadZoneInfoMap; // 0x88
	private static DelegateBridge __Hotfix0__CalcTaskNodesWhenRebuild; // 0x90
	private static DelegateBridge __Hotfix0__CalcSmallMapTaskNodesWhenRebuild; // 0x98
	private static DelegateBridge __Hotfix0__CalcBigMapTaskNodesWhenRebuild; // 0xa0
	private static DelegateBridge __Hotfix0__ReloadNodeViewModelWithPointInfo; // 0xa8
	private static DelegateBridge __Hotfix0__GeneStageInfoViewModel; // 0xb0
	private static DelegateBridge __Hotfix0__LoadRankNum; // 0xb8
	private static DelegateBridge __Hotfix0__GetCornerIconIdFromZone; // 0xc0
	private static DelegateBridge __Hotfix0_get_stageSelectedType; // 0xc8
	private static DelegateBridge __Hotfix0_get_selectedNodeViewModel; // 0xd0
	private static DelegateBridge __Hotfix0_FindNormalStageFromSpecialStage; // 0xd8
	private static DelegateBridge __Hotfix0_FindSpecialStageFromNormal; // 0xe0
	private static DelegateBridge __Hotfix0_GetStageByType; // 0xe8
	private static DelegateBridge __Hotfix0_get_selectedStageHard; // 0xf0
	private static DelegateBridge __Hotfix0_get_selectedStageNormal; // 0xf8
	private static DelegateBridge __Hotfix0_get_selectedStage; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public Dictionary`2 mapZoneInfoViewModels { get; }
	public Dictionary`2 zoneStageInfoMap { get; }
	public Dictionary`2 lockedAreaMap { get; }
	public Dictionary`2 nodeViewModels { get; }
	public List`1 curTaskPointIds { get; }
	public SpecialStageType stageSelectedType { get; }
	public SiracusaMapMapNodeViewModel selectedNodeViewModel { get; }
	public StageViewModel selectedStageHard { get; }
	public StageViewModel selectedStageNormal { get; }
	public StageViewModel selectedStage { get; }

	// RVA: 0x2418284 VA: 0x7594a30284
	public Dictionary`2 get_mapZoneInfoViewModels() { }
	// RVA: 0x2418958 VA: 0x7594a30958
	public Dictionary`2 get_zoneStageInfoMap() { }
	// RVA: 0x24141f0 VA: 0x7594a2c1f0
	public Dictionary`2 get_lockedAreaMap() { }
	// RVA: 0x2414258 VA: 0x7594a2c258
	public Dictionary`2 get_nodeViewModels() { }
	// RVA: 0x241a1a0 VA: 0x7594a321a0
	public List`1 get_curTaskPointIds() { }
	// RVA: 0x241819c VA: 0x7594a3019c
	public Void Init(InitParam param) { }
	// RVA: 0x241951c VA: 0x7594a3151c
	public Void UpdateModelWithPlayerData(PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x24195ac VA: 0x7594a315ac
	public Void ReBuildNodeViewModels(UpdateParam updateParam) { }
	// RVA: 0x2418694 VA: 0x7594a30694
	public Boolean SelectPoint(String pointId, Boolean needChangeNodeShowSelected) { }
	// RVA: 0x2417a10 VA: 0x7594a2fa10
	public Boolean IsSelectingNormal() { }
	// RVA: 0x2417508 VA: 0x7594a2f508
	public NormalStageRelation GetNormalStageRelation(String stageId) { }
	// RVA: 0x2417438 VA: 0x7594a2f438
	public IEnumerator`1 TranverseNormalStages(Func`2 picker) { }
	// RVA: 0x2419878 VA: 0x7594a31878
	public String TryGetCurPointIdWithStageId(String stageId) { }
	// RVA: 0x241a208 VA: 0x7594a32208
	private Void _LoadGameDataZoneInfo() { }
	// RVA: 0x241a580 VA: 0x7594a32580
	private Void _LoadValidStageData() { }
	// RVA: 0x241ae54 VA: 0x7594a32e54
	private Void _UpdateShowAreaAndPoints(PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x241b128 VA: 0x7594a33128
	private Void _LoadStageInfoFromPlayer() { }
	// RVA: 0x241b708 VA: 0x7594a33708
	private Void _ReloadZoneInfoMap() { }
	// RVA: 0x241bb6c VA: 0x7594a33b6c
	private Void _CalcTaskNodesWhenRebuild(UpdateParam updateParam, ref List`1 showPoints, ref List`1 selectNodes, out Dictionary`2 taskNodeMap) { }
	// RVA: 0x241c4d8 VA: 0x7594a344d8
	private static Void _CalcSmallMapTaskNodesWhenRebuild(UpdateParam updateParam, out List`1 showPoints, ref List`1 selectNodes, ref Dictionary`2 taskNodeMap) { }
	// RVA: 0x241cca0 VA: 0x7594a34ca0
	private static Void _CalcBigMapTaskNodesWhenRebuild(UpdateParam updateParam, ref Dictionary`2 taskNodeMap) { }
	// RVA: 0x241bde8 VA: 0x7594a33de8
	private Void _ReloadNodeViewModelWithPointInfo(List`1 pointIds, List`1 selectPoints, Dictionary`2 taskNodes) { }
	// RVA: 0x241c33c VA: 0x7594a3433c
	private static SiracusaMapStageInfoViewModel _GeneStageInfoViewModel(Dictionary`2 playerStages, StageViewModelStruct stageViewModelStruct) { }
	// RVA: 0x241d260 VA: 0x7594a35260
	private static Int32 _LoadRankNum(StageViewModelStruct stageViewModelStruct, PlayerStageState normalPlayerStageState, PlayerStageState hardPlayerStageState) { }
	// RVA: 0x241d198 VA: 0x7594a35198
	private String _GetCornerIconIdFromZone(StageViewModel stageViewModel) { }
	// RVA: 0x241d354 VA: 0x7594a35354
	public SpecialStageType get_stageSelectedType() { }
	// RVA: 0x24173d0 VA: 0x7594a2f3d0
	public SiracusaMapMapNodeViewModel get_selectedNodeViewModel() { }
	// RVA: 0x241d3d4 VA: 0x7594a353d4
	public StageViewModel FindNormalStageFromSpecialStage(String notNormalStageId, SpecialStageType sourceStageType) { }
	// RVA: 0x241d4f4 VA: 0x7594a354f4
	public StageViewModel FindSpecialStageFromNormal(String normalStageId, SpecialStageType targetStageType) { }
	// RVA: 0x241d61c VA: 0x7594a3561c
	public StageViewModel GetStageByType(SpecialStageType stageType) { }
	// RVA: 0x241d6cc VA: 0x7594a356cc
	public StageViewModel get_selectedStageHard() { }
	// RVA: 0x241d74c VA: 0x7594a3574c
	public StageViewModel get_selectedStageNormal() { }
	// RVA: 0x2417a90 VA: 0x7594a2fa90
	public StageViewModel get_selectedStage() { }
	// RVA: 0x2419d94 VA: 0x7594a31d94
	public Void .ctor() { }
}
```