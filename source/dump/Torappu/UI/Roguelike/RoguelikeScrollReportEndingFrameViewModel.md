# RoguelikeScrollReportEndingFrameViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Brief brief`

- `Initial initial`

- `Int32 zoneArrayIndex`

- `Int32 zoneNodeArrayIndex`

- `RoguelikeScrollReportEndingFrameViewModelPlugin m_modelPlugin`


## Methods

- `Boolean CheckRogueEndingTextValid()`

- `String GetSummaryActor()`

- `String GetPlayerName()`

- `IRoguelikeScrollEndingText GetEndingText()`

- `Void LoadData()`

- `Void InjectPlugin(RoguelikeScrollReportEndingFrameViewModelPlugin)`

- `Void _TryAddDisplayItemToList(ReportItemType, List`1)`

- `EndingReportDisplayItem _CreateDisplayItem(ReportItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeScrollReportEndingFrameViewModel : RoguelikeEndingFrameViewModel
{
	public Brief brief; // 0x28
	public Initial initial; // 0x30
	public List`1 zones; // 0x38
	public Int32 zoneArrayIndex; // 0x40
	public Int32 zoneNodeArrayIndex; // 0x44
	public List`1 troopChars; // 0x48
	private RoguelikeScrollReportEndingFrameViewModelPlugin m_modelPlugin; // 0x50
	private static DelegateBridge __Hotfix0_CheckRogueEndingTextValid; // 0x0
	private static DelegateBridge __Hotfix0_GetSummaryActor; // 0x8
	private static DelegateBridge __Hotfix0_GetPlayerName; // 0x10
	private static DelegateBridge __Hotfix0_GetEndingText; // 0x18
	private static DelegateBridge __Hotfix0_ExportZoneAdditionInfo; // 0x20
	private static DelegateBridge __Hotfix0_ExportNodeSceneAdditionInfo; // 0x28
	private static DelegateBridge __Hotfix0_ExportNodeBattleAdditionInfo; // 0x30
	private static DelegateBridge __Hotfix0_ExportNodeSceneInfo; // 0x38
	private static DelegateBridge __Hotfix0_ExportNodeAlchemyInfo; // 0x40
	private static DelegateBridge __Hotfix0_ExportNodeBattleInfo; // 0x48
	private static DelegateBridge __Hotfix0_ExportNodeGotAdditionRelicInfo; // 0x50
	private static DelegateBridge __Hotfix0_ExportNodeGotAdditionInfo; // 0x58
	private static DelegateBridge __Hotfix0_ExportShopNodeRecycleAdditionInfo; // 0x60
	private static DelegateBridge __Hotfix0_ExportNodeModuleChangeInfo; // 0x68
	private static DelegateBridge __Hotfix0_ExportNodeModuleBetweenInfo; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x78
	private static DelegateBridge __Hotfix0_Export; // 0x80
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x88
	private static DelegateBridge __Hotfix0__TryAddDisplayItemToList; // 0x90
	private static DelegateBridge __Hotfix0__CreateDisplayItem; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2a8709c VA: 0x759509f09c
	public Boolean CheckRogueEndingTextValid() { }
	// RVA: 0x2a83d58 VA: 0x759509bd58
	public String GetSummaryActor() { }
	// RVA: 0x2a83e08 VA: 0x759509be08
	public String GetPlayerName() { }
	// RVA: 0x2a8711c VA: 0x759509f11c
	public IRoguelikeScrollEndingText GetEndingText() { }
	// RVA: 0x2a8a094 VA: 0x75950a2094
	public List`1 ExportZoneAdditionInfo(Zone zoneInfo) { }
	// RVA: 0x2a8c3c4 VA: 0x75950a43c4
	public List`1 ExportNodeSceneAdditionInfo(Node nodeInfo) { }
	// RVA: 0x2a8c478 VA: 0x75950a4478
	public List`1 ExportNodeBattleAdditionInfo(Node nodeInfo) { }
	// RVA: 0x2a8c1a8 VA: 0x75950a41a8
	public List`1 ExportNodeSceneInfo(Node nodeInfo) { }
	// RVA: 0x2a8c25c VA: 0x75950a425c
	public List`1 ExportNodeAlchemyInfo(Node nodeInfo) { }
	// RVA: 0x2a8c310 VA: 0x75950a4310
	public List`1 ExportNodeBattleInfo(Node nodeInfo) { }
	// RVA: 0x2a8c5e4 VA: 0x75950a45e4
	public List`1 ExportNodeGotAdditionRelicInfo(Got nodeGot, Node nodeInfo) { }
	// RVA: 0x2a8c6a8 VA: 0x75950a46a8
	public List`1 ExportNodeGotAdditionInfo(Got nodeGot) { }
	// RVA: 0x2a8c52c VA: 0x75950a452c
	public List`1 ExportShopNodeRecycleAdditionInfo(ShopNode shop) { }
	// RVA: 0x2a8c760 VA: 0x75950a4760
	public List`1 ExportNodeModuleChangeInfo(Node nodeInfo) { }
	// RVA: 0x2a8c818 VA: 0x75950a4818
	public List`1 ExportNodeModuleBetweenInfo(Node nodeInfo) { }
	// RVA: 0x2a82950 VA: 0x759509a950
	public Void LoadData() { }
	// RVA: 0x2a829d8 VA: 0x759509a9d8
	public List`1 Export() { }
	// RVA: 0x2a856f4 VA: 0x759509d6f4
	public Void InjectPlugin(RoguelikeScrollReportEndingFrameViewModelPlugin plugin) { }
	// RVA: 0x2a8c93c VA: 0x75950a493c
	private Void _TryAddDisplayItemToList(ReportItemType reportItemType, List`1 outputList) { }
	// RVA: 0x2a8ca58 VA: 0x75950a4a58
	private EndingReportDisplayItem _CreateDisplayItem(ReportItemType reportItemType) { }
	// RVA: 0x2a8cd00 VA: 0x75950a4d00
	public Void .ctor() { }
}
```