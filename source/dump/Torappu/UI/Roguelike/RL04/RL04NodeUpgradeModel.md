# RL04NodeUpgradeModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String m_topicId`

- `String m_currTempUpgradeId`

- `Int32 <currPermLevel>k__BackingField`

- `String <typeName>k__BackingField`

- `RoguelikeEventType <nodeType>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`


## Properties

- `Int32 currPermLevel`

- `String typeName`

- `RoguelikeEventType nodeType`

- `Int32 enterSeqNum`

- `RL04TempNodeUpgradeItemModel tempUpgradeModel`


## Methods

- `Int32 get_currPermLevel()`

- `Void set_currPermLevel(Int32)`

- `String get_typeName()`

- `Void set_typeName(String)`

- `RoguelikeEventType get_nodeType()`

- `Void set_nodeType(RoguelikeEventType)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `RL04TempNodeUpgradeItemModel get_tempUpgradeModel()`

- `Boolean IsAllPermUnlock()`

- `RL04NodeUpgradeItemModel GetNextUpgradeModel()`

- `Void UpdateEnterSeqNum()`

- `Void LoadData(String, RoguelikeEventType)`

- `Void UpdatePlayerData()`

- `Void _UpdatePlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeModel : IHotfixable
{
	private List`1 m_permItemList; // 0x10
	private Dictionary`2 m_tempItemDict; // 0x18
	private String m_topicId; // 0x20
	private String m_currTempUpgradeId; // 0x28
	private Int32 <currPermLevel>k__BackingField; // 0x30
	private String <typeName>k__BackingField; // 0x38
	private RoguelikeEventType <nodeType>k__BackingField; // 0x40
	private Int32 <enterSeqNum>k__BackingField; // 0x44
	private static DelegateBridge __Hotfix0_get_currPermLevel; // 0x0
	private static DelegateBridge __Hotfix0_set_currPermLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_typeName; // 0x10
	private static DelegateBridge __Hotfix0_set_typeName; // 0x18
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x20
	private static DelegateBridge __Hotfix0_set_nodeType; // 0x28
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x30
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x38
	private static DelegateBridge __Hotfix0_get_permItemList; // 0x40
	private static DelegateBridge __Hotfix0_get_tempUpgradeModel; // 0x48
	private static DelegateBridge __Hotfix0_IsAllPermUnlock; // 0x50
	private static DelegateBridge __Hotfix0_GetNextUpgradeModel; // 0x58
	private static DelegateBridge __Hotfix0_UpdateEnterSeqNum; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x70
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Int32 currPermLevel { get; set; }
	public String typeName { get; set; }
	public RoguelikeEventType nodeType { get; set; }
	public Int32 enterSeqNum { get; set; }
	public List`1 permItemList { get; }
	public RL04TempNodeUpgradeItemModel tempUpgradeModel { get; }

	// RVA: 0x2b329f8 VA: 0x759514a9f8
	public Int32 get_currPermLevel() { }
	// RVA: 0x2b32a60 VA: 0x759514aa60
	private Void set_currPermLevel(Int32 value) { }
	// RVA: 0x2b32adc VA: 0x759514aadc
	public String get_typeName() { }
	// RVA: 0x2b32b44 VA: 0x759514ab44
	private Void set_typeName(String value) { }
	// RVA: 0x2b31070 VA: 0x7595149070
	public RoguelikeEventType get_nodeType() { }
	// RVA: 0x2b32bc8 VA: 0x759514abc8
	private Void set_nodeType(RoguelikeEventType value) { }
	// RVA: 0x2b32c44 VA: 0x759514ac44
	public Int32 get_enterSeqNum() { }
	// RVA: 0x2b32cac VA: 0x759514acac
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x2b32d28 VA: 0x759514ad28
	public List`1 get_permItemList() { }
	// RVA: 0x2b32d90 VA: 0x759514ad90
	public RL04TempNodeUpgradeItemModel get_tempUpgradeModel() { }
	// RVA: 0x2b32e18 VA: 0x759514ae18
	public Boolean IsAllPermUnlock() { }
	// RVA: 0x2b30e90 VA: 0x7595148e90
	public RL04NodeUpgradeItemModel GetNextUpgradeModel() { }
	// RVA: 0x2b308d0 VA: 0x75951488d0
	public Void UpdateEnterSeqNum() { }
	// RVA: 0x2b303a8 VA: 0x75951483a8
	public Void LoadData(String topicId, RoguelikeEventType nodeType) { }
	// RVA: 0x2b31350 VA: 0x7595149350
	public Void UpdatePlayerData() { }
	// RVA: 0x2b33258 VA: 0x759514b258
	private Void _UpdatePlayerData() { }
	// RVA: 0x2b336ec VA: 0x759514b6ec
	public Void .ctor() { }
}
```