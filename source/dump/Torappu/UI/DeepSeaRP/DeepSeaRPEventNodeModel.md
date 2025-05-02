# DeepSeaRPEventNodeModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `EventNodeData eventNodeData`

- `EventData m_eventData`

- `EventData m_endEventData`

- `ReadStatus m_status`


## Methods

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea)`

- `EventData <>xLuaBaseProxy_GetEndEvent()`

- `Boolean <>xLuaBaseProxy_IsGrey()`

- `String <>xLuaBaseProxy_GetTitleText()`

- `String <>xLuaBaseProxy_GetSpecialPicId()`

- `String <>xLuaBaseProxy_GetNodePicId()`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPEventNodeModel : DeepSeaRPNodeModel
{
	public EventNodeData eventNodeData; // 0x30
	private EventData m_eventData; // 0x38
	private EventData m_endEventData; // 0x40
	private ReadStatus m_status; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetEndEvent; // 0x10
	private static DelegateBridge __Hotfix0_IsGrey; // 0x18
	private static DelegateBridge __Hotfix0_GetTitleText; // 0x20
	private static DelegateBridge __Hotfix0_GetSpecialPicId; // 0x28
	private static DelegateBridge __Hotfix0_GetNodePicId; // 0x30
	private static DelegateBridge __Hotfix0_GetDescList; // 0x38
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x29d66ac VA: 0x7594fee6ac
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d682c VA: 0x7594fee82c
	public override Void UpdateNodeStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29d68f8 VA: 0x7594fee8f8
	public override EventData GetEndEvent() { }
	// RVA: 0x29d6960 VA: 0x7594fee960
	public override Boolean IsGrey() { }
	// RVA: 0x29d69d0 VA: 0x7594fee9d0
	public override String GetTitleText() { }
	// RVA: 0x29d6a50 VA: 0x7594feea50
	public override String GetSpecialPicId() { }
	// RVA: 0x29d6ac4 VA: 0x7594feeac4
	public override String GetNodePicId() { }
	// RVA: 0x29d6b38 VA: 0x7594feeb38
	public override List`1 GetDescList() { }
	// RVA: 0x29d6bac VA: 0x7594feebac
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29d4670 VA: 0x7594fec670
	public Void .ctor() { }
	// RVA: 0x29d6c30 VA: 0x7594feec30
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d6c34 VA: 0x7594feec34
	private Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea P0) { }
	// RVA: 0x29d6c38 VA: 0x7594feec38
	private EventData <>xLuaBaseProxy_GetEndEvent() { }
	// RVA: 0x29d6c3c VA: 0x7594feec3c
	private Boolean <>xLuaBaseProxy_IsGrey() { }
	// RVA: 0x29d6c40 VA: 0x7594feec40
	private String <>xLuaBaseProxy_GetTitleText() { }
	// RVA: 0x29d6c44 VA: 0x7594feec44
	private String <>xLuaBaseProxy_GetSpecialPicId() { }
	// RVA: 0x29d6c48 VA: 0x7594feec48
	private String <>xLuaBaseProxy_GetNodePicId() { }
	// RVA: 0x29d6c4c VA: 0x7594feec4c
	private List`1 <>xLuaBaseProxy_GetDescList() { }
	// RVA: 0x29d6c50 VA: 0x7594feec50
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
}
```