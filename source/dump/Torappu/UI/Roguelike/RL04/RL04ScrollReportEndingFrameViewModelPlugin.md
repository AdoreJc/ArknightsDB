# RL04ScrollReportEndingFrameViewModelPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Methods

- `String _ExportNodeLostFragmentInfo(String, Node)`

- `String _ExportNodeFragmentBagStatusInfo(Node)`

- `String _MergeItemsNameToLongStr(List`1)`

- `Boolean <>xLuaBaseProxy_CheckRogueEndingTextValid()`

- `String <>xLuaBaseProxy_GetSummaryActor()`

- `IRoguelikeScrollEndingText <>xLuaBaseProxy_GetEndingText()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ScrollReportEndingFrameViewModelPlugin : RoguelikeScrollReportEndingFrameViewModelPlugin
{
	private static DelegateBridge __Hotfix0_CheckRogueEndingTextValid; // 0x0
	private static DelegateBridge __Hotfix0_GetSummaryActor; // 0x8
	private static DelegateBridge __Hotfix0_GetEndingText; // 0x10
	private static DelegateBridge __Hotfix0_ExportZoneAdditionInfo; // 0x18
	private static DelegateBridge __Hotfix0_ExportNodeSceneAdditionInfo; // 0x20
	private static DelegateBridge __Hotfix0_ExportNodeBattleAdditionInfo; // 0x28
	private static DelegateBridge __Hotfix0_ExportNodeSceneInfo; // 0x30
	private static DelegateBridge __Hotfix0_ExportNodeAlchemyInfo; // 0x38
	private static DelegateBridge __Hotfix0_ExportShopNodeRecycleAdditionInfo; // 0x40
	private static DelegateBridge __Hotfix0_ExportNodeBattleInfo; // 0x48
	private static DelegateBridge __Hotfix0_ExportNodeGotAdditionRelicInfo; // 0x50
	private static DelegateBridge __Hotfix0_ExportNodeGotAdditionInfo; // 0x58
	private static DelegateBridge __Hotfix0_ExportNodeModuleChangeInfo; // 0x60
	private static DelegateBridge __Hotfix0__ExportNodeAlchemyInfo; // 0x68
	private static DelegateBridge __Hotfix0__ExportNodeUseFragmentInfo; // 0x70
	private static DelegateBridge __Hotfix0__ExportNodeLostFragmentInfo; // 0x78
	private static DelegateBridge __Hotfix0__ExportNodeFragmentBagStatusInfo; // 0x80
	private static DelegateBridge __Hotfix0__ExportNodeDisasterInfo; // 0x88
	private static DelegateBridge __Hotfix0__MergeItemsNameToLongStr; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x2b18738 VA: 0x7595130738
	public override Boolean CheckRogueEndingTextValid() { }
	// RVA: 0x2b187c8 VA: 0x75951307c8
	public override String GetSummaryActor() { }
	// RVA: 0x2b18854 VA: 0x7595130854
	public override IRoguelikeScrollEndingText GetEndingText() { }
	// RVA: 0x2b188d8 VA: 0x75951308d8
	public override List`1 ExportZoneAdditionInfo(String topicId, Zone zoneInfo) { }
	// RVA: 0x2b18edc VA: 0x7595130edc
	public override List`1 ExportNodeSceneAdditionInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b1906c VA: 0x759513106c
	public override List`1 ExportNodeBattleAdditionInfo(Node nodeInfo) { }
	// RVA: 0x2b19314 VA: 0x7595131314
	public override List`1 ExportNodeSceneInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b19638 VA: 0x7595131638
	public override List`1 ExportNodeAlchemyInfo(String topicId, Node node) { }
	// RVA: 0x2b19b6c VA: 0x7595131b6c
	public override List`1 ExportShopNodeRecycleAdditionInfo(String topicId, ShopNode shop) { }
	// RVA: 0x2b19e94 VA: 0x7595131e94
	public override List`1 ExportNodeBattleInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b1a140 VA: 0x7595132140
	public override List`1 ExportNodeGotAdditionRelicInfo(String topicId, Got got, Node nodeInfo) { }
	// RVA: 0x2b1a458 VA: 0x7595132458
	public override List`1 ExportNodeGotAdditionInfo(String topicId, Got got) { }
	// RVA: 0x2b1a5e4 VA: 0x75951325e4
	public override List`1 ExportNodeModuleChangeInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b19868 VA: 0x7595131868
	private List`1 _ExportNodeAlchemyInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b1a868 VA: 0x7595132868
	private List`1 _ExportNodeUseFragmentInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b1acd0 VA: 0x7595132cd0
	private String _ExportNodeLostFragmentInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b1af88 VA: 0x7595132f88
	private String _ExportNodeFragmentBagStatusInfo(Node nodeInfo) { }
	// RVA: 0x2b1b0c8 VA: 0x75951330c8
	private List`1 _ExportNodeDisasterInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b18e00 VA: 0x7595130e00
	private String _MergeItemsNameToLongStr(List`1 itemNameList) { }
	// RVA: 0x2b1b590 VA: 0x7595133590
	public Void .ctor() { }
	// RVA: 0x2b1b600 VA: 0x7595133600
	private Boolean <>xLuaBaseProxy_CheckRogueEndingTextValid() { }
	// RVA: 0x2b1b608 VA: 0x7595133608
	private String <>xLuaBaseProxy_GetSummaryActor() { }
	// RVA: 0x2b1b610 VA: 0x7595133610
	private IRoguelikeScrollEndingText <>xLuaBaseProxy_GetEndingText() { }
	// RVA: 0x2b1b618 VA: 0x7595133618
	private List`1 <>xLuaBaseProxy_ExportZoneAdditionInfo(String P0, Zone P1) { }
	// RVA: 0x2b1b620 VA: 0x7595133620
	private List`1 <>xLuaBaseProxy_ExportNodeSceneAdditionInfo(String P0, Node P1) { }
	// RVA: 0x2b1b628 VA: 0x7595133628
	private List`1 <>xLuaBaseProxy_ExportNodeBattleAdditionInfo(Node P0) { }
	// RVA: 0x2b1b630 VA: 0x7595133630
	private List`1 <>xLuaBaseProxy_ExportNodeSceneInfo(String P0, Node P1) { }
	// RVA: 0x2b1b638 VA: 0x7595133638
	private List`1 <>xLuaBaseProxy_ExportNodeAlchemyInfo(String P0, Node P1) { }
	// RVA: 0x2b1b640 VA: 0x7595133640
	private List`1 <>xLuaBaseProxy_ExportShopNodeRecycleAdditionInfo(String P0, ShopNode P1) { }
	// RVA: 0x2b1b648 VA: 0x7595133648
	private List`1 <>xLuaBaseProxy_ExportNodeBattleInfo(String P0, Node P1) { }
	// RVA: 0x2b1b650 VA: 0x7595133650
	private List`1 <>xLuaBaseProxy_ExportNodeGotAdditionRelicInfo(String P0, Got P1, Node P2) { }
	// RVA: 0x2b1b658 VA: 0x7595133658
	private List`1 <>xLuaBaseProxy_ExportNodeGotAdditionInfo(String P0, Got P1) { }
	// RVA: 0x2b1b660 VA: 0x7595133660
	private List`1 <>xLuaBaseProxy_ExportNodeModuleChangeInfo(String P0, Node P1) { }
}
```