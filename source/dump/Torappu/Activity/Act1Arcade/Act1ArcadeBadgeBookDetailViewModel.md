# Act1ArcadeBadgeBookDetailViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeBadgeBookItemViewModel m_ultimateItem`

- `String <actId>k__BackingField`

- `Int32 <presentingIndex>k__BackingField`

- `Act1ArcadeBadgeBookItemViewModel <presentingItem>k__BackingField`

- `Boolean <initShow>k__BackingField`


## Properties

- `String actId`

- `Int32 presentingIndex`

- `Act1ArcadeBadgeBookItemViewModel presentingItem`

- `Boolean initShow`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Int32 get_presentingIndex()`

- `Void set_presentingIndex(Int32)`

- `Act1ArcadeBadgeBookItemViewModel get_presentingItem()`

- `Void set_presentingItem(Act1ArcadeBadgeBookItemViewModel)`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `Void LoadData(String, Act1ArcadeBadgeBookItemViewModel, Dictionary`2, String)`

- `Void SwitchItem(Boolean)`

- `Void _MapItems(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookDetailViewModel : IHotfixable
{
	private Act1ArcadeBadgeBookItemViewModel m_ultimateItem; // 0x10
	private readonly List`1 m_badgeGroupList; // 0x18
	private readonly List`1 m_mappedItems; // 0x20
	private String <actId>k__BackingField; // 0x28
	private Int32 <presentingIndex>k__BackingField; // 0x30
	private Act1ArcadeBadgeBookItemViewModel <presentingItem>k__BackingField; // 0x38
	private Boolean <initShow>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_mappedItems; // 0x10
	private static DelegateBridge __Hotfix0_get_presentingIndex; // 0x18
	private static DelegateBridge __Hotfix0_set_presentingIndex; // 0x20
	private static DelegateBridge __Hotfix0_get_presentingItem; // 0x28
	private static DelegateBridge __Hotfix0_set_presentingItem; // 0x30
	private static DelegateBridge __Hotfix0_get_initShow; // 0x38
	private static DelegateBridge __Hotfix0_set_initShow; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_SwitchItem; // 0x50
	private static DelegateBridge __Hotfix0__MapItems; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String actId { get; set; }
	public List`1 mappedItems { get; }
	public Int32 presentingIndex { get; set; }
	public Act1ArcadeBadgeBookItemViewModel presentingItem { get; set; }
	public Boolean initShow { get; set; }

	// RVA: 0x33f423c VA: 0x7595a0c23c
	public String get_actId() { }
	// RVA: 0x33f42a4 VA: 0x7595a0c2a4
	private Void set_actId(String value) { }
	// RVA: 0x33f4328 VA: 0x7595a0c328
	public List`1 get_mappedItems() { }
	// RVA: 0x33f4390 VA: 0x7595a0c390
	public Int32 get_presentingIndex() { }
	// RVA: 0x33f43f8 VA: 0x7595a0c3f8
	private Void set_presentingIndex(Int32 value) { }
	// RVA: 0x33f4474 VA: 0x7595a0c474
	public Act1ArcadeBadgeBookItemViewModel get_presentingItem() { }
	// RVA: 0x33f44dc VA: 0x7595a0c4dc
	private Void set_presentingItem(Act1ArcadeBadgeBookItemViewModel value) { }
	// RVA: 0x33f4560 VA: 0x7595a0c560
	public Boolean get_initShow() { }
	// RVA: 0x33f45c8 VA: 0x7595a0c5c8
	private Void set_initShow(Boolean value) { }
	// RVA: 0x33f4648 VA: 0x7595a0c648
	public Void LoadData(String actId, Act1ArcadeBadgeBookItemViewModel ultimateItem, Dictionary`2 badgeGroups, String presentingBadgeId) { }
	// RVA: 0x33f4c34 VA: 0x7595a0cc34
	public Void SwitchItem(Boolean forward) { }
	// RVA: 0x33f488c VA: 0x7595a0c88c
	private Void _MapItems(String presentingBadgeId) { }
	// RVA: 0x33f4d88 VA: 0x7595a0cd88
	public Void .ctor() { }
}
```