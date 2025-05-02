# StageStorylineViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Int64 m_startTs`

- `String <storylineId>k__BackingField`

- `StorylineType <storylineType>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <name>k__BackingField`

- `String <iconId>k__BackingField`

- `String <backgroundId>k__BackingField`

- `Boolean <presented>k__BackingField`

- `Boolean <hasTrackPoint>k__BackingField`


## Properties

- `String storylineId`

- `StorylineType storylineType`

- `Int32 sortId`

- `String name`

- `String iconId`

- `String backgroundId`

- `Boolean presented`

- `Boolean hasTrackPoint`


## Methods

- `String get_storylineId()`

- `Void set_storylineId(String)`

- `StorylineType get_storylineType()`

- `Void set_storylineType(StorylineType)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_iconId()`

- `Void set_iconId(String)`

- `String get_backgroundId()`

- `Void set_backgroundId(String)`

- `Boolean get_presented()`

- `Void set_presented(Boolean)`

- `Boolean get_hasTrackPoint()`

- `Void set_hasTrackPoint(Boolean)`

- `Void LoadData(StorylineData, Dictionary`2)`

- `Void RefreshData()`

- `Void _LoadLocations(ListDict`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineViewModel : IHotfixable
{
	private Int64 m_startTs; // 0x10
	private readonly List`1 m_locations; // 0x18
	private readonly List`1 m_presentedLocations; // 0x20
	private readonly List`1 m_presentedStorySets; // 0x28
	private String <storylineId>k__BackingField; // 0x30
	private StorylineType <storylineType>k__BackingField; // 0x38
	private Int32 <sortId>k__BackingField; // 0x3c
	private String <name>k__BackingField; // 0x40
	private String <iconId>k__BackingField; // 0x48
	private String <backgroundId>k__BackingField; // 0x50
	private Boolean <presented>k__BackingField; // 0x58
	private Boolean <hasTrackPoint>k__BackingField; // 0x59
	private static DelegateBridge __Hotfix0_get_storylineId; // 0x0
	private static DelegateBridge __Hotfix0_set_storylineId; // 0x8
	private static DelegateBridge __Hotfix0_get_storylineType; // 0x10
	private static DelegateBridge __Hotfix0_set_storylineType; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x30
	private static DelegateBridge __Hotfix0_set_name; // 0x38
	private static DelegateBridge __Hotfix0_get_iconId; // 0x40
	private static DelegateBridge __Hotfix0_set_iconId; // 0x48
	private static DelegateBridge __Hotfix0_get_backgroundId; // 0x50
	private static DelegateBridge __Hotfix0_set_backgroundId; // 0x58
	private static DelegateBridge __Hotfix0_get_presentedLocations; // 0x60
	private static DelegateBridge __Hotfix0_get_presentedStorySets; // 0x68
	private static DelegateBridge __Hotfix0_get_presented; // 0x70
	private static DelegateBridge __Hotfix0_set_presented; // 0x78
	private static DelegateBridge __Hotfix0_get_hasTrackPoint; // 0x80
	private static DelegateBridge __Hotfix0_set_hasTrackPoint; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_RefreshData; // 0x98
	private static DelegateBridge __Hotfix0__LoadLocations; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String storylineId { get; set; }
	public StorylineType storylineType { get; set; }
	public Int32 sortId { get; set; }
	public String name { get; set; }
	public String iconId { get; set; }
	public String backgroundId { get; set; }
	public List`1 presentedLocations { get; }
	public List`1 presentedStorySets { get; }
	public Boolean presented { get; set; }
	public Boolean hasTrackPoint { get; set; }

	// RVA: 0x2ff7b20 VA: 0x759560fb20
	public String get_storylineId() { }
	// RVA: 0x2ff7b88 VA: 0x759560fb88
	private Void set_storylineId(String value) { }
	// RVA: 0x2ff7c0c VA: 0x759560fc0c
	public StorylineType get_storylineType() { }
	// RVA: 0x2ff7c74 VA: 0x759560fc74
	private Void set_storylineType(StorylineType value) { }
	// RVA: 0x2ff7cf0 VA: 0x759560fcf0
	public Int32 get_sortId() { }
	// RVA: 0x2ff7d58 VA: 0x759560fd58
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2ff7dd4 VA: 0x759560fdd4
	public String get_name() { }
	// RVA: 0x2ff7e3c VA: 0x759560fe3c
	private Void set_name(String value) { }
	// RVA: 0x2ff7ec0 VA: 0x759560fec0
	public String get_iconId() { }
	// RVA: 0x2ff7f28 VA: 0x759560ff28
	private Void set_iconId(String value) { }
	// RVA: 0x2ff7fac VA: 0x759560ffac
	public String get_backgroundId() { }
	// RVA: 0x2ff8014 VA: 0x7595610014
	private Void set_backgroundId(String value) { }
	// RVA: 0x2ff8098 VA: 0x7595610098
	public List`1 get_presentedLocations() { }
	// RVA: 0x2ff8100 VA: 0x7595610100
	public List`1 get_presentedStorySets() { }
	// RVA: 0x2ff8168 VA: 0x7595610168
	public Boolean get_presented() { }
	// RVA: 0x2ff81d0 VA: 0x75956101d0
	private Void set_presented(Boolean value) { }
	// RVA: 0x2ff8250 VA: 0x7595610250
	public Boolean get_hasTrackPoint() { }
	// RVA: 0x2ff82b8 VA: 0x75956102b8
	private Void set_hasTrackPoint(Boolean value) { }
	// RVA: 0x2ff8338 VA: 0x7595610338
	public Void LoadData(StorylineData data, Dictionary`2 storySetDict) { }
	// RVA: 0x2ff8ce0 VA: 0x7595610ce0
	public Void RefreshData() { }
	// RVA: 0x2ff8494 VA: 0x7595610494
	private Void _LoadLocations(ListDict`2 locationListDict, Dictionary`2 storySetDict) { }
	// RVA: 0x2ff8e84 VA: 0x7595610e84
	public Void .ctor() { }
}
```