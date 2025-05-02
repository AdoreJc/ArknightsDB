# DeepSeaRPStoryNodeModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `StoryNodeData storyData`

- `ReadStatus m_readStatus`


## Methods

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea)`

- `String <>xLuaBaseProxy_GetTitleText()`

- `String <>xLuaBaseProxy_GetNodePicId()`

- `Boolean <>xLuaBaseProxy_HasTrackPoint()`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPStoryNodeModel : DeepSeaRPNodeModel
{
	public StoryNodeData storyData; // 0x30
	private ReadStatus m_readStatus; // 0x38
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetTitleText; // 0x10
	private static DelegateBridge __Hotfix0_GetNodePicId; // 0x18
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0_GetDescList; // 0x28
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x29d4c20 VA: 0x7594fecc20
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d4d24 VA: 0x7594fecd24
	public override Void UpdateNodeStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29d4df0 VA: 0x7594fecdf0
	public override String GetTitleText() { }
	// RVA: 0x29d4e70 VA: 0x7594fece70
	public override String GetNodePicId() { }
	// RVA: 0x29d4ee4 VA: 0x7594fecee4
	public override Boolean HasTrackPoint() { }
	// RVA: 0x29d4f64 VA: 0x7594fecf64
	public override List`1 GetDescList() { }
	// RVA: 0x29d4fd8 VA: 0x7594fecfd8
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29d4458 VA: 0x7594fec458
	public Void .ctor() { }
	// RVA: 0x29d505c VA: 0x7594fed05c
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d5060 VA: 0x7594fed060
	private Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea P0) { }
	// RVA: 0x29d5064 VA: 0x7594fed064
	private String <>xLuaBaseProxy_GetTitleText() { }
	// RVA: 0x29d5068 VA: 0x7594fed068
	private String <>xLuaBaseProxy_GetNodePicId() { }
	// RVA: 0x29d506c VA: 0x7594fed06c
	private Boolean <>xLuaBaseProxy_HasTrackPoint() { }
	// RVA: 0x29d5070 VA: 0x7594fed070
	private List`1 <>xLuaBaseProxy_GetDescList() { }
	// RVA: 0x29d5074 VA: 0x7594fed074
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
}
```