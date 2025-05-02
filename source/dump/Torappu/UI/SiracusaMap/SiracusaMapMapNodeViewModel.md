# SiracusaMapMapNodeViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `NodeType nodeType`

- `PointData m_pointData`

- `Boolean isStage`

- `StageViewModel <normalStage>k__BackingField`

- `StageViewModel hardStage`

- `String cornerIconId`

- `Boolean isSelectingHard`

- `Int32 <rankNum>k__BackingField`

- `CharCardPatch charCardPatch`

- `Boolean showSelected`

- `String m_pointId`


## Properties

- `StageViewModel normalStage`

- `Int32 rankNum`

- `String pointId`

- `String pointName`

- `String pointItaName`

- `String pointDesc`

- `String pointIconId`

- `String stageId`


## Methods

- `StageViewModel get_normalStage()`

- `Void set_normalStage(StageViewModel)`

- `Int32 get_rankNum()`

- `Void set_rankNum(Int32)`

- `String get_pointId()`

- `String get_pointName()`

- `String get_pointItaName()`

- `String get_pointDesc()`

- `String get_pointIconId()`

- `String get_stageId()`

- `Void LoadData(Param)`

- `Boolean IsSameNodeWithStatus(NodeModelStruct)`

- `Boolean IsTaskNode()`

- `Boolean IsNormalNode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapMapNodeViewModel : ISiracusaMapStageInfoModel, IHotfixable
{
	public NodeType nodeType; // 0x10
	private PointData m_pointData; // 0x18
	public Boolean isStage; // 0x20
	private StageViewModel <normalStage>k__BackingField; // 0x28
	public StageViewModel hardStage; // 0x30
	public String cornerIconId; // 0x38
	public Boolean isSelectingHard; // 0x40
	private Int32 <rankNum>k__BackingField; // 0x44
	public CharCardPatch charCardPatch; // 0x48
	public Boolean showSelected; // 0x78
	private String m_pointId; // 0x80
	private static DelegateBridge __Hotfix0_get_normalStage; // 0x0
	private static DelegateBridge __Hotfix0_set_normalStage; // 0x8
	private static DelegateBridge __Hotfix0_get_rankNum; // 0x10
	private static DelegateBridge __Hotfix0_set_rankNum; // 0x18
	private static DelegateBridge __Hotfix0_get_pointId; // 0x20
	private static DelegateBridge __Hotfix0_get_pointName; // 0x28
	private static DelegateBridge __Hotfix0_get_pointItaName; // 0x30
	private static DelegateBridge __Hotfix0_get_pointDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_pointIconId; // 0x40
	private static DelegateBridge __Hotfix0_get_stageId; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_IsSameNodeWithStatus; // 0x58
	private static DelegateBridge __Hotfix0_IsTaskNode; // 0x60
	private static DelegateBridge __Hotfix0_IsNormalNode; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public StageViewModel normalStage { get; set; }
	public Int32 rankNum { get; set; }
	public String pointId { get; }
	public String pointName { get; }
	public String pointItaName { get; }
	public String pointDesc { get; }
	public String pointIconId { get; }
	public String stageId { get; }

	// RVA: 0x2416140 VA: 0x7594a2e140
	public StageViewModel get_normalStage() { }
	// RVA: 0x24161a8 VA: 0x7594a2e1a8
	private Void set_normalStage(StageViewModel value) { }
	// RVA: 0x2415184 VA: 0x7594a2d184
	public Int32 get_rankNum() { }
	// RVA: 0x241622c VA: 0x7594a2e22c
	private Void set_rankNum(Int32 value) { }
	// RVA: 0x241511c VA: 0x7594a2d11c
	public String get_pointId() { }
	// RVA: 0x24158f0 VA: 0x7594a2d8f0
	public String get_pointName() { }
	// RVA: 0x24162a8 VA: 0x7594a2e2a8
	public String get_pointItaName() { }
	// RVA: 0x241633c VA: 0x7594a2e33c
	public String get_pointDesc() { }
	// RVA: 0x2415664 VA: 0x7594a2d664
	public String get_pointIconId() { }
	// RVA: 0x24163d0 VA: 0x7594a2e3d0
	public String get_stageId() { }
	// RVA: 0x2416478 VA: 0x7594a2e478
	public Void LoadData(Param param) { }
	// RVA: 0x2414fcc VA: 0x7594a2cfcc
	public Boolean IsSameNodeWithStatus(NodeModelStruct nodeModelStruct) { }
	// RVA: 0x241671c VA: 0x7594a2e71c
	public Boolean IsTaskNode() { }
	// RVA: 0x241678c VA: 0x7594a2e78c
	public Boolean IsNormalNode() { }
	// RVA: 0x24167fc VA: 0x7594a2e7fc
	public Void .ctor() { }
}
```