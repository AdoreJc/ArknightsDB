# SandboxV2SquadToolModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `String m_toolId`

- `String m_name`

- `UIItemViewModel m_itemModel`

- `String m_tagPicId`

- `String m_tagName`

- `String m_desc`

- `Int32 m_toolCntLimit`

- `String m_usage`

- `Boolean m_canBuild`


## Properties

- `String toolId`

- `String name`

- `UIItemViewModel itemModel`

- `Boolean canBuild`

- `Int32 sortId`

- `String tagPicId`

- `String tagName`

- `String desc`

- `String usage`


## Methods

- `String get_toolId()`

- `String get_name()`

- `UIItemViewModel get_itemModel()`

- `Boolean get_canBuild()`

- `Int32 get_sortId()`

- `String get_tagPicId()`

- `String get_tagName()`

- `String get_desc()`

- `String get_usage()`

- `Void _Load(String, SandboxPermItemData, SandboxV2ItemTrapData, SandboxV2ItemTrapTagData, Int32)`

- `Void _UpdatePlayerData()`

- `Void UpdatePlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadToolModel
{
	private String m_topicId; // 0x10
	private String m_toolId; // 0x18
	private String m_name; // 0x20
	private UIItemViewModel m_itemModel; // 0x28
	private String m_tagPicId; // 0x30
	private String m_tagName; // 0x38
	private String m_desc; // 0x40
	private Int32 m_toolCntLimit; // 0x48
	private String m_usage; // 0x50
	private Boolean m_canBuild; // 0x58

	public String toolId { get; }
	public String name { get; }
	public UIItemViewModel itemModel { get; }
	public Boolean canBuild { get; }
	public Int32 sortId { get; }
	public String tagPicId { get; }
	public String tagName { get; }
	public String desc { get; }
	public String usage { get; }

	// RVA: 0x261aed4 VA: 0x7594c32ed4
	public String get_toolId() { }
	// RVA: 0x261aedc VA: 0x7594c32edc
	public String get_name() { }
	// RVA: 0x261aee4 VA: 0x7594c32ee4
	public UIItemViewModel get_itemModel() { }
	// RVA: 0x261aeec VA: 0x7594c32eec
	public Boolean get_canBuild() { }
	// RVA: 0x261aef4 VA: 0x7594c32ef4
	public Int32 get_sortId() { }
	// RVA: 0x261af10 VA: 0x7594c32f10
	public String get_tagPicId() { }
	// RVA: 0x261af18 VA: 0x7594c32f18
	public String get_tagName() { }
	// RVA: 0x261af20 VA: 0x7594c32f20
	public String get_desc() { }
	// RVA: 0x261af28 VA: 0x7594c32f28
	public String get_usage() { }
	// RVA: 0x261af30 VA: 0x7594c32f30
	private Void .ctor() { }
	// RVA: 0x2619e0c VA: 0x7594c31e0c
	public static SandboxV2SquadToolModel Create(String topicId, String toolId, Boolean limitCnt) { }
	// RVA: 0x261af38 VA: 0x7594c32f38
	private Void _Load(String topicId, SandboxPermItemData itemData, SandboxV2ItemTrapData toolData, SandboxV2ItemTrapTagData tagData, Int32 toolCntLimit) { }
	// RVA: 0x261b090 VA: 0x7594c33090
	private Void _UpdatePlayerData() { }
	// RVA: 0x2619c3c VA: 0x7594c31c3c
	public Void UpdatePlayerData() { }
}
```