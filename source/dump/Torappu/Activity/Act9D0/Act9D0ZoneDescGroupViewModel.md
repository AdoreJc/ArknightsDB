# Act9D0ZoneDescGroupViewModel

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String <selectedZoneId>k__BackingField`

- `Boolean <isAllTimeout>k__BackingField`


## Properties

- `String selectedZoneId`

- `Boolean isAllTimeout`


## Methods

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `Boolean get_isAllTimeout()`

- `Void set_isAllTimeout(Boolean)`

- `Void LoadData(ActivityBasicInfo, List`1)`

- `Void SetSelectedZone(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0ZoneDescGroupViewModel
{
	public List`1 zoneDescModelList; // 0x10
	private String <selectedZoneId>k__BackingField; // 0x18
	private Boolean <isAllTimeout>k__BackingField; // 0x20

	public String selectedZoneId { get; set; }
	public Boolean isAllTimeout { get; set; }

	// RVA: 0x31ae714 VA: 0x75957c6714
	public String get_selectedZoneId() { }
	// RVA: 0x31ae71c VA: 0x75957c671c
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x31ae724 VA: 0x75957c6724
	public Boolean get_isAllTimeout() { }
	// RVA: 0x31ae72c VA: 0x75957c672c
	private Void set_isAllTimeout(Boolean value) { }
	// RVA: 0x31ae738 VA: 0x75957c6738
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 actZoneModels) { }
	// RVA: 0x31aeabc VA: 0x75957c6abc
	public Void SetSelectedZone(String zoneId) { }
	// RVA: 0x31aebb4 VA: 0x75957c6bb4
	public Void .ctor() { }
}
```