# Act1ArcadeBadgeBookViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeBadgeBookItemViewModel m_ultimateItem`

- `String <actId>k__BackingField`

- `String <ultimateGroupName>k__BackingField`

- `Boolean <initShow>k__BackingField`

- `BadgeBookLayoutMode <layoutMode>k__BackingField`


## Properties

- `String actId`

- `String ultimateGroupName`

- `Act1ArcadeBadgeBookItemViewModel ultimateItem`

- `Boolean initShow`

- `BadgeBookLayoutMode layoutMode`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_ultimateGroupName()`

- `Void set_ultimateGroupName(String)`

- `Act1ArcadeBadgeBookItemViewModel get_ultimateItem()`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `BadgeBookLayoutMode get_layoutMode()`

- `Void set_layoutMode(BadgeBookLayoutMode)`

- `Void LoadData(String)`

- `Void SwitchLayoutMode()`

- `Int32 GetIndexOfZoneBadge(String)`

- `Void _LoadGroupData(Dictionary`2)`

- `Void _LoadItemData(Dictionary`2)`

- `Act1ArcadeBadgeBookItemViewModel _LoadItem(ArcadeBadgeData)`

- `Void _SortGroupItems()`

- `Void _RefreshData()`

- `Void _RefreshItem(PlayerArcadeActivity, Dictionary`2, Act1ArcadeBadgeBookItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookViewModel : IHotfixable
{
	private Act1ArcadeBadgeBookItemViewModel m_ultimateItem; // 0x10
	private readonly Dictionary`2 m_badgeGroups; // 0x18
	private String <actId>k__BackingField; // 0x20
	private String <ultimateGroupName>k__BackingField; // 0x28
	private Boolean <initShow>k__BackingField; // 0x30
	private BadgeBookLayoutMode <layoutMode>k__BackingField; // 0x34
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_ultimateGroupName; // 0x10
	private static DelegateBridge __Hotfix0_set_ultimateGroupName; // 0x18
	private static DelegateBridge __Hotfix0_get_ultimateItem; // 0x20
	private static DelegateBridge __Hotfix0_get_badgeGroups; // 0x28
	private static DelegateBridge __Hotfix0_get_initShow; // 0x30
	private static DelegateBridge __Hotfix0_set_initShow; // 0x38
	private static DelegateBridge __Hotfix0_get_layoutMode; // 0x40
	private static DelegateBridge __Hotfix0_set_layoutMode; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_SwitchLayoutMode; // 0x58
	private static DelegateBridge __Hotfix0_GetIndexOfZoneBadge; // 0x60
	private static DelegateBridge __Hotfix0__LoadGroupData; // 0x68
	private static DelegateBridge __Hotfix0__LoadItemData; // 0x70
	private static DelegateBridge __Hotfix0__LoadItem; // 0x78
	private static DelegateBridge __Hotfix0__SortGroupItems; // 0x80
	private static DelegateBridge __Hotfix0__RefreshData; // 0x88
	private static DelegateBridge __Hotfix0__RefreshItem; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public String actId { get; set; }
	public String ultimateGroupName { get; set; }
	public Act1ArcadeBadgeBookItemViewModel ultimateItem { get; }
	public Dictionary`2 badgeGroups { get; }
	public Boolean initShow { get; set; }
	public BadgeBookLayoutMode layoutMode { get; set; }

	// RVA: 0x33f85b4 VA: 0x7595a105b4
	public String get_actId() { }
	// RVA: 0x33fc30c VA: 0x7595a1430c
	private Void set_actId(String value) { }
	// RVA: 0x33fb0ec VA: 0x7595a130ec
	public String get_ultimateGroupName() { }
	// RVA: 0x33fc390 VA: 0x7595a14390
	private Void set_ultimateGroupName(String value) { }
	// RVA: 0x33f861c VA: 0x7595a1061c
	public Act1ArcadeBadgeBookItemViewModel get_ultimateItem() { }
	// RVA: 0x33f8684 VA: 0x7595a10684
	public Dictionary`2 get_badgeGroups() { }
	// RVA: 0x33fb1bc VA: 0x7595a131bc
	public Boolean get_initShow() { }
	// RVA: 0x33f8534 VA: 0x7595a10534
	public Void set_initShow(Boolean value) { }
	// RVA: 0x33fb154 VA: 0x7595a13154
	public BadgeBookLayoutMode get_layoutMode() { }
	// RVA: 0x33fc414 VA: 0x7595a14414
	private Void set_layoutMode(BadgeBookLayoutMode value) { }
	// RVA: 0x33f8eec VA: 0x7595a10eec
	public Void LoadData(String actId) { }
	// RVA: 0x33f89a8 VA: 0x7595a109a8
	public Void SwitchLayoutMode() { }
	// RVA: 0x33f9210 VA: 0x7595a11210
	public Int32 GetIndexOfZoneBadge(String zoneId) { }
	// RVA: 0x33fc490 VA: 0x7595a14490
	private Void _LoadGroupData(Dictionary`2 badgeTypeDataDict) { }
	// RVA: 0x33fc6e8 VA: 0x7595a146e8
	private Void _LoadItemData(Dictionary`2 badgeDataDict) { }
	// RVA: 0x33fcc4c VA: 0x7595a14c4c
	private Act1ArcadeBadgeBookItemViewModel _LoadItem(ArcadeBadgeData data) { }
	// RVA: 0x33fc904 VA: 0x7595a14904
	private Void _SortGroupItems() { }
	// RVA: 0x33fca4c VA: 0x7595a14a4c
	private Void _RefreshData() { }
	// RVA: 0x33fcf7c VA: 0x7595a14f7c
	private Void _RefreshItem(PlayerArcadeActivity playerData, Dictionary`2 badgeInfoDict, Act1ArcadeBadgeBookItemViewModel item) { }
	// RVA: 0x33fd174 VA: 0x7595a15174
	public Void .ctor() { }
}
```