# CrisisV2MapKeypointNodeModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2ChallengeNodeData m_keypointServerData`

- `NodeState m_nodeState`


## Methods

- `Boolean <>xLuaBaseProxy_get_isSpecialNode()`

- `Boolean <>xLuaBaseProxy_get_canCoverRoad()`

- `Boolean <>xLuaBaseProxy_get_isAutoSelect()`

- `Boolean <>xLuaBaseProxy_get_canStartFrom()`

- `CrisisV2RoadPointStyle <>xLuaBaseProxy_get_roadPointStyle()`

- `NodeState <>xLuaBaseProxy_get_currentState()`

- `Boolean <>xLuaBaseProxy_get_needShowPreview()`

- `String <>xLuaBaseProxy_get_previewTitle()`

- `String <>xLuaBaseProxy_get_previewDesc()`

- `ViewType <>xLuaBaseProxy_get_highlightView()`

- `Int32 <>xLuaBaseProxy_get_requiredSelectCount()`

- `Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo)`

- `Void <>xLuaBaseProxy_OnLoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapKeypointNodeModel : CrisisV2MapNodeModel
{
	private CrisisV2ChallengeNodeData m_keypointServerData; // 0x30
	private NodeState m_nodeState; // 0x38
	private List`1 m_previewRewards; // 0x40
	private static DelegateBridge __Hotfix0_get_isSpecialNode; // 0x0
	private static DelegateBridge __Hotfix0_get_canCoverRoad; // 0x8
	private static DelegateBridge __Hotfix0_get_isAutoSelect; // 0x10
	private static DelegateBridge __Hotfix0_get_canStartFrom; // 0x18
	private static DelegateBridge __Hotfix0_get_roadPointStyle; // 0x20
	private static DelegateBridge __Hotfix0_get_currentState; // 0x28
	private static DelegateBridge __Hotfix0_get_needShowPreview; // 0x30
	private static DelegateBridge __Hotfix0_get_previewTitle; // 0x38
	private static DelegateBridge __Hotfix0_get_previewDesc; // 0x40
	private static DelegateBridge __Hotfix0_get_rewards; // 0x48
	private static DelegateBridge __Hotfix0_get_relatedNodeOrBagIds; // 0x50
	private static DelegateBridge __Hotfix0_get_highlightView; // 0x58
	private static DelegateBridge __Hotfix0_get_requiredSelectCount; // 0x60
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x68
	private static DelegateBridge __Hotfix0_OnLoadData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override Boolean isSpecialNode { get; }
	public override Boolean canCoverRoad { get; }
	public override Boolean isAutoSelect { get; }
	public override Boolean canStartFrom { get; }
	public override CrisisV2RoadPointStyle roadPointStyle { get; }
	public override NodeState currentState { get; }
	public override Boolean needShowPreview { get; }
	public override String previewTitle { get; }
	public override String previewDesc { get; }
	public override List`1 rewards { get; }
	public override List`1 relatedNodeOrBagIds { get; }
	public override ViewType highlightView { get; }
	public override Int32 requiredSelectCount { get; }

	// RVA: 0x2be7b8c VA: 0x75951ffb8c
	public override Boolean get_isSpecialNode() { }
	// RVA: 0x2be7bf4 VA: 0x75951ffbf4
	public override Boolean get_canCoverRoad() { }
	// RVA: 0x2be7c5c VA: 0x75951ffc5c
	public override Boolean get_isAutoSelect() { }
	// RVA: 0x2be7cc4 VA: 0x75951ffcc4
	public override Boolean get_canStartFrom() { }
	// RVA: 0x2be7d34 VA: 0x75951ffd34
	public override CrisisV2RoadPointStyle get_roadPointStyle() { }
	// RVA: 0x2be7db4 VA: 0x75951ffdb4
	public override NodeState get_currentState() { }
	// RVA: 0x2be7e1c VA: 0x75951ffe1c
	public override Boolean get_needShowPreview() { }
	// RVA: 0x2be7e84 VA: 0x75951ffe84
	public override String get_previewTitle() { }
	// RVA: 0x2be7f18 VA: 0x75951fff18
	public override String get_previewDesc() { }
	// RVA: 0x2be7fac VA: 0x75951fffac
	public override List`1 get_rewards() { }
	// RVA: 0x2be8208 VA: 0x7595200208
	public override List`1 get_relatedNodeOrBagIds() { }
	// RVA: 0x2be8280 VA: 0x7595200280
	public override ViewType get_highlightView() { }
	// RVA: 0x2be82e8 VA: 0x75952002e8
	public override Int32 get_requiredSelectCount() { }
	// RVA: 0x2be8360 VA: 0x7595200360
	public override Void UpdatePlayerData(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2be8440 VA: 0x7595200440
	protected override Void OnLoadData() { }
	// RVA: 0x2be6f7c VA: 0x75951fef7c
	public Void .ctor() { }
	// RVA: 0x2be8510 VA: 0x7595200510
	private Boolean <>xLuaBaseProxy_get_isSpecialNode() { }
	// RVA: 0x2be8514 VA: 0x7595200514
	private Boolean <>xLuaBaseProxy_get_canCoverRoad() { }
	// RVA: 0x2be8518 VA: 0x7595200518
	private Boolean <>xLuaBaseProxy_get_isAutoSelect() { }
	// RVA: 0x2be851c VA: 0x759520051c
	private Boolean <>xLuaBaseProxy_get_canStartFrom() { }
	// RVA: 0x2be8520 VA: 0x7595200520
	private CrisisV2RoadPointStyle <>xLuaBaseProxy_get_roadPointStyle() { }
	// RVA: 0x2be8524 VA: 0x7595200524
	private NodeState <>xLuaBaseProxy_get_currentState() { }
	// RVA: 0x2be8528 VA: 0x7595200528
	private Boolean <>xLuaBaseProxy_get_needShowPreview() { }
	// RVA: 0x2be852c VA: 0x759520052c
	private String <>xLuaBaseProxy_get_previewTitle() { }
	// RVA: 0x2be8530 VA: 0x7595200530
	private String <>xLuaBaseProxy_get_previewDesc() { }
	// RVA: 0x2be8534 VA: 0x7595200534
	private List`1 <>xLuaBaseProxy_get_rewards() { }
	// RVA: 0x2be8538 VA: 0x7595200538
	private List`1 <>xLuaBaseProxy_get_relatedNodeOrBagIds() { }
	// RVA: 0x2be853c VA: 0x759520053c
	private ViewType <>xLuaBaseProxy_get_highlightView() { }
	// RVA: 0x2be8540 VA: 0x7595200540
	private Int32 <>xLuaBaseProxy_get_requiredSelectCount() { }
	// RVA: 0x2be8544 VA: 0x7595200544
	private Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo P0) { }
	// RVA: 0x2be8548 VA: 0x7595200548
	private Void <>xLuaBaseProxy_OnLoadData() { }
}
```