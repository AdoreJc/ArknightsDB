# SandboxV2AdminMainSciencePanelModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isInDungeon`

- `Int32 m_developPointsHasCount`

- `Boolean m_isAllDevelopFinish`

- `Single m_developNodeMaxYAxis`

- `Single m_developNodeYPosOffset`

- `Int32 m_firstNotLightUpRow`

- `String <topicId>k__BackingField`

- `SandboxV2AdminMainScienceType <curScienceType>k__BackingField`

- `String <selectedNodeId>k__BackingField`

- `Boolean <initShow>k__BackingField`

- `Boolean <needRefreshNode>k__BackingField`


## Properties

- `String topicId`

- `SandboxV2AdminMainScienceType curScienceType`

- `String selectedNodeId`

- `Boolean initShow`

- `Boolean needRefreshNode`

- `Int32 pointsRemain`

- `Single currentNodeMaxWidth`

- `SandboxV2AdminMainScienceItemViewModel curNodeItem`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `SandboxV2AdminMainScienceType get_curScienceType()`

- `Void set_curScienceType(SandboxV2AdminMainScienceType)`

- `String get_selectedNodeId()`

- `Void set_selectedNodeId(String)`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `Boolean get_needRefreshNode()`

- `Void set_needRefreshNode(Boolean)`

- `Int32 get_pointsRemain()`

- `Single get_currentNodeMaxWidth()`

- `Void LoadData(String)`

- `Void _LoadDevelopmentBaseDatas(Dictionary`2)`

- `Void _UpdateContentWidthByNode(SandboxV2DevelopmentData)`

- `Void _LoadDevelopmentDatas(Dictionary`2)`

- `SandboxV2AdminMainScienceType _GetScienceTypeByTechType(SandboxV2DevelopmentType)`

- `Void _LoadLineSegmentDatas(List`1)`

- `Void RefreshPlayerData()`

- `Boolean IfNodeCanDevelop(String)`

- `Boolean CleanSelected()`

- `Single GetScienceProgressByType(SandboxV2AdminMainScienceType)`

- `Void _RefreshDevelopTotalUsedDots(Tech)`

- `Void _RefreshDevelopNodesStatus(Tech, Int32)`

- `Boolean _CheckIfPreNodeLighted(String, Tech)`

- `Void _RefreshDevelopLineSegmentsState(Int32)`

- `Void _RefreshDevelopProgress(Tech)`

- `Boolean _CheckIfSegmentUnlock(SandboxV2DevelopmentLineSegmentData)`

- `Boolean _IsNodeLighted(String)`

- `SandboxV2AdminMainScienceType _GetNodeType(String)`

- `SandboxV2AdminMainScienceItemViewModel _GetNodeViewModel(String)`

- `SANDBOX_DEVELOP_NODE_LIGHT_STATE _GetDevelopNodeLightState(Boolean, Boolean, Boolean, Int32)`

- `SandboxV2AdminMainScienceItemViewModel _GetScienceItemViewModelById(String)`

- `Boolean SetSelectType(SandboxV2AdminMainScienceType, Boolean)`

- `SandboxV2AdminMainScienceItemViewModel get_curNodeItem()`

- `Int32 GetCurrentScienceTypeTotalPoints()`

- `Int32 GetCurrentScienceTypePointsUsed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainSciencePanelModel : IHotfixable
{
	private static readonly Single X_START_OFFSET; // 0x0
	private static readonly Single X_END_OFFSET; // 0x4
	private static readonly Single X_AXIS_UNIT_SIZE; // 0x8
	private static readonly Single Y_AXIS_UNIT_SIZE; // 0xc
	private static readonly Single Y_NODE_AXIS_TOP_OFFSET; // 0x10
	private Boolean m_isInDungeon; // 0x10
	private Int32 m_developPointsHasCount; // 0x14
	private Boolean m_isAllDevelopFinish; // 0x18
	private Single m_developNodeMaxYAxis; // 0x1c
	private Single m_developNodeYPosOffset; // 0x20
	private Int32 m_firstNotLightUpRow; // 0x24
	private String <topicId>k__BackingField; // 0x28
	private SandboxV2AdminMainScienceType <curScienceType>k__BackingField; // 0x30
	private String <selectedNodeId>k__BackingField; // 0x38
	private Boolean <initShow>k__BackingField; // 0x40
	private Boolean <needRefreshNode>k__BackingField; // 0x41
	public ListDict`2 itemViewModelDatas; // 0x48
	public List`1 lineSegmentModels; // 0x50
	public Dictionary`2 itemViewModelsDict; // 0x58
	public Dictionary`2 lineSegDict; // 0x60
	public Dictionary`2 scienceProgressDict; // 0x68
	public Dictionary`2 sciencePointsUsedDict; // 0x70
	public Dictionary`2 sciencePointsTotalDict; // 0x78
	public Dictionary`2 scienceContentSizeDict; // 0x80
	private static DelegateBridge __Hotfix0_get_topicId; // 0x18
	private static DelegateBridge __Hotfix0_set_topicId; // 0x20
	private static DelegateBridge __Hotfix0_get_curScienceType; // 0x28
	private static DelegateBridge __Hotfix0_set_curScienceType; // 0x30
	private static DelegateBridge __Hotfix0_get_selectedNodeId; // 0x38
	private static DelegateBridge __Hotfix0_set_selectedNodeId; // 0x40
	private static DelegateBridge __Hotfix0_get_initShow; // 0x48
	private static DelegateBridge __Hotfix0_set_initShow; // 0x50
	private static DelegateBridge __Hotfix0_get_needRefreshNode; // 0x58
	private static DelegateBridge __Hotfix0_set_needRefreshNode; // 0x60
	private static DelegateBridge __Hotfix0_get_pointsRemain; // 0x68
	private static DelegateBridge __Hotfix0_get_currentNodeMaxWidth; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x78
	private static DelegateBridge __Hotfix0__LoadDevelopmentBaseDatas; // 0x80
	private static DelegateBridge __Hotfix0__UpdateContentWidthByNode; // 0x88
	private static DelegateBridge __Hotfix0__LoadDevelopmentDatas; // 0x90
	private static DelegateBridge __Hotfix0__GetScienceTypeByTechType; // 0x98
	private static DelegateBridge __Hotfix0__LoadLineSegmentDatas; // 0xa0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0xa8
	private static DelegateBridge __Hotfix0_IfNodeCanDevelop; // 0xb0
	private static DelegateBridge __Hotfix0_CleanSelected; // 0xb8
	private static DelegateBridge __Hotfix0_GetScienceProgressByType; // 0xc0
	private static DelegateBridge __Hotfix0__RefreshDevelopTotalUsedDots; // 0xc8
	private static DelegateBridge __Hotfix0__RefreshDevelopNodesStatus; // 0xd0
	private static DelegateBridge __Hotfix0__CheckIfPreNodeLighted; // 0xd8
	private static DelegateBridge __Hotfix0__RefreshDevelopLineSegmentsState; // 0xe0
	private static DelegateBridge __Hotfix0__RefreshDevelopProgress; // 0xe8
	private static DelegateBridge __Hotfix0__CheckIfSegmentUnlock; // 0xf0
	private static DelegateBridge __Hotfix0__IsNodeLighted; // 0xf8
	private static DelegateBridge __Hotfix0__GetNodeType; // 0x100
	private static DelegateBridge __Hotfix0__GetNodeViewModel; // 0x108
	private static DelegateBridge __Hotfix0__GetScienceListByType; // 0x110
	private static DelegateBridge __Hotfix0__GetDevelopNodeLightState; // 0x118
	private static DelegateBridge __Hotfix0__GetScienceItemViewModelById; // 0x120
	private static DelegateBridge __Hotfix0_SetSelectType; // 0x128
	private static DelegateBridge __Hotfix0_get_curNodeItem; // 0x130
	private static DelegateBridge __Hotfix0_GetCurrentScienceList; // 0x138
	private static DelegateBridge __Hotfix0_GetCurrentScienceTypeTotalPoints; // 0x140
	private static DelegateBridge __Hotfix0_GetCurrentScienceTypePointsUsed; // 0x148
	private static DelegateBridge __Hotfix0_GetCurrentLineList; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public String topicId { get; set; }
	public SandboxV2AdminMainScienceType curScienceType { get; set; }
	public String selectedNodeId { get; set; }
	public Boolean initShow { get; set; }
	public Boolean needRefreshNode { get; set; }
	public Int32 pointsRemain { get; }
	public Single currentNodeMaxWidth { get; }
	public SandboxV2AdminMainScienceItemViewModel curNodeItem { get; }

	// RVA: 0x24ddaec VA: 0x7594af5aec
	public String get_topicId() { }
	// RVA: 0x24e3144 VA: 0x7594afb144
	private Void set_topicId(String value) { }
	// RVA: 0x24e31d8 VA: 0x7594afb1d8
	public SandboxV2AdminMainScienceType get_curScienceType() { }
	// RVA: 0x24e3250 VA: 0x7594afb250
	private Void set_curScienceType(SandboxV2AdminMainScienceType value) { }
	// RVA: 0x24e32dc VA: 0x7594afb2dc
	public String get_selectedNodeId() { }
	// RVA: 0x24ddf3c VA: 0x7594af5f3c
	public Void set_selectedNodeId(String value) { }
	// RVA: 0x24e3354 VA: 0x7594afb354
	public Boolean get_initShow() { }
	// RVA: 0x24e33cc VA: 0x7594afb3cc
	private Void set_initShow(Boolean value) { }
	// RVA: 0x24e345c VA: 0x7594afb45c
	public Boolean get_needRefreshNode() { }
	// RVA: 0x24e2c78 VA: 0x7594afac78
	public Void set_needRefreshNode(Boolean value) { }
	// RVA: 0x24e34d4 VA: 0x7594afb4d4
	public Int32 get_pointsRemain() { }
	// RVA: 0x24e354c VA: 0x7594afb54c
	public Single get_currentNodeMaxWidth() { }
	// RVA: 0x24e2680 VA: 0x7594afa680
	public Void LoadData(String topicId) { }
	// RVA: 0x24e3604 VA: 0x7594afb604
	private Void _LoadDevelopmentBaseDatas(Dictionary`2 developmentDatas) { }
	// RVA: 0x24e437c VA: 0x7594afc37c
	private Void _UpdateContentWidthByNode(SandboxV2DevelopmentData nodeData) { }
	// RVA: 0x24e39f4 VA: 0x7594afb9f4
	private Void _LoadDevelopmentDatas(Dictionary`2 developmentDatas) { }
	// RVA: 0x24e44e4 VA: 0x7594afc4e4
	private SandboxV2AdminMainScienceType _GetScienceTypeByTechType(SandboxV2DevelopmentType techType) { }
	// RVA: 0x24e3f3c VA: 0x7594afbf3c
	private Void _LoadLineSegmentDatas(List`1 lineDatas) { }
	// RVA: 0x24e2aa8 VA: 0x7594afaaa8
	public Void RefreshPlayerData() { }
	// RVA: 0x24e2f4c VA: 0x7594afaf4c
	public Boolean IfNodeCanDevelop(String developId) { }
	// RVA: 0x24e51c0 VA: 0x7594afd1c0
	public Boolean CleanSelected() { }
	// RVA: 0x24e527c VA: 0x7594afd27c
	public Single GetScienceProgressByType(SandboxV2AdminMainScienceType techType) { }
	// RVA: 0x24e484c VA: 0x7594afc84c
	private Void _RefreshDevelopTotalUsedDots(Tech tech) { }
	// RVA: 0x24e49e0 VA: 0x7594afc9e0
	private Void _RefreshDevelopNodesStatus(Tech tech, Int32 baseLevel) { }
	// RVA: 0x24e5394 VA: 0x7594afd394
	private Boolean _CheckIfPreNodeLighted(String preNodeId, Tech tech) { }
	// RVA: 0x24e4c68 VA: 0x7594afcc68
	private Void _RefreshDevelopLineSegmentsState(Int32 playerBaseLevel) { }
	// RVA: 0x24e4db8 VA: 0x7594afcdb8
	private Void _RefreshDevelopProgress(Tech tech) { }
	// RVA: 0x24e5590 VA: 0x7594afd590
	private Boolean _CheckIfSegmentUnlock(SandboxV2DevelopmentLineSegmentData segmentData) { }
	// RVA: 0x24e5774 VA: 0x7594afd774
	private Boolean _IsNodeLighted(String techId) { }
	// RVA: 0x24e45ec VA: 0x7594afc5ec
	private SandboxV2AdminMainScienceType _GetNodeType(String techId) { }
	// RVA: 0x24e4724 VA: 0x7594afc724
	private SandboxV2AdminMainScienceItemViewModel _GetNodeViewModel(String techId) { }
	// RVA: 0x24e58a8 VA: 0x7594afd8a8
	private ListDict`2 _GetScienceListByType(SandboxV2AdminMainScienceType techType) { }
	// RVA: 0x24e549c VA: 0x7594afd49c
	private SANDBOX_DEVELOP_NODE_LIGHT_STATE _GetDevelopNodeLightState(Boolean lighted, Boolean levelLimited, Boolean frontLighted, Int32 tokenCost) { }
	// RVA: 0x24e56b0 VA: 0x7594afd6b0
	private SandboxV2AdminMainScienceItemViewModel _GetScienceItemViewModelById(String techId) { }
	// RVA: 0x24e28f8 VA: 0x7594afa8f8
	public Boolean SetSelectType(SandboxV2AdminMainScienceType scienceType, Boolean isInit) { }
	// RVA: 0x24dd68c VA: 0x7594af568c
	public SandboxV2AdminMainScienceItemViewModel get_curNodeItem() { }
	// RVA: 0x24e59c0 VA: 0x7594afd9c0
	public ListDict`2 GetCurrentScienceList() { }
	// RVA: 0x24e5a44 VA: 0x7594afda44
	public Int32 GetCurrentScienceTypeTotalPoints() { }
	// RVA: 0x24e5afc VA: 0x7594afdafc
	public Int32 GetCurrentScienceTypePointsUsed() { }
	// RVA: 0x24e5bb4 VA: 0x7594afdbb4
	public List`1 GetCurrentLineList() { }
	// RVA: 0x24e5cb8 VA: 0x7594afdcb8
	public Void .ctor() { }
	// RVA: 0x24e5f84 VA: 0x7594afdf84
	private static Void .cctor() { }
}
```