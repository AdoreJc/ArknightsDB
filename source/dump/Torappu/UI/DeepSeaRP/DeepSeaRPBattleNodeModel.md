# DeepSeaRPBattleNodeModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `BattleNodeData battleData`

- `StageViewModel normalStage`

- `StageViewModel hardStage`

- `Int32 m_rankNum`


## Properties

- `Int32 stageRank`


## Methods

- `Int32 get_stageRank()`

- `Void _LoadRankNum()`

- `Void <>xLuaBaseProxy_InitData(String, NodeInfoData, Act17sideData)`

- `Boolean <>xLuaBaseProxy_IsNodeComplete()`

- `Boolean <>xLuaBaseProxy_HasTrackPoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattleNodeModel : DeepSeaRPNodeModel
{
	public BattleNodeData battleData; // 0x30
	public StageViewModel normalStage; // 0x38
	public StageViewModel hardStage; // 0x40
	private Int32 m_rankNum; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_get_stageRank; // 0x8
	private static DelegateBridge __Hotfix0__LoadRankNum; // 0x10
	private static DelegateBridge __Hotfix0_IsNodeComplete; // 0x18
	private static DelegateBridge __Hotfix0_HasTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0__LoadStageViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 stageRank { get; }

	// RVA: 0x29d5078 VA: 0x7594fed078
	public override Void InitData(String nodeId_, NodeInfoData infoData_, Act17sideData actData) { }
	// RVA: 0x29d54a8 VA: 0x7594fed4a8
	public Int32 get_stageRank() { }
	// RVA: 0x29d53e4 VA: 0x7594fed3e4
	private Void _LoadRankNum() { }
	// RVA: 0x29d5510 VA: 0x7594fed510
	public override Boolean IsNodeComplete() { }
	// RVA: 0x29d5590 VA: 0x7594fed590
	public override Boolean HasTrackPoint() { }
	// RVA: 0x29d51a8 VA: 0x7594fed1a8
	private static Void _LoadStageViewModel(String stageId, StageViewModel stageViewModel) { }
	// RVA: 0x29d44c4 VA: 0x7594fec4c4
	public Void .ctor() { }
	// RVA: 0x29d5620 VA: 0x7594fed620
	private Void <>xLuaBaseProxy_InitData(String P0, NodeInfoData P1, Act17sideData P2) { }
	// RVA: 0x29d5624 VA: 0x7594fed624
	private Boolean <>xLuaBaseProxy_IsNodeComplete() { }
	// RVA: 0x29d5628 VA: 0x7594fed628
	private Boolean <>xLuaBaseProxy_HasTrackPoint() { }
}
```