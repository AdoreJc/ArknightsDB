# RL04NodeUpgradeSummaryModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `String m_topicId`

- `RoguelikeEventType <currNodeType>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Int32 <switchSeqNum>k__BackingField`


## Properties

- `RoguelikeEventType currNodeType`

- `Int32 enterSeqNum`

- `Int32 switchSeqNum`


## Methods

- `RoguelikeEventType get_currNodeType()`

- `Void set_currNodeType(RoguelikeEventType)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Int32 get_switchSeqNum()`

- `Void set_switchSeqNum(Int32)`

- `RL04NodeUpgradeModel GetCurrUpgradeModel()`

- `Void UpdateEnterSeqNum()`

- `Void _UpdateMuralSeq()`

- `Void LoadData(String)`

- `Void SelectNodeType(RoguelikeEventType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NodeUpgradeSummaryModel : IHotfixable
{
	private List`1 m_nodeUpgradeList; // 0x10
	private String m_topicId; // 0x18
	private Dictionary`2 m_muralSeqDict; // 0x20
	private RoguelikeEventType <currNodeType>k__BackingField; // 0x28
	private Int32 <enterSeqNum>k__BackingField; // 0x2c
	private Int32 <switchSeqNum>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_currNodeType; // 0x0
	private static DelegateBridge __Hotfix0_set_currNodeType; // 0x8
	private static DelegateBridge __Hotfix0_get_nodeUpgradeList; // 0x10
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x18
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_get_switchSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_set_switchSeqNum; // 0x30
	private static DelegateBridge __Hotfix0_get_muralSeqDict; // 0x38
	private static DelegateBridge __Hotfix0_GetCurrUpgradeModel; // 0x40
	private static DelegateBridge __Hotfix0_UpdateEnterSeqNum; // 0x48
	private static DelegateBridge __Hotfix0__UpdateMuralSeq; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0_SelectNodeType; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public RoguelikeEventType currNodeType { get; set; }
	public List`1 nodeUpgradeList { get; }
	public Int32 enterSeqNum { get; set; }
	public Int32 switchSeqNum { get; set; }
	public Dictionary`2 muralSeqDict { get; }

	// RVA: 0x26e490c VA: 0x7594cfc90c
	public RoguelikeEventType get_currNodeType() { }
	// RVA: 0x26e4e9c VA: 0x7594cfce9c
	private Void set_currNodeType(RoguelikeEventType value) { }
	// RVA: 0x26e4f18 VA: 0x7594cfcf18
	public List`1 get_nodeUpgradeList() { }
	// RVA: 0x26e4f80 VA: 0x7594cfcf80
	public Int32 get_enterSeqNum() { }
	// RVA: 0x26e4fe8 VA: 0x7594cfcfe8
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x26e5064 VA: 0x7594cfd064
	public Int32 get_switchSeqNum() { }
	// RVA: 0x26e50cc VA: 0x7594cfd0cc
	private Void set_switchSeqNum(Int32 value) { }
	// RVA: 0x26e5148 VA: 0x7594cfd148
	public Dictionary`2 get_muralSeqDict() { }
	// RVA: 0x26e51b0 VA: 0x7594cfd1b0
	public RL04NodeUpgradeModel GetCurrUpgradeModel() { }
	// RVA: 0x26e47a8 VA: 0x7594cfc7a8
	public Void UpdateEnterSeqNum() { }
	// RVA: 0x26e532c VA: 0x7594cfd32c
	private Void _UpdateMuralSeq() { }
	// RVA: 0x26e4384 VA: 0x7594cfc384
	public Void LoadData(String topicId) { }
	// RVA: 0x26e4974 VA: 0x7594cfc974
	public Void SelectNodeType(RoguelikeEventType nodeType) { }
	// RVA: 0x26e5b24 VA: 0x7594cfdb24
	public Void .ctor() { }
}
```