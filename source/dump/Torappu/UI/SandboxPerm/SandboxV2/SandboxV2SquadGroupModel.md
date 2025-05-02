# SandboxV2SquadGroupModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `ViewType m_selectViewType`

- `Int32 m_selectSquadIdx`

- `SandboxV2CharRepoModel m_repoModel`

- `Boolean m_showRepo`

- `Boolean m_showNaviPanel`

- `Int32 m_scrollSeqNum`

- `Single m_scrollTweenVal`

- `SandboxV2SquadPanelShowMode m_showMode`

- `Int64 m_timestamp`


## Properties

- `String topicId`

- `Int64 timestamp`

- `Boolean showRepo`

- `Boolean showNaviPanel`

- `Int32 scrollSeqNum`

- `Single scrollTweenVal`

- `SandboxV2CharRepoModel repoModel`

- `ViewType selectViewType`

- `Int32 squadCount`

- `SandboxV2SquadModel selectSquadModel`

- `Boolean isMonthMode`


## Methods

- `String get_topicId()`

- `Int64 get_timestamp()`

- `Boolean get_showRepo()`

- `Boolean get_showNaviPanel()`

- `Int32 get_scrollSeqNum()`

- `Single get_scrollTweenVal()`

- `SandboxV2CharRepoModel get_repoModel()`

- `ViewType get_selectViewType()`

- `Int32 get_squadCount()`

- `SandboxV2SquadModel get_selectSquadModel()`

- `Boolean get_isMonthMode()`

- `SandboxV2SquadModel GetSquadModel(Int32)`

- `SandboxV2CharFoodModel GetCharFood(Int32)`

- `Boolean IsSquadSelect(Int32)`

- `Void SelectRepo()`

- `Void SelectSquad(Int32)`

- `Void InitData(String, Boolean, Boolean, SandboxV2SquadPanelShowMode)`

- `Void ScrollToPos(Single)`

- `Void _InitCharRepo(Boolean)`

- `Void _InitSquadList(String, PlayerSandboxV2)`

- `Void _UpdateCharFood(String)`

- `Void UpdateFoodModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadGroupModel : IHotfixable
{
	private String m_topicId; // 0x10
	private ViewType m_selectViewType; // 0x18
	private Int32 m_selectSquadIdx; // 0x1c
	private List`1 m_squadModelList; // 0x20
	private SandboxV2CharRepoModel m_repoModel; // 0x28
	private Dictionary`2 m_charFoodDict; // 0x30
	private Boolean m_showRepo; // 0x38
	private Boolean m_showNaviPanel; // 0x39
	private Int32 m_scrollSeqNum; // 0x3c
	private Single m_scrollTweenVal; // 0x40
	private SandboxV2SquadPanelShowMode m_showMode; // 0x44
	private Int64 m_timestamp; // 0x48
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_timestamp; // 0x8
	private static DelegateBridge __Hotfix0_get_showRepo; // 0x10
	private static DelegateBridge __Hotfix0_get_showNaviPanel; // 0x18
	private static DelegateBridge __Hotfix0_get_scrollSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_get_scrollTweenVal; // 0x28
	private static DelegateBridge __Hotfix0_get_repoModel; // 0x30
	private static DelegateBridge __Hotfix0_get_selectViewType; // 0x38
	private static DelegateBridge __Hotfix0_get_squadCount; // 0x40
	private static DelegateBridge __Hotfix0_get_selectSquadModel; // 0x48
	private static DelegateBridge __Hotfix0_get_isMonthMode; // 0x50
	private static DelegateBridge __Hotfix0_GetSquadModel; // 0x58
	private static DelegateBridge __Hotfix0_GetCharFood; // 0x60
	private static DelegateBridge __Hotfix0_IsSquadSelect; // 0x68
	private static DelegateBridge __Hotfix0_SelectRepo; // 0x70
	private static DelegateBridge __Hotfix0_SelectSquad; // 0x78
	private static DelegateBridge __Hotfix0_InitData; // 0x80
	private static DelegateBridge __Hotfix0_ScrollToPos; // 0x88
	private static DelegateBridge __Hotfix0__InitCharRepo; // 0x90
	private static DelegateBridge __Hotfix0__InitSquadList; // 0x98
	private static DelegateBridge __Hotfix0__UpdateCharFood; // 0xa0
	private static DelegateBridge __Hotfix0_UpdateFoodModel; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String topicId { get; }
	public Int64 timestamp { get; }
	public Boolean showRepo { get; }
	public Boolean showNaviPanel { get; }
	public Int32 scrollSeqNum { get; }
	public Single scrollTweenVal { get; }
	public SandboxV2CharRepoModel repoModel { get; }
	public ViewType selectViewType { get; }
	public Int32 squadCount { get; }
	public SandboxV2SquadModel selectSquadModel { get; }
	public Boolean isMonthMode { get; }

	// RVA: 0x2610be4 VA: 0x7594c28be4
	public String get_topicId() { }
	// RVA: 0x2610c4c VA: 0x7594c28c4c
	public Int64 get_timestamp() { }
	// RVA: 0x260e7b8 VA: 0x7594c267b8
	public Boolean get_showRepo() { }
	// RVA: 0x2610cb4 VA: 0x7594c28cb4
	public Boolean get_showNaviPanel() { }
	// RVA: 0x2610d1c VA: 0x7594c28d1c
	public Int32 get_scrollSeqNum() { }
	// RVA: 0x2610d84 VA: 0x7594c28d84
	public Single get_scrollTweenVal() { }
	// RVA: 0x260d930 VA: 0x7594c25930
	public SandboxV2CharRepoModel get_repoModel() { }
	// RVA: 0x260dc5c VA: 0x7594c25c5c
	public ViewType get_selectViewType() { }
	// RVA: 0x260eb2c VA: 0x7594c26b2c
	public Int32 get_squadCount() { }
	// RVA: 0x2610dec VA: 0x7594c28dec
	public SandboxV2SquadModel get_selectSquadModel() { }
	// RVA: 0x2610e90 VA: 0x7594c28e90
	public Boolean get_isMonthMode() { }
	// RVA: 0x2610f00 VA: 0x7594c28f00
	public SandboxV2SquadModel GetSquadModel(Int32 squadIdx) { }
	// RVA: 0x2610f9c VA: 0x7594c28f9c
	public SandboxV2CharFoodModel GetCharFood(Int32 charInstId) { }
	// RVA: 0x260ed64 VA: 0x7594c26d64
	public Boolean IsSquadSelect(Int32 squadIdx) { }
	// RVA: 0x2611038 VA: 0x7594c29038
	public Void SelectRepo() { }
	// RVA: 0x26110b4 VA: 0x7594c290b4
	public Void SelectSquad(Int32 squadIdx) { }
	// RVA: 0x261138c VA: 0x7594c2938c
	public Void InitData(String topicId, Boolean showRepo, Boolean showNaviPanel, SandboxV2SquadPanelShowMode showMode) { }
	// RVA: 0x2611b20 VA: 0x7594c29b20
	public Void ScrollToPos(Single scrollPos) { }
	// RVA: 0x261176c VA: 0x7594c2976c
	private Void _InitCharRepo(Boolean showRepo) { }
	// RVA: 0x2611584 VA: 0x7594c29584
	private Void _InitSquadList(String topicId, PlayerSandboxV2 playerSandbox) { }
	// RVA: 0x2611844 VA: 0x7594c29844
	private Void _UpdateCharFood(String topicId) { }
	// RVA: 0x261216c VA: 0x7594c2a16c
	public Void UpdateFoodModel() { }
	// RVA: 0x26121d8 VA: 0x7594c2a1d8
	public Void .ctor() { }
}
```