# CampBuffAdapter

**Namespace:** ` `


## Fields

- `Boolean <hasUpdatedBuff>k__BackingField`

- `Int32 <updatedBuffIndex>k__BackingField`

- `Boolean <fastMode>k__BackingField`


## Properties

- `Boolean hasUpdatedBuff`

- `Int32 updatedBuffIndex`

- `Boolean fastMode`


## Methods

- `Void set_dataSource(List`1)`

- `Boolean get_hasUpdatedBuff()`

- `Void set_hasUpdatedBuff(Boolean)`

- `Int32 get_updatedBuffIndex()`

- `Void set_updatedBuffIndex(Int32)`

- `Boolean get_fastMode()`

- `Void set_fastMode(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CampBuffAdapter : SimpleLayoutAdapter
{
	private List`1 <dataSource>k__BackingField; // 0x20
	private Boolean <hasUpdatedBuff>k__BackingField; // 0x28
	private Int32 <updatedBuffIndex>k__BackingField; // 0x2c
	private Boolean <fastMode>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_dataSource; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSource; // 0x8
	private static DelegateBridge __Hotfix0_get_hasUpdatedBuff; // 0x10
	private static DelegateBridge __Hotfix0_set_hasUpdatedBuff; // 0x18
	private static DelegateBridge __Hotfix0_get_updatedBuffIndex; // 0x20
	private static DelegateBridge __Hotfix0_set_updatedBuffIndex; // 0x28
	private static DelegateBridge __Hotfix0_get_fastMode; // 0x30
	private static DelegateBridge __Hotfix0_set_fastMode; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x40
	private static DelegateBridge __Hotfix0_RenderView; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private List`1 dataSource { get; set; }
	private Boolean hasUpdatedBuff { get; set; }
	private Int32 updatedBuffIndex { get; set; }
	private Boolean fastMode { get; set; }
	public override Int32 count { get; }

	// RVA: 0x3369740 VA: 0x7595981740
	private List`1 get_dataSource() { }
	// RVA: 0x3369034 VA: 0x7595981034
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x33697a8 VA: 0x75959817a8
	private Boolean get_hasUpdatedBuff() { }
	// RVA: 0x33690b8 VA: 0x75959810b8
	public Void set_hasUpdatedBuff(Boolean value) { }
	// RVA: 0x3369810 VA: 0x7595981810
	private Int32 get_updatedBuffIndex() { }
	// RVA: 0x3369138 VA: 0x7595981138
	public Void set_updatedBuffIndex(Int32 value) { }
	// RVA: 0x3369878 VA: 0x7595981878
	private Boolean get_fastMode() { }
	// RVA: 0x33691b4 VA: 0x75959811b4
	public Void set_fastMode(Boolean value) { }
	// RVA: 0x33698e0 VA: 0x75959818e0
	public override Int32 get_count() { }
	// RVA: 0x3369964 VA: 0x7595981964
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x33696b4 VA: 0x75959816b4
	public Void .ctor() { }
}
```