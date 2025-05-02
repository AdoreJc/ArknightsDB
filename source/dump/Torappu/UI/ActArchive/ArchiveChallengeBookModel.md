# ArchiveChallengeBookModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String <archiveId>k__BackingField`

- `String <selectedId>k__BackingField`

- `ChallengeBookItemModel <selectedItem>k__BackingField`

- `Boolean <showSwitchTween>k__BackingField`


## Properties

- `String archiveId`

- `String selectedId`

- `ChallengeBookItemModel selectedItem`

- `Boolean showSwitchTween`


## Methods

- `String get_archiveId()`

- `Void set_archiveId(String)`

- `String get_selectedId()`

- `Void set_selectedId(String)`

- `ChallengeBookItemModel get_selectedItem()`

- `Void set_selectedItem(ChallengeBookItemModel)`

- `Boolean get_showSwitchTween()`

- `Void set_showSwitchTween(Boolean)`

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `ChallengeBookArchiveResItemData _getArchivePicResData(String)`

- `Void SelectItem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChallengeBookModel : IHotfixable
{
	private readonly Dictionary`2 m_items; // 0x10
	private readonly List`1 m_itemList; // 0x18
	private String <archiveId>k__BackingField; // 0x20
	private String <selectedId>k__BackingField; // 0x28
	private ChallengeBookItemModel <selectedItem>k__BackingField; // 0x30
	private Boolean <showSwitchTween>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_archiveId; // 0x0
	private static DelegateBridge __Hotfix0_set_archiveId; // 0x8
	private static DelegateBridge __Hotfix0_get_items; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedId; // 0x18
	private static DelegateBridge __Hotfix0_set_selectedId; // 0x20
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x28
	private static DelegateBridge __Hotfix0_set_selectedItem; // 0x30
	private static DelegateBridge __Hotfix0_get_showSwitchTween; // 0x38
	private static DelegateBridge __Hotfix0_set_showSwitchTween; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0__getArchivePicResData; // 0x50
	private static DelegateBridge __Hotfix0_SelectItem; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String archiveId { get; set; }
	public List`1 items { get; }
	public String selectedId { get; set; }
	public ChallengeBookItemModel selectedItem { get; set; }
	public Boolean showSwitchTween { get; set; }

	// RVA: 0x303ed6c VA: 0x7595656d6c
	public String get_archiveId() { }
	// RVA: 0x303edd4 VA: 0x7595656dd4
	private Void set_archiveId(String value) { }
	// RVA: 0x303d8f4 VA: 0x75956558f4
	public List`1 get_items() { }
	// RVA: 0x303ee58 VA: 0x7595656e58
	public String get_selectedId() { }
	// RVA: 0x303eec0 VA: 0x7595656ec0
	private Void set_selectedId(String value) { }
	// RVA: 0x303d9c4 VA: 0x75956559c4
	public ChallengeBookItemModel get_selectedItem() { }
	// RVA: 0x303ef44 VA: 0x7595656f44
	private Void set_selectedItem(ChallengeBookItemModel value) { }
	// RVA: 0x303d95c VA: 0x759565595c
	public Boolean get_showSwitchTween() { }
	// RVA: 0x303efc8 VA: 0x7595656fc8
	private Void set_showSwitchTween(Boolean value) { }
	// RVA: 0x303f048 VA: 0x7595657048
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x303f4e4 VA: 0x75956574e4
	private ChallengeBookArchiveResItemData _getArchivePicResData(String storyId) { }
	// RVA: 0x303f614 VA: 0x7595657614
	public Void SelectItem(String storyId) { }
	// RVA: 0x303f7e0 VA: 0x75956577e0
	public Void .ctor() { }
}
```