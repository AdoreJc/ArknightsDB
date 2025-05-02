# RL03ScrollReportEndingFrameViewModelPlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Methods

- `String _ExportZoneVisionModuleAdditionInfo(String, Zone)`

- `String _ExportNodeChaosModuleValueChangeInfo(Node)`

- `String _ExportNodeChaosModuleGradeUpGainInfo(Node, Dictionary`2)`

- `String _ExportNodeChaosModuleGradeDownLostInfo(Node, Dictionary`2)`

- `String _GetChaosChangesStr(List`1, Dictionary`2)`

- `String _ExportNodeVisionModuleValueUpInfo(Node)`

- `String _ExportNodeVisionModuleGradeUpInfo(Node)`

- `String _ExportNodeVisionModuleValueDownInfo(Node)`

- `String _ExportNodeVisionModuleGradeDownInfo(Node)`

- `Boolean <>xLuaBaseProxy_CheckRogueEndingTextValid()`

- `String <>xLuaBaseProxy_GetSummaryActor()`

- `IRoguelikeScrollEndingText <>xLuaBaseProxy_GetEndingText()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ScrollReportEndingFrameViewModelPlugin : RoguelikeScrollReportEndingFrameViewModelPlugin
{
	private static DelegateBridge __Hotfix0_CheckRogueEndingTextValid; // 0x0
	private static DelegateBridge __Hotfix0_GetSummaryActor; // 0x8
	private static DelegateBridge __Hotfix0_GetEndingText; // 0x10
	private static DelegateBridge __Hotfix0_ExportZoneAdditionInfo; // 0x18
	private static DelegateBridge __Hotfix0_ExportNodeSceneAdditionInfo; // 0x20
	private static DelegateBridge __Hotfix0_ExportNodeBattleAdditionInfo; // 0x28
	private static DelegateBridge __Hotfix0_ExportNodeSceneInfo; // 0x30
	private static DelegateBridge __Hotfix0_ExportNodeBattleInfo; // 0x38
	private static DelegateBridge __Hotfix0_ExportNodeGotAdditionInfo; // 0x40
	private static DelegateBridge __Hotfix0_ExportNodeModuleChangeInfo; // 0x48
	private static DelegateBridge __Hotfix0_ExportNodeModuleBetweenInfo; // 0x50
	private static DelegateBridge __Hotfix0__ExportZoneTotemModuleAdditionInfo; // 0x58
	private static DelegateBridge __Hotfix0__ExportZoneVisionModuleAdditionInfo; // 0x60
	private static DelegateBridge __Hotfix0__ExportNodeChaosModuleValueChangeInfo; // 0x68
	private static DelegateBridge __Hotfix0__ExportNodeChaosModuleGradeChangeInfo; // 0x70
	private static DelegateBridge __Hotfix0__ExportNodeChaosModuleGradeUpGainInfo; // 0x78
	private static DelegateBridge __Hotfix0__ExportNodeChaosModuleGradeDownLostInfo; // 0x80
	private static DelegateBridge __Hotfix0__GetChaosChangesStr; // 0x88
	private static DelegateBridge __Hotfix0__ExportNodeVisionModuleValueUpInfo; // 0x90
	private static DelegateBridge __Hotfix0__ExportNodeVisionModuleGradeUpInfo; // 0x98
	private static DelegateBridge __Hotfix0__ExportNodeVisionModuleValueDownInfo; // 0xa0
	private static DelegateBridge __Hotfix0__ExportNodeVisionModuleGradeDownInfo; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x2b98e38 VA: 0x75951b0e38
	public override Boolean CheckRogueEndingTextValid() { }
	// RVA: 0x2b98ec8 VA: 0x75951b0ec8
	public override String GetSummaryActor() { }
	// RVA: 0x2b98f54 VA: 0x75951b0f54
	public override IRoguelikeScrollEndingText GetEndingText() { }
	// RVA: 0x2b98fd8 VA: 0x75951b0fd8
	public override List`1 ExportZoneAdditionInfo(String topicId, Zone zoneInfo) { }
	// RVA: 0x2b995c4 VA: 0x75951b15c4
	public override List`1 ExportNodeSceneAdditionInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b99784 VA: 0x75951b1784
	public override List`1 ExportNodeBattleAdditionInfo(Node nodeInfo) { }
	// RVA: 0x2b99988 VA: 0x75951b1988
	public override List`1 ExportNodeSceneInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b99cac VA: 0x75951b1cac
	public override List`1 ExportNodeBattleInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b99f50 VA: 0x75951b1f50
	public override List`1 ExportNodeGotAdditionInfo(String topicId, Got got) { }
	// RVA: 0x2b9a0dc VA: 0x75951b20dc
	public override List`1 ExportNodeModuleChangeInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b9a940 VA: 0x75951b2940
	public override List`1 ExportNodeModuleBetweenInfo(Node nodeInfo) { }
	// RVA: 0x2b99194 VA: 0x75951b1194
	private List`1 _ExportZoneTotemModuleAdditionInfo(Zone zoneInfo) { }
	// RVA: 0x2b993cc VA: 0x75951b13cc
	private String _ExportZoneVisionModuleAdditionInfo(String topicId, Zone zoneInfo) { }
	// RVA: 0x2b9a39c VA: 0x75951b239c
	private String _ExportNodeChaosModuleValueChangeInfo(Node nodeInfo) { }
	// RVA: 0x2b9a4f0 VA: 0x75951b24f0
	private List`1 _ExportNodeChaosModuleGradeChangeInfo(String topicId, Node nodeInfo) { }
	// RVA: 0x2b9ad10 VA: 0x75951b2d10
	private String _ExportNodeChaosModuleGradeUpGainInfo(Node nodeInfo, Dictionary`2 chaosDatas) { }
	// RVA: 0x2b9ae24 VA: 0x75951b2e24
	private String _ExportNodeChaosModuleGradeDownLostInfo(Node nodeInfo, Dictionary`2 chaosDatas) { }
	// RVA: 0x2b9af38 VA: 0x75951b2f38
	private String _GetChaosChangesStr(List`1 chaosIdList, Dictionary`2 chaosDatas) { }
	// RVA: 0x2b9a744 VA: 0x75951b2744
	private String _ExportNodeVisionModuleValueUpInfo(Node nodeInfo) { }
	// RVA: 0x2b9a85c VA: 0x75951b285c
	private String _ExportNodeVisionModuleGradeUpInfo(Node nodeInfo) { }
	// RVA: 0x2b9ab18 VA: 0x75951b2b18
	private String _ExportNodeVisionModuleValueDownInfo(Node nodeInfo) { }
	// RVA: 0x2b9ac30 VA: 0x75951b2c30
	private String _ExportNodeVisionModuleGradeDownInfo(Node nodeInfo) { }
	// RVA: 0x2b9b1e4 VA: 0x75951b31e4
	public Void .ctor() { }
	// RVA: 0x2b9b254 VA: 0x75951b3254
	private Boolean <>xLuaBaseProxy_CheckRogueEndingTextValid() { }
	// RVA: 0x2b9b25c VA: 0x75951b325c
	private String <>xLuaBaseProxy_GetSummaryActor() { }
	// RVA: 0x2b9b264 VA: 0x75951b3264
	private IRoguelikeScrollEndingText <>xLuaBaseProxy_GetEndingText() { }
	// RVA: 0x2b9b26c VA: 0x75951b326c
	private List`1 <>xLuaBaseProxy_ExportZoneAdditionInfo(String P0, Zone P1) { }
	// RVA: 0x2b9b274 VA: 0x75951b3274
	private List`1 <>xLuaBaseProxy_ExportNodeSceneAdditionInfo(String P0, Node P1) { }
	// RVA: 0x2b9b27c VA: 0x75951b327c
	private List`1 <>xLuaBaseProxy_ExportNodeBattleAdditionInfo(Node P0) { }
	// RVA: 0x2b9b284 VA: 0x75951b3284
	private List`1 <>xLuaBaseProxy_ExportNodeSceneInfo(String P0, Node P1) { }
	// RVA: 0x2b9b28c VA: 0x75951b328c
	private List`1 <>xLuaBaseProxy_ExportNodeBattleInfo(String P0, Node P1) { }
	// RVA: 0x2b9b294 VA: 0x75951b3294
	private List`1 <>xLuaBaseProxy_ExportNodeGotAdditionInfo(String P0, Got P1) { }
	// RVA: 0x2b9b29c VA: 0x75951b329c
	private List`1 <>xLuaBaseProxy_ExportNodeModuleChangeInfo(String P0, Node P1) { }
	// RVA: 0x2b9b2a4 VA: 0x75951b32a4
	private List`1 <>xLuaBaseProxy_ExportNodeModuleBetweenInfo(Node P0) { }
}
```