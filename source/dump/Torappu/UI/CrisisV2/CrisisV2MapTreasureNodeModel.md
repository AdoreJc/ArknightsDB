# CrisisV2MapTreasureNodeModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2RewardNodeData m_treasureServerData`

- `RewardInfo m_rewardInfo`


## Properties

- `ItemBundle reward`

- `Int32 currentVal`

- `Int32 totalVal`


## Methods

- `ItemBundle get_reward()`

- `Int32 get_currentVal()`

- `Int32 get_totalVal()`

- `Boolean <>xLuaBaseProxy_get_isSpecialNode()`

- `NodeState <>xLuaBaseProxy_get_currentState()`

- `Boolean <>xLuaBaseProxy_get_needShowPreview()`

- `String <>xLuaBaseProxy_get_previewTitle()`

- `String <>xLuaBaseProxy_get_previewDesc()`

- `ViewType <>xLuaBaseProxy_get_highlightView()`

- `Int32 <>xLuaBaseProxy_get_requiredSelectCount()`

- `Void <>xLuaBaseProxy_OnLoadData()`

- `Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapTreasureNodeModel : CrisisV2MapNodeModel
{
	private CrisisV2RewardNodeData m_treasureServerData; // 0x30
	private RewardInfo m_rewardInfo; // 0x38
	private List`1 m_previewRewards; // 0x40
	private static DelegateBridge __Hotfix0_get_reward; // 0x0
	private static DelegateBridge __Hotfix0_get_isSpecialNode; // 0x8
	private static DelegateBridge __Hotfix0_get_currentState; // 0x10
	private static DelegateBridge __Hotfix0_get_needShowPreview; // 0x18
	private static DelegateBridge __Hotfix0_get_previewTitle; // 0x20
	private static DelegateBridge __Hotfix0_get_previewDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_rewards; // 0x30
	private static DelegateBridge __Hotfix0_get_relatedNodeOrBagIds; // 0x38
	private static DelegateBridge __Hotfix0_get_highlightView; // 0x40
	private static DelegateBridge __Hotfix0_get_requiredSelectCount; // 0x48
	private static DelegateBridge __Hotfix0_get_currentVal; // 0x50
	private static DelegateBridge __Hotfix0_get_totalVal; // 0x58
	private static DelegateBridge __Hotfix0_OnLoadData; // 0x60
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public ItemBundle reward { get; }
	public override Boolean isSpecialNode { get; }
	public override NodeState currentState { get; }
	public override Boolean needShowPreview { get; }
	public override String previewTitle { get; }
	public override String previewDesc { get; }
	public override List`1 rewards { get; }
	public override List`1 relatedNodeOrBagIds { get; }
	public override ViewType highlightView { get; }
	public override Int32 requiredSelectCount { get; }
	public Int32 currentVal { get; }
	public Int32 totalVal { get; }

	// RVA: 0x2be7280 VA: 0x75951ff280
	public ItemBundle get_reward() { }
	// RVA: 0x2be72f8 VA: 0x75951ff2f8
	public override Boolean get_isSpecialNode() { }
	// RVA: 0x2be7360 VA: 0x75951ff360
	public override NodeState get_currentState() { }
	// RVA: 0x2be73d8 VA: 0x75951ff3d8
	public override Boolean get_needShowPreview() { }
	// RVA: 0x2be7440 VA: 0x75951ff440
	public override String get_previewTitle() { }
	// RVA: 0x2be74d4 VA: 0x75951ff4d4
	public override String get_previewDesc() { }
	// RVA: 0x2be7568 VA: 0x75951ff568
	public override List`1 get_rewards() { }
	// RVA: 0x2be7724 VA: 0x75951ff724
	public override List`1 get_relatedNodeOrBagIds() { }
	// RVA: 0x2be779c VA: 0x75951ff79c
	public override ViewType get_highlightView() { }
	// RVA: 0x2be7804 VA: 0x75951ff804
	public override Int32 get_requiredSelectCount() { }
	// RVA: 0x2be787c VA: 0x75951ff87c
	public Int32 get_currentVal() { }
	// RVA: 0x2be78f4 VA: 0x75951ff8f4
	public Int32 get_totalVal() { }
	// RVA: 0x2be7968 VA: 0x75951ff968
	protected override Void OnLoadData() { }
	// RVA: 0x2be7a38 VA: 0x75951ffa38
	public override Void UpdatePlayerData(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2be6fe8 VA: 0x75951fefe8
	public Void .ctor() { }
	// RVA: 0x2be7b60 VA: 0x75951ffb60
	private Boolean <>xLuaBaseProxy_get_isSpecialNode() { }
	// RVA: 0x2be7b64 VA: 0x75951ffb64
	private NodeState <>xLuaBaseProxy_get_currentState() { }
	// RVA: 0x2be7b68 VA: 0x75951ffb68
	private Boolean <>xLuaBaseProxy_get_needShowPreview() { }
	// RVA: 0x2be7b6c VA: 0x75951ffb6c
	private String <>xLuaBaseProxy_get_previewTitle() { }
	// RVA: 0x2be7b70 VA: 0x75951ffb70
	private String <>xLuaBaseProxy_get_previewDesc() { }
	// RVA: 0x2be7b74 VA: 0x75951ffb74
	private List`1 <>xLuaBaseProxy_get_rewards() { }
	// RVA: 0x2be7b78 VA: 0x75951ffb78
	private List`1 <>xLuaBaseProxy_get_relatedNodeOrBagIds() { }
	// RVA: 0x2be7b7c VA: 0x75951ffb7c
	private ViewType <>xLuaBaseProxy_get_highlightView() { }
	// RVA: 0x2be7b80 VA: 0x75951ffb80
	private Int32 <>xLuaBaseProxy_get_requiredSelectCount() { }
	// RVA: 0x2be7b84 VA: 0x75951ffb84
	private Void <>xLuaBaseProxy_OnLoadData() { }
	// RVA: 0x2be7b88 VA: 0x75951ffb88
	private Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo P0) { }
}
```