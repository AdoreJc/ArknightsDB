# Act12sideZoneDescGroupViewModel

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `String <selectedZoneId>k__BackingField`

- `ActZoneClass <selectedZoneClass>k__BackingField`

- `Boolean <isAllTimeOut>k__BackingField`


## Properties

- `String selectedZoneId`

- `ActZoneClass selectedZoneClass`

- `Boolean isAllTimeOut`


## Methods

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `ActZoneClass get_selectedZoneClass()`

- `Void set_selectedZoneClass(ActZoneClass)`

- `Boolean get_isAllTimeOut()`

- `Void set_isAllTimeOut(Boolean)`

- `Void LoadData(ActivityBasicInfo, List`1)`

- `Void SetSelectedZone(String, String)`

- `Void _UpdateSelectedZoneClass()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideZoneDescGroupViewModel
{
	public List`1 zoneDescModelList; // 0x10
	private String <selectedZoneId>k__BackingField; // 0x18
	private ActZoneClass <selectedZoneClass>k__BackingField; // 0x20
	private Boolean <isAllTimeOut>k__BackingField; // 0x24

	public String selectedZoneId { get; set; }
	public ActZoneClass selectedZoneClass { get; set; }
	public Boolean isAllTimeOut { get; set; }

	// RVA: 0x3461420 VA: 0x7595a79420
	public String get_selectedZoneId() { }
	// RVA: 0x3461428 VA: 0x7595a79428
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x3461430 VA: 0x7595a79430
	public ActZoneClass get_selectedZoneClass() { }
	// RVA: 0x3461438 VA: 0x7595a79438
	private Void set_selectedZoneClass(ActZoneClass value) { }
	// RVA: 0x3461440 VA: 0x7595a79440
	public Boolean get_isAllTimeOut() { }
	// RVA: 0x3461448 VA: 0x7595a79448
	private Void set_isAllTimeOut(Boolean value) { }
	// RVA: 0x3461454 VA: 0x7595a79454
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 actZoneModels) { }
	// RVA: 0x3461910 VA: 0x7595a79910
	public Void SetSelectedZone(String activityId, String zoneId) { }
	// RVA: 0x346182c VA: 0x7595a7982c
	private Void _UpdateSelectedZoneClass() { }
	// RVA: 0x3461b58 VA: 0x7595a79b58
	public Void .ctor() { }
}
```