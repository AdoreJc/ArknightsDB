# ArchiveTotemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String m_selectedItemId`

- `TotemItemModel m_selectedItemModel`

- `Boolean m_showSwitchAnim`


## Properties

- `String selectedItemId`

- `TotemItemModel selectedItem`

- `Boolean showSwitchAnim`

- `Int32 newNum`


## Methods

- `String get_selectedItemId()`

- `TotemItemModel get_selectedItem()`

- `Boolean get_showSwitchAnim()`

- `Int32 get_newNum()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`

- `Void SelectItem(String)`

- `String _GetDefaultItemId()`

- `Int32 _ItemComparison(KeyValuePair`2, KeyValuePair`2)`

- `Int32 _ColorComparison(RoguelikeTotemColorType, RoguelikeTotemColorType)`

- `RoguelikeArchiveItemUnlockStatus _StatusOfItem(OuterData, ActArchiveTotemItemData)`

- `String _LockedToastOfItem(String, RoguelikeTopicDetail, RoguelikeTopicItemModel, RoguelikeArchiveItemUnlockStatus)`

- `Void _GenerateItemGroups()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemModel : IHotfixable
{
	private ListDict`2 m_items; // 0x10
	private List`1 m_groups; // 0x18
	private String m_selectedItemId; // 0x20
	private TotemItemModel m_selectedItemModel; // 0x28
	private Boolean m_showSwitchAnim; // 0x30
	private static DelegateBridge __Hotfix0_get_groups; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x10
	private static DelegateBridge __Hotfix0_get_showSwitchAnim; // 0x18
	private static DelegateBridge __Hotfix0_get_newNum; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_SelectItem; // 0x30
	private static DelegateBridge __Hotfix0__GetDefaultItemId; // 0x38
	private static DelegateBridge __Hotfix0__ItemComparison; // 0x40
	private static DelegateBridge __Hotfix0__ColorComparison; // 0x48
	private static DelegateBridge __Hotfix0__StatusOfItem; // 0x50
	private static DelegateBridge __Hotfix0__LockedToastOfItem; // 0x58
	private static DelegateBridge __Hotfix0__GenerateItemGroups; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public List`1 groups { get; }
	public String selectedItemId { get; }
	public TotemItemModel selectedItem { get; }
	public Boolean showSwitchAnim { get; }
	public Int32 newNum { get; }

	// RVA: 0x308ab10 VA: 0x75956a2b10
	public List`1 get_groups() { }
	// RVA: 0x308abfc VA: 0x75956a2bfc
	public String get_selectedItemId() { }
	// RVA: 0x308aaa8 VA: 0x75956a2aa8
	public TotemItemModel get_selectedItem() { }
	// RVA: 0x308ace8 VA: 0x75956a2ce8
	public Boolean get_showSwitchAnim() { }
	// RVA: 0x308c028 VA: 0x75956a4028
	public Int32 get_newNum() { }
	// RVA: 0x308c37c VA: 0x75956a437c
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x308d4d8 VA: 0x75956a54d8
	public Void SelectItem(String id) { }
	// RVA: 0x308d600 VA: 0x75956a5600
	private String _GetDefaultItemId() { }
	// RVA: 0x308d6e8 VA: 0x75956a56e8
	private Int32 _ItemComparison(KeyValuePair`2 x, KeyValuePair`2 y) { }
	// RVA: 0x308d81c VA: 0x75956a581c
	private Int32 _ColorComparison(RoguelikeTotemColorType x, RoguelikeTotemColorType y) { }
	// RVA: 0x308ca78 VA: 0x75956a4a78
	private RoguelikeArchiveItemUnlockStatus _StatusOfItem(OuterData outerData, ActArchiveTotemItemData totemItem) { }
	// RVA: 0x308cb90 VA: 0x75956a4b90
	private String _LockedToastOfItem(String archiveId, RoguelikeTopicDetail topicDetail, RoguelikeTopicItemModel itemInfo, RoguelikeArchiveItemUnlockStatus status) { }
	// RVA: 0x308ce3c VA: 0x75956a4e3c
	private Void _GenerateItemGroups() { }
	// RVA: 0x308d908 VA: 0x75956a5908
	public Void .ctor() { }
}
```