# Act6FunZoneMapStagePreviewPluginAchieveItemModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `String <achievementId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <desc>k__BackingField`

- `Boolean <hasComplete>k__BackingField`


## Properties

- `String achievementId`

- `Int32 sortId`

- `String desc`

- `Boolean hasComplete`


## Methods

- `String get_achievementId()`

- `Void set_achievementId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_desc()`

- `Void set_desc(String)`

- `Boolean get_hasComplete()`

- `Void set_hasComplete(Boolean)`

- `Void LoadData(Act6FunAchievementData)`

- `Void RefreshData(Boolean)`

- `Int32 CompareTo(Act6FunZoneMapStagePreviewPluginAchieveItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapStagePreviewPluginAchieveItemModel : IHotfixable, IComparable`1
{
	private String <achievementId>k__BackingField; // 0x10
	private Int32 <sortId>k__BackingField; // 0x18
	private String <desc>k__BackingField; // 0x20
	private Boolean <hasComplete>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_achievementId; // 0x0
	private static DelegateBridge __Hotfix0_set_achievementId; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_set_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_desc; // 0x20
	private static DelegateBridge __Hotfix0_set_desc; // 0x28
	private static DelegateBridge __Hotfix0_get_hasComplete; // 0x30
	private static DelegateBridge __Hotfix0_set_hasComplete; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x48
	private static DelegateBridge __Hotfix0_CompareTo; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String achievementId { get; set; }
	public Int32 sortId { get; set; }
	public String desc { get; set; }
	public Boolean hasComplete { get; set; }

	// RVA: 0x31b320c VA: 0x75957cb20c
	public String get_achievementId() { }
	// RVA: 0x31b3274 VA: 0x75957cb274
	private Void set_achievementId(String value) { }
	// RVA: 0x31b32f8 VA: 0x75957cb2f8
	public Int32 get_sortId() { }
	// RVA: 0x31b3360 VA: 0x75957cb360
	private Void set_sortId(Int32 value) { }
	// RVA: 0x31b33dc VA: 0x75957cb3dc
	public String get_desc() { }
	// RVA: 0x31b3444 VA: 0x75957cb444
	private Void set_desc(String value) { }
	// RVA: 0x31b34c8 VA: 0x75957cb4c8
	public Boolean get_hasComplete() { }
	// RVA: 0x31b3530 VA: 0x75957cb530
	private Void set_hasComplete(Boolean value) { }
	// RVA: 0x31b35b0 VA: 0x75957cb5b0
	public Void LoadData(Act6FunAchievementData data) { }
	// RVA: 0x31b365c VA: 0x75957cb65c
	public Void RefreshData(Boolean complete) { }
	// RVA: 0x31b36dc VA: 0x75957cb6dc
	public Int32 CompareTo(Act6FunZoneMapStagePreviewPluginAchieveItemModel other) { }
	// RVA: 0x31b37a4 VA: 0x75957cb7a4
	public Void .ctor() { }
}
```