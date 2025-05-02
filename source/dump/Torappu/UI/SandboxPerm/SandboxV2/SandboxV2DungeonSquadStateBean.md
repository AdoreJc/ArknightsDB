# SandboxV2DungeonSquadStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 <actionCost>k__BackingField`

- `String <nodeId>k__BackingField`

- `String <stageId>k__BackingField`

- `SandboxV2NodeType <nodeType>k__BackingField`

- `SandboxV2SeasonType <nodeSeasonType>k__BackingField`

- `String <nodeWeatherId>k__BackingField`

- `String <monthlyRushId>k__BackingField`

- `SandboxV2BattleBgmType <battleBgmType>k__BackingField`


## Properties

- `Int32 actionCost`

- `String nodeId`

- `String stageId`

- `SandboxV2NodeType nodeType`

- `SandboxV2SeasonType nodeSeasonType`

- `String nodeWeatherId`

- `String monthlyRushId`

- `SandboxV2BattleBgmType battleBgmType`


## Methods

- `Int32 get_actionCost()`

- `Void set_actionCost(Int32)`

- `String get_nodeId()`

- `Void set_nodeId(String)`

- `String get_stageId()`

- `Void set_stageId(String)`

- `SandboxV2NodeType get_nodeType()`

- `Void set_nodeType(SandboxV2NodeType)`

- `SandboxV2SeasonType get_nodeSeasonType()`

- `Void set_nodeSeasonType(SandboxV2SeasonType)`

- `String get_nodeWeatherId()`

- `Void set_nodeWeatherId(String)`

- `String get_monthlyRushId()`

- `Void set_monthlyRushId(String)`

- `SandboxV2BattleBgmType get_battleBgmType()`

- `Void set_battleBgmType(SandboxV2BattleBgmType)`

- `Void LoadData(SandboxV2SquadStateInputParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSquadStateBean : IStateBean, IHotfixable
{
	private Int32 <actionCost>k__BackingField; // 0x10
	private String <nodeId>k__BackingField; // 0x18
	private String <stageId>k__BackingField; // 0x20
	private SandboxV2NodeType <nodeType>k__BackingField; // 0x28
	private SandboxV2SeasonType <nodeSeasonType>k__BackingField; // 0x2c
	private String <nodeWeatherId>k__BackingField; // 0x30
	private String <monthlyRushId>k__BackingField; // 0x38
	private SandboxV2BattleBgmType <battleBgmType>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_actionCost; // 0x0
	private static DelegateBridge __Hotfix0_set_actionCost; // 0x8
	private static DelegateBridge __Hotfix0_get_nodeId; // 0x10
	private static DelegateBridge __Hotfix0_set_nodeId; // 0x18
	private static DelegateBridge __Hotfix0_get_stageId; // 0x20
	private static DelegateBridge __Hotfix0_set_stageId; // 0x28
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x30
	private static DelegateBridge __Hotfix0_set_nodeType; // 0x38
	private static DelegateBridge __Hotfix0_get_nodeSeasonType; // 0x40
	private static DelegateBridge __Hotfix0_set_nodeSeasonType; // 0x48
	private static DelegateBridge __Hotfix0_get_nodeWeatherId; // 0x50
	private static DelegateBridge __Hotfix0_set_nodeWeatherId; // 0x58
	private static DelegateBridge __Hotfix0_get_monthlyRushId; // 0x60
	private static DelegateBridge __Hotfix0_set_monthlyRushId; // 0x68
	private static DelegateBridge __Hotfix0_get_battleBgmType; // 0x70
	private static DelegateBridge __Hotfix0_set_battleBgmType; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Int32 actionCost { get; set; }
	public String nodeId { get; set; }
	public String stageId { get; set; }
	public SandboxV2NodeType nodeType { get; set; }
	public SandboxV2SeasonType nodeSeasonType { get; set; }
	public String nodeWeatherId { get; set; }
	public String monthlyRushId { get; set; }
	public SandboxV2BattleBgmType battleBgmType { get; set; }

	// RVA: 0x2542770 VA: 0x7594b5a770
	public Int32 get_actionCost() { }
	// RVA: 0x25427d8 VA: 0x7594b5a7d8
	private Void set_actionCost(Int32 value) { }
	// RVA: 0x2542854 VA: 0x7594b5a854
	public String get_nodeId() { }
	// RVA: 0x25428bc VA: 0x7594b5a8bc
	private Void set_nodeId(String value) { }
	// RVA: 0x2542940 VA: 0x7594b5a940
	public String get_stageId() { }
	// RVA: 0x25429a8 VA: 0x7594b5a9a8
	private Void set_stageId(String value) { }
	// RVA: 0x2542a2c VA: 0x7594b5aa2c
	public SandboxV2NodeType get_nodeType() { }
	// RVA: 0x2542a94 VA: 0x7594b5aa94
	private Void set_nodeType(SandboxV2NodeType value) { }
	// RVA: 0x2542b10 VA: 0x7594b5ab10
	public SandboxV2SeasonType get_nodeSeasonType() { }
	// RVA: 0x2542b78 VA: 0x7594b5ab78
	private Void set_nodeSeasonType(SandboxV2SeasonType value) { }
	// RVA: 0x2542bf4 VA: 0x7594b5abf4
	public String get_nodeWeatherId() { }
	// RVA: 0x2542c5c VA: 0x7594b5ac5c
	private Void set_nodeWeatherId(String value) { }
	// RVA: 0x2542ce0 VA: 0x7594b5ace0
	public String get_monthlyRushId() { }
	// RVA: 0x2542d48 VA: 0x7594b5ad48
	private Void set_monthlyRushId(String value) { }
	// RVA: 0x2542dcc VA: 0x7594b5adcc
	public SandboxV2BattleBgmType get_battleBgmType() { }
	// RVA: 0x2542e34 VA: 0x7594b5ae34
	private Void set_battleBgmType(SandboxV2BattleBgmType value) { }
	// RVA: 0x2542eb0 VA: 0x7594b5aeb0
	public Void LoadData(SandboxV2SquadStateInputParam inputParam) { }
	// RVA: 0x2542fa4 VA: 0x7594b5afa4
	public Void .ctor() { }
}
```