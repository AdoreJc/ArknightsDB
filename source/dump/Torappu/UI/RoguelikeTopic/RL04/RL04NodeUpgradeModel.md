# RL04NodeUpgradeModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `String m_topicId`

- `RoguelikeEventType <nodeType>k__BackingField`

- `String <typeName>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `Int32 <currPermLevel>k__BackingField`


## Properties

- `RoguelikeEventType nodeType`

- `String typeName`

- `Int32 sortId`

- `Int32 currPermLevel`


## Methods

- `RoguelikeEventType get_nodeType()`

- `Void set_nodeType(RoguelikeEventType)`

- `String get_typeName()`

- `Void set_typeName(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Int32 get_currPermLevel()`

- `Void set_currPermLevel(Int32)`

- `String GetUpgradeTypeName()`

- `Void LoadData(String, RoguelikeNodeUpgradeData, RoguelikeGameNodeTypeData)`

- `Void _UpdatePlayerData()`

- `Boolean IsAllPermUnlock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NodeUpgradeModel : IHotfixable
{
	private String m_topicId; // 0x10
	private RoguelikeEventType <nodeType>k__BackingField; // 0x18
	private String <typeName>k__BackingField; // 0x20
	private Int32 <sortId>k__BackingField; // 0x28
	private Int32 <currPermLevel>k__BackingField; // 0x2c
	private List`1 m_permItemList; // 0x30
	private List`1 m_tempItemList; // 0x38
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x0
	private static DelegateBridge __Hotfix0_set_nodeType; // 0x8
	private static DelegateBridge __Hotfix0_get_typeName; // 0x10
	private static DelegateBridge __Hotfix0_set_typeName; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_currPermLevel; // 0x30
	private static DelegateBridge __Hotfix0_set_currPermLevel; // 0x38
	private static DelegateBridge __Hotfix0_get_permItemList; // 0x40
	private static DelegateBridge __Hotfix0_get_tempItemList; // 0x48
	private static DelegateBridge __Hotfix0_GetUpgradeTypeName; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x60
	private static DelegateBridge __Hotfix0_IsAllPermUnlock; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public RoguelikeEventType nodeType { get; set; }
	public String typeName { get; set; }
	public Int32 sortId { get; set; }
	public Int32 currPermLevel { get; set; }
	public List`1 permItemList { get; }
	public List`1 tempItemList { get; }

	// RVA: 0x26e52c4 VA: 0x7594cfd2c4
	public RoguelikeEventType get_nodeType() { }
	// RVA: 0x26e5d64 VA: 0x7594cfdd64
	private Void set_nodeType(RoguelikeEventType value) { }
	// RVA: 0x26e5de0 VA: 0x7594cfdde0
	public String get_typeName() { }
	// RVA: 0x26e5e48 VA: 0x7594cfde48
	private Void set_typeName(String value) { }
	// RVA: 0x26e5cfc VA: 0x7594cfdcfc
	public Int32 get_sortId() { }
	// RVA: 0x26e5ecc VA: 0x7594cfdecc
	private Void set_sortId(Int32 value) { }
	// RVA: 0x26e5f48 VA: 0x7594cfdf48
	public Int32 get_currPermLevel() { }
	// RVA: 0x26e5fb0 VA: 0x7594cfdfb0
	private Void set_currPermLevel(Int32 value) { }
	// RVA: 0x26e545c VA: 0x7594cfd45c
	public List`1 get_permItemList() { }
	// RVA: 0x26e602c VA: 0x7594cfe02c
	public List`1 get_tempItemList() { }
	// RVA: 0x26e6094 VA: 0x7594cfe094
	public String GetUpgradeTypeName() { }
	// RVA: 0x26e55d8 VA: 0x7594cfd5d8
	public Void LoadData(String topicId, RoguelikeNodeUpgradeData upgradeData, RoguelikeGameNodeTypeData typeData) { }
	// RVA: 0x26e61c4 VA: 0x7594cfe1c4
	private Void _UpdatePlayerData() { }
	// RVA: 0x26e63f0 VA: 0x7594cfe3f0
	public Boolean IsAllPermUnlock() { }
	// RVA: 0x26e54c4 VA: 0x7594cfd4c4
	public Void .ctor() { }
}
```