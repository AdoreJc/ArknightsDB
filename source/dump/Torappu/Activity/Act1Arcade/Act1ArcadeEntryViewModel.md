# Act1ArcadeEntryViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Int32 <allZoneScore>k__BackingField`

- `Int32 <badgeBookEntryIconIndex>k__BackingField`

- `Boolean <hasBadgeBookTrackPoint>k__BackingField`


## Properties

- `Int32 allZoneScore`

- `Int32 badgeBookEntryIconIndex`

- `Boolean hasBadgeBookTrackPoint`


## Methods

- `Void set_itemViewModels(List`1)`

- `Int32 get_allZoneScore()`

- `Void set_allZoneScore(Int32)`

- `Int32 get_badgeBookEntryIconIndex()`

- `Void set_badgeBookEntryIconIndex(Int32)`

- `Boolean get_hasBadgeBookTrackPoint()`

- `Void set_hasBadgeBookTrackPoint(Boolean)`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryViewModel : IHotfixable
{
	private List`1 <itemViewModels>k__BackingField; // 0x10
	private Int32 <allZoneScore>k__BackingField; // 0x18
	private Int32 <badgeBookEntryIconIndex>k__BackingField; // 0x1c
	private Boolean <hasBadgeBookTrackPoint>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_itemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_set_itemViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_allZoneScore; // 0x10
	private static DelegateBridge __Hotfix0_set_allZoneScore; // 0x18
	private static DelegateBridge __Hotfix0_get_badgeBookEntryIconIndex; // 0x20
	private static DelegateBridge __Hotfix0_set_badgeBookEntryIconIndex; // 0x28
	private static DelegateBridge __Hotfix0_get_hasBadgeBookTrackPoint; // 0x30
	private static DelegateBridge __Hotfix0_set_hasBadgeBookTrackPoint; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 itemViewModels { get; set; }
	public Int32 allZoneScore { get; set; }
	public Int32 badgeBookEntryIconIndex { get; set; }
	public Boolean hasBadgeBookTrackPoint { get; set; }

	// RVA: 0x34005dc VA: 0x7595a185dc
	public List`1 get_itemViewModels() { }
	// RVA: 0x3400990 VA: 0x7595a18990
	private Void set_itemViewModels(List`1 value) { }
	// RVA: 0x3400574 VA: 0x7595a18574
	public Int32 get_allZoneScore() { }
	// RVA: 0x3400a14 VA: 0x7595a18a14
	private Void set_allZoneScore(Int32 value) { }
	// RVA: 0x3400644 VA: 0x7595a18644
	public Int32 get_badgeBookEntryIconIndex() { }
	// RVA: 0x3400a90 VA: 0x7595a18a90
	private Void set_badgeBookEntryIconIndex(Int32 value) { }
	// RVA: 0x34006ac VA: 0x7595a186ac
	public Boolean get_hasBadgeBookTrackPoint() { }
	// RVA: 0x3400b0c VA: 0x7595a18b0c
	private Void set_hasBadgeBookTrackPoint(Boolean value) { }
	// RVA: 0x33ff818 VA: 0x7595a17818
	public Void LoadData(String actId) { }
	// RVA: 0x3400d90 VA: 0x7595a18d90
	public Void .ctor() { }
}
```