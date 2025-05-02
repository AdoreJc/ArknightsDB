# StageStorylineCollectViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `String <name>k__BackingField`

- `String <desc>k__BackingField`

- `String <backgroundId>k__BackingField`

- `Boolean m_hasNewTag`

- `Boolean <hasTrail>k__BackingField`


## Properties

- `String name`

- `String desc`

- `String backgroundId`

- `Boolean hasTrail`


## Methods

- `String get_name()`

- `Void set_name(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_backgroundId()`

- `Void set_backgroundId(String)`

- `Boolean get_hasTrail()`

- `Void set_hasTrail(Boolean)`

- `Void _RefreshStoryProgress()`

- `Void _RefreshTrailStatus()`

- `Void OnRetroSelected()`

- `Void <>xLuaBaseProxy_LoadData(StorylineStorySetData, Dictionary`2)`

- `Void <>xLuaBaseProxy_RefreshData()`

- `Boolean <>xLuaBaseProxy_CheckCoreRewardValid()`

- `Boolean <>xLuaBaseProxy_CheckNewTagValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineCollectViewModel : StageStorylineStorySetViewModel
{
	private String <name>k__BackingField; // 0x80
	private String <desc>k__BackingField; // 0x88
	private String <backgroundId>k__BackingField; // 0x90
	private Boolean m_hasNewTag; // 0x98
	private Boolean <hasTrail>k__BackingField; // 0x99
	private static DelegateBridge __Hotfix0_get_name; // 0x0
	private static DelegateBridge __Hotfix0_set_name; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_backgroundId; // 0x20
	private static DelegateBridge __Hotfix0_set_backgroundId; // 0x28
	private static DelegateBridge __Hotfix0_get_hasTrail; // 0x30
	private static DelegateBridge __Hotfix0_set_hasTrail; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x48
	private static DelegateBridge __Hotfix0__RefreshStoryProgress; // 0x50
	private static DelegateBridge __Hotfix0__RefreshTrailStatus; // 0x58
	private static DelegateBridge __Hotfix0_CheckCoreRewardValid; // 0x60
	private static DelegateBridge __Hotfix0_CheckNewTagValid; // 0x68
	private static DelegateBridge __Hotfix0_OnRetroSelected; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String name { get; set; }
	public String desc { get; set; }
	public String backgroundId { get; set; }
	public Boolean hasTrail { get; set; }

	// RVA: 0x2ff6768 VA: 0x759560e768
	public String get_name() { }
	// RVA: 0x2ff67d0 VA: 0x759560e7d0
	private Void set_name(String value) { }
	// RVA: 0x2ff6854 VA: 0x759560e854
	public String get_desc() { }
	// RVA: 0x2ff68bc VA: 0x759560e8bc
	private Void set_desc(String value) { }
	// RVA: 0x2ff6940 VA: 0x759560e940
	public String get_backgroundId() { }
	// RVA: 0x2ff69a8 VA: 0x759560e9a8
	private Void set_backgroundId(String value) { }
	// RVA: 0x2ff6a2c VA: 0x759560ea2c
	public Boolean get_hasTrail() { }
	// RVA: 0x2ff6a94 VA: 0x759560ea94
	private Void set_hasTrail(Boolean value) { }
	// RVA: 0x2ff6b14 VA: 0x759560eb14
	public override Void LoadData(StorylineStorySetData data, Dictionary`2 tagDict) { }
	// RVA: 0x2ff6be0 VA: 0x759560ebe0
	public override Void RefreshData() { }
	// RVA: 0x2ff6cb8 VA: 0x759560ecb8
	private Void _RefreshStoryProgress() { }
	// RVA: 0x2ff6f58 VA: 0x759560ef58
	private Void _RefreshTrailStatus() { }
	// RVA: 0x2ff7270 VA: 0x759560f270
	public override Boolean CheckCoreRewardValid() { }
	// RVA: 0x2ff72f4 VA: 0x759560f2f4
	public override Boolean CheckNewTagValid() { }
	// RVA: 0x2ff735c VA: 0x759560f35c
	public Void OnRetroSelected() { }
	// RVA: 0x2ff7410 VA: 0x759560f410
	public Void .ctor() { }
	// RVA: 0x2ff747c VA: 0x759560f47c
	private Void <>xLuaBaseProxy_LoadData(StorylineStorySetData P0, Dictionary`2 P1) { }
	// RVA: 0x2ff7480 VA: 0x759560f480
	private Void <>xLuaBaseProxy_RefreshData() { }
	// RVA: 0x2ff7484 VA: 0x759560f484
	private Boolean <>xLuaBaseProxy_CheckCoreRewardValid() { }
	// RVA: 0x2ff7488 VA: 0x759560f488
	private Boolean <>xLuaBaseProxy_CheckNewTagValid() { }
}
```