# DeepSeaRPTechNodeModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `TechNodeData techNodeData`

- `TechStatus techStatus`

- `MissionData m_missionData`

- `EventData m_endEventData`


## Properties

- `MissionData missionData`


## Methods

- `MissionData get_missionData()`

- `Boolean IsMissionComplete()`

- `MissionCalcState GetMissionProgress()`

- `Void _FetchMissionData()`

- `EventData <>xLuaBaseProxy_GetEndEvent()`

- `Boolean <>xLuaBaseProxy_IsGrey()`

- `String <>xLuaBaseProxy_GetTitleText()`

- `String <>xLuaBaseProxy_GetSpecialPicId()`

- `String <>xLuaBaseProxy_GetNodePicId()`

- `Boolean <>xLuaBaseProxy_HasEntryTrackPoint()`

- `Boolean <>xLuaBaseProxy_HasTrackPoint()`

- `Boolean <>xLuaBaseProxy_ShowLockOnMap()`

- `Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea)`

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Boolean <>xLuaBaseProxy_ShouldCustomizeLasDes()`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechNodeModel : DeepSeaRPNodeModel
{
	public TechNodeData techNodeData; // 0x30
	public TechStatus techStatus; // 0x38
	private MissionData m_missionData; // 0x40
	private EventData m_endEventData; // 0x48
	private static DelegateBridge __Hotfix0_GetEndEvent; // 0x0
	private static DelegateBridge __Hotfix0_get_missionData; // 0x8
	private static DelegateBridge __Hotfix0_IsGrey; // 0x10
	private static DelegateBridge __Hotfix0_GetTitleText; // 0x18
	private static DelegateBridge __Hotfix0_GetSpecialPicId; // 0x20
	private static DelegateBridge __Hotfix0_GetNodePicId; // 0x28
	private static DelegateBridge __Hotfix0_IsMissionComplete; // 0x30
	private static DelegateBridge __Hotfix0_GetMissionProgress; // 0x38
	private static DelegateBridge __Hotfix0__FetchMissionData; // 0x40
	private static DelegateBridge __Hotfix0_HasEntryTrackPoint; // 0x48
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x50
	private static DelegateBridge __Hotfix0_ShowLockOnMap; // 0x58
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x60
	private static DelegateBridge __Hotfix0_InitData; // 0x68
	private static DelegateBridge __Hotfix0_GetDescList; // 0x70
	private static DelegateBridge __Hotfix0_ShouldCustomizeLasDes; // 0x78
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public MissionData missionData { get; }

	// RVA: 0x29d6c54 VA: 0x7594feec54
	public override EventData GetEndEvent() { }
	// RVA: 0x29d6cbc VA: 0x7594feecbc
	public MissionData get_missionData() { }
	// RVA: 0x29d6eac VA: 0x7594feeeac
	public override Boolean IsGrey() { }
	// RVA: 0x29d6f1c VA: 0x7594feef1c
	public override String GetTitleText() { }
	// RVA: 0x29d6f9c VA: 0x7594feef9c
	public override String GetSpecialPicId() { }
	// RVA: 0x29d7010 VA: 0x7594fef010
	public override String GetNodePicId() { }
	// RVA: 0x29d7084 VA: 0x7594fef084
	public Boolean IsMissionComplete() { }
	// RVA: 0x29d7208 VA: 0x7594fef208
	public MissionCalcState GetMissionProgress() { }
	// RVA: 0x29d6d34 VA: 0x7594feed34
	private Void _FetchMissionData() { }
	// RVA: 0x29d7330 VA: 0x7594fef330
	public override Boolean HasEntryTrackPoint() { }
	// RVA: 0x29d73c0 VA: 0x7594fef3c0
	public override Boolean HasTrackPoint() { }
	// RVA: 0x29d7468 VA: 0x7594fef468
	public override Boolean ShowLockOnMap() { }
	// RVA: 0x29d74fc VA: 0x7594fef4fc
	public override Void UpdateNodeStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29d75d4 VA: 0x7594fef5d4
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d7720 VA: 0x7594fef720
	public override List`1 GetDescList() { }
	// RVA: 0x29d7794 VA: 0x7594fef794
	public override Boolean ShouldCustomizeLasDes() { }
	// RVA: 0x29d77fc VA: 0x7594fef7fc
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29d46dc VA: 0x7594fec6dc
	public Void .ctor() { }
	// RVA: 0x29d7880 VA: 0x7594fef880
	private EventData <>xLuaBaseProxy_GetEndEvent() { }
	// RVA: 0x29d7884 VA: 0x7594fef884
	private Boolean <>xLuaBaseProxy_IsGrey() { }
	// RVA: 0x29d7888 VA: 0x7594fef888
	private String <>xLuaBaseProxy_GetTitleText() { }
	// RVA: 0x29d788c VA: 0x7594fef88c
	private String <>xLuaBaseProxy_GetSpecialPicId() { }
	// RVA: 0x29d7890 VA: 0x7594fef890
	private String <>xLuaBaseProxy_GetNodePicId() { }
	// RVA: 0x29d7894 VA: 0x7594fef894
	private Boolean <>xLuaBaseProxy_HasEntryTrackPoint() { }
	// RVA: 0x29d7898 VA: 0x7594fef898
	private Boolean <>xLuaBaseProxy_HasTrackPoint() { }
	// RVA: 0x29d789c VA: 0x7594fef89c
	private Boolean <>xLuaBaseProxy_ShowLockOnMap() { }
	// RVA: 0x29d78a0 VA: 0x7594fef8a0
	private Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea P0) { }
	// RVA: 0x29d78a4 VA: 0x7594fef8a4
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d78a8 VA: 0x7594fef8a8
	private List`1 <>xLuaBaseProxy_GetDescList() { }
	// RVA: 0x29d78ac VA: 0x7594fef8ac
	private Boolean <>xLuaBaseProxy_ShouldCustomizeLasDes() { }
	// RVA: 0x29d78b0 VA: 0x7594fef8b0
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
}
```