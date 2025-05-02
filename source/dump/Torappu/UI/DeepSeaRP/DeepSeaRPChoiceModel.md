# DeepSeaRPChoiceModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `ChoiceNodeData choiceData`


## Methods

- `Boolean HasOptionSelected()`

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Boolean <>xLuaBaseProxy_IsGrey()`

- `Boolean <>xLuaBaseProxy_ShowLockOnMap()`

- `Boolean <>xLuaBaseProxy_HasTrackPoint()`

- `Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea)`

- `String <>xLuaBaseProxy_GetTitleText()`

- `String <>xLuaBaseProxy_GetSpecialPicId()`

- `String <>xLuaBaseProxy_GetNodePicId()`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPChoiceModel : DeepSeaRPNodeModel
{
	public ChoiceNodeData choiceData; // 0x30
	public List`1 choiceStatusList; // 0x38
	public List`1 eventDataList; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_IsGrey; // 0x8
	private static DelegateBridge __Hotfix0_ShowLockOnMap; // 0x10
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x18
	private static DelegateBridge __Hotfix0_UpdateNodeStatus; // 0x20
	private static DelegateBridge __Hotfix0_GetTitleText; // 0x28
	private static DelegateBridge __Hotfix0_GetSpecialPicId; // 0x30
	private static DelegateBridge __Hotfix0_GetNodePicId; // 0x38
	private static DelegateBridge __Hotfix0_GetDescList; // 0x40
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x48
	private static DelegateBridge __Hotfix0_HasOptionSelected; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x29d78b4 VA: 0x7594fef8b4
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d7b6c VA: 0x7594fefb6c
	public override Boolean IsGrey() { }
	// RVA: 0x29d7c5c VA: 0x7594fefc5c
	public override Boolean ShowLockOnMap() { }
	// RVA: 0x29d7d5c VA: 0x7594fefd5c
	public override Boolean HasTrackPoint() { }
	// RVA: 0x29d7e78 VA: 0x7594fefe78
	public override Void UpdateNodeStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29d7f5c VA: 0x7594feff5c
	public override String GetTitleText() { }
	// RVA: 0x29d7fdc VA: 0x7594feffdc
	public override String GetSpecialPicId() { }
	// RVA: 0x29d8050 VA: 0x7594ff0050
	public override String GetNodePicId() { }
	// RVA: 0x29d80c4 VA: 0x7594ff00c4
	public override List`1 GetDescList() { }
	// RVA: 0x29d8138 VA: 0x7594ff0138
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29ce5f8 VA: 0x7594fe65f8
	public Boolean HasOptionSelected() { }
	// RVA: 0x29d4748 VA: 0x7594fec748
	public Void .ctor() { }
	// RVA: 0x29d8234 VA: 0x7594ff0234
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d8238 VA: 0x7594ff0238
	private Boolean <>xLuaBaseProxy_IsGrey() { }
	// RVA: 0x29d823c VA: 0x7594ff023c
	private Boolean <>xLuaBaseProxy_ShowLockOnMap() { }
	// RVA: 0x29d8240 VA: 0x7594ff0240
	private Boolean <>xLuaBaseProxy_HasTrackPoint() { }
	// RVA: 0x29d8244 VA: 0x7594ff0244
	private Void <>xLuaBaseProxy_UpdateNodeStatus(PlayerDeepSea P0) { }
	// RVA: 0x29d8248 VA: 0x7594ff0248
	private String <>xLuaBaseProxy_GetTitleText() { }
	// RVA: 0x29d824c VA: 0x7594ff024c
	private String <>xLuaBaseProxy_GetSpecialPicId() { }
	// RVA: 0x29d8250 VA: 0x7594ff0250
	private String <>xLuaBaseProxy_GetNodePicId() { }
	// RVA: 0x29d8254 VA: 0x7594ff0254
	private List`1 <>xLuaBaseProxy_GetDescList() { }
	// RVA: 0x29d8258 VA: 0x7594ff0258
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
}
```