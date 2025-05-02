# DeepSeaRPTreasureNodeModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `TreasureNodeData treasureData`

- `TreasureStatus treasureStatus`

- `MissionData m_missionData`

- `EventData m_endEventData`


## Properties

- `MissionData missionData`


## Methods

- `MissionData get_missionData()`

- `Boolean IsMissionComplete()`

- `MissionCalcState GetMissionProgress()`

- `Void _FetchMissionData()`

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Boolean <>xLuaBaseProxy_IsGrey()`

- `Boolean <>xLuaBaseProxy_ShowLockOnMap()`

- `Boolean <>xLuaBaseProxy_HasEntryTrackPoint()`

- `Boolean <>xLuaBaseProxy_HasTrackPoint()`

- `EventData <>xLuaBaseProxy_GetEndEvent()`

- `Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea)`

- `String <>xLuaBaseProxy_GetMapIconName()`

- `String <>xLuaBaseProxy_GetDetailIconName()`

- `String <>xLuaBaseProxy_GetImgDecoName()`

- `String <>xLuaBaseProxy_GetTitleText()`

- `String <>xLuaBaseProxy_GetSpecialPicId()`

- `String <>xLuaBaseProxy_GetNodePicId()`

- `Boolean <>xLuaBaseProxy_ShouldCustomizeLasDes()`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTreasureNodeModel : DeepSeaRPNodeModel
{
	public TreasureNodeData treasureData; // 0x30
	public TreasureStatus treasureStatus; // 0x38
	private MissionData m_missionData; // 0x40
	private EventData m_endEventData; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_get_missionData; // 0x8
	private static DelegateBridge __Hotfix0_IsMissionComplete; // 0x10
	private static DelegateBridge __Hotfix0_GetMissionProgress; // 0x18
	private static DelegateBridge __Hotfix0__FetchMissionData; // 0x20
	private static DelegateBridge __Hotfix0_IsGrey; // 0x28
	private static DelegateBridge __Hotfix0_ShowLockOnMap; // 0x30
	private static DelegateBridge __Hotfix0_HasEntryTrackPoint; // 0x38
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x40
	private static DelegateBridge __Hotfix0_GetEndEvent; // 0x48
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x50
	private static DelegateBridge __Hotfix0_GetMapIconName; // 0x58
	private static DelegateBridge __Hotfix0_GetDetailIconName; // 0x60
	private static DelegateBridge __Hotfix0_GetImgDecoName; // 0x68
	private static DelegateBridge __Hotfix0_GetTitleText; // 0x70
	private static DelegateBridge __Hotfix0_GetSpecialPicId; // 0x78
	private static DelegateBridge __Hotfix0_GetNodePicId; // 0x80
	private static DelegateBridge __Hotfix0_GetDescList; // 0x88
	private static DelegateBridge __Hotfix0_ShouldCustomizeLasDes; // 0x90
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public MissionData missionData { get; }

	// RVA: 0x29d562c VA: 0x7594fed62c
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d5778 VA: 0x7594fed778
	public MissionData get_missionData() { }
	// RVA: 0x29d5968 VA: 0x7594fed968
	public Boolean IsMissionComplete() { }
	// RVA: 0x29d5aec VA: 0x7594fedaec
	public MissionCalcState GetMissionProgress() { }
	// RVA: 0x29d57f0 VA: 0x7594fed7f0
	private Void _FetchMissionData() { }
	// RVA: 0x29d5c14 VA: 0x7594fedc14
	public override Boolean IsGrey() { }
	// RVA: 0x29d5c84 VA: 0x7594fedc84
	public override Boolean ShowLockOnMap() { }
	// RVA: 0x29d5d18 VA: 0x7594fedd18
	public override Boolean HasEntryTrackPoint() { }
	// RVA: 0x29d5da8 VA: 0x7594fedda8
	public override Boolean HasTrackPoint() { }
	// RVA: 0x29d5e50 VA: 0x7594fede50
	public override EventData GetEndEvent() { }
	// RVA: 0x29d5eb8 VA: 0x7594fedeb8
	public override Void UpdateNodeStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29d5f84 VA: 0x7594fedf84
	public override String GetMapIconName() { }
	// RVA: 0x29d60e4 VA: 0x7594fee0e4
	public override String GetDetailIconName() { }
	// RVA: 0x29d6244 VA: 0x7594fee244
	public override String GetImgDecoName() { }
	// RVA: 0x29d63a4 VA: 0x7594fee3a4
	public override String GetTitleText() { }
	// RVA: 0x29d6424 VA: 0x7594fee424
	public override String GetSpecialPicId() { }
	// RVA: 0x29d6498 VA: 0x7594fee498
	public override String GetNodePicId() { }
	// RVA: 0x29d650c VA: 0x7594fee50c
	public override List`1 GetDescList() { }
	// RVA: 0x29d6580 VA: 0x7594fee580
	public override Boolean ShouldCustomizeLasDes() { }
	// RVA: 0x29d65e8 VA: 0x7594fee5e8
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29d4604 VA: 0x7594fec604
	public Void .ctor() { }
	// RVA: 0x29d666c VA: 0x7594fee66c
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d6670 VA: 0x7594fee670
	private Boolean <>xLuaBaseProxy_IsGrey() { }
	// RVA: 0x29d6674 VA: 0x7594fee674
	private Boolean <>xLuaBaseProxy_ShowLockOnMap() { }
	// RVA: 0x29d6678 VA: 0x7594fee678
	private Boolean <>xLuaBaseProxy_HasEntryTrackPoint() { }
	// RVA: 0x29d667c VA: 0x7594fee67c
	private Boolean <>xLuaBaseProxy_HasTrackPoint() { }
	// RVA: 0x29d6680 VA: 0x7594fee680
	private EventData <>xLuaBaseProxy_GetEndEvent() { }
	// RVA: 0x29d6684 VA: 0x7594fee684
	private Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea P0) { }
	// RVA: 0x29d6688 VA: 0x7594fee688
	private String <>xLuaBaseProxy_GetMapIconName() { }
	// RVA: 0x29d668c VA: 0x7594fee68c
	private String <>xLuaBaseProxy_GetDetailIconName() { }
	// RVA: 0x29d6690 VA: 0x7594fee690
	private String <>xLuaBaseProxy_GetImgDecoName() { }
	// RVA: 0x29d6694 VA: 0x7594fee694
	private String <>xLuaBaseProxy_GetTitleText() { }
	// RVA: 0x29d6698 VA: 0x7594fee698
	private String <>xLuaBaseProxy_GetSpecialPicId() { }
	// RVA: 0x29d669c VA: 0x7594fee69c
	private String <>xLuaBaseProxy_GetNodePicId() { }
	// RVA: 0x29d66a0 VA: 0x7594fee6a0
	private List`1 <>xLuaBaseProxy_GetDescList() { }
	// RVA: 0x29d66a4 VA: 0x7594fee6a4
	private Boolean <>xLuaBaseProxy_ShouldCustomizeLasDes() { }
	// RVA: 0x29d66a8 VA: 0x7594fee6a8
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
}
```