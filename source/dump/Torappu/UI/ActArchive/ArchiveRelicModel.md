# ArchiveRelicModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Int32 selectedDifficultyCount`

- `Int32 selectedDifficultyIndex`

- `Int32 selectLineNum`

- `FilterRule filterRule`

- `Boolean showSwitchAnim`

- `Int32 m_attainedNum`

- `Boolean m_checkedNewFilterFlag`

- `String <selectedItemId>k__BackingField`

- `RelicItemModel <selectedItem>k__BackingField`


## Properties

- `Int32 newNum`

- `String selectedItemId`

- `RelicItemModel selectedItem`


## Methods

- `Int32 get_newNum()`

- `String get_selectedItemId()`

- `Void set_selectedItemId(String)`

- `RelicItemModel get_selectedItem()`

- `Void set_selectedItem(RelicItemModel)`

- `String GetDefaultItemId()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`

- `Void GenerateItemGroup(Boolean)`

- `Void UpdateSelectedItemId(String)`

- `Void _GenerateRootItems(String, RoguelikeArchiveComponentData, RoguelikeTopicDetail, OuterData)`

- `Void _GenerateDifficultyItems(String, RoguelikeTopicDetail, OuterData)`

- `Boolean _IsRelicItemsFiltered(RelicItemModel, FilterRule)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicModel : IHotfixable
{
	public Int32 selectedDifficultyCount; // 0x10
	public Int32 selectedDifficultyIndex; // 0x14
	public Int32 selectLineNum; // 0x18
	public FilterRule filterRule; // 0x1c
	public List`1 relicItemGroups; // 0x20
	public Boolean showSwitchAnim; // 0x28
	private ListDict`2 m_relicItems; // 0x30
	private Dictionary`2 m_difficultyRelics; // 0x38
	private Int32 m_attainedNum; // 0x40
	private Boolean m_checkedNewFilterFlag; // 0x44
	private String <selectedItemId>k__BackingField; // 0x48
	private RelicItemModel <selectedItem>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_newNum; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x8
	private static DelegateBridge __Hotfix0_set_selectedItemId; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x18
	private static DelegateBridge __Hotfix0_set_selectedItem; // 0x20
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_GenerateItemGroup; // 0x38
	private static DelegateBridge __Hotfix0_UpdateSelectedItemId; // 0x40
	private static DelegateBridge __Hotfix0__GenerateRootItems; // 0x48
	private static DelegateBridge __Hotfix0__GenerateDifficultyItems; // 0x50
	private static DelegateBridge __Hotfix0__IsRelicItemsFiltered; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Int32 newNum { get; }
	public String selectedItemId { get; set; }
	public RelicItemModel selectedItem { get; set; }

	// RVA: 0x307880c VA: 0x759569080c
	public Int32 get_newNum() { }
	// RVA: 0x30790b4 VA: 0x75956910b4
	public String get_selectedItemId() { }
	// RVA: 0x307b510 VA: 0x7595693510
	private Void set_selectedItemId(String value) { }
	// RVA: 0x307904c VA: 0x759569104c
	public RelicItemModel get_selectedItem() { }
	// RVA: 0x307b594 VA: 0x7595693594
	private Void set_selectedItem(RelicItemModel value) { }
	// RVA: 0x307b618 VA: 0x7595693618
	public String GetDefaultItemId() { }
	// RVA: 0x307b700 VA: 0x7595693700
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x307c7d0 VA: 0x75956947d0
	public Void GenerateItemGroup(Boolean isInit) { }
	// RVA: 0x307cfd8 VA: 0x7595694fd8
	public Void UpdateSelectedItemId(String itemId) { }
	// RVA: 0x307bfb4 VA: 0x7595693fb4
	private Void _GenerateRootItems(String archiveId, RoguelikeArchiveComponentData compData, RoguelikeTopicDetail topicDetail, OuterData playerData) { }
	// RVA: 0x307b898 VA: 0x7595693898
	private Void _GenerateDifficultyItems(String archiveId, RoguelikeTopicDetail topicDetail, OuterData playerData) { }
	// RVA: 0x307cef8 VA: 0x7595694ef8
	private Boolean _IsRelicItemsFiltered(RelicItemModel model, FilterRule rule) { }
	// RVA: 0x307d0fc VA: 0x75956950fc
	public Void .ctor() { }
}
```