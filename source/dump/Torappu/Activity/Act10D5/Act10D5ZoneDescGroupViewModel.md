# Act10D5ZoneDescGroupViewModel

**Namespace:** `Torappu.Activity.Act10D5`


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
// Namespace : Torappu.Activity.Act10D5
public class Act10D5ZoneDescGroupViewModel
{
	public List`1 zoneDescModelList; // 0x10
	private String <selectedZoneId>k__BackingField; // 0x18
	private Boolean <isAllTimeout>k__BackingField; // 0x20

	public String selectedZoneId { get; set; }
	public Boolean isAllTimeout { get; set; }

	// RVA: 0x3489558 VA: 0x7595aa1558
	public String get_selectedZoneId() { }
	// RVA: 0x3489560 VA: 0x7595aa1560
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x3489568 VA: 0x7595aa1568
	public Boolean get_isAllTimeout() { }
	// RVA: 0x3489570 VA: 0x7595aa1570
	private Void set_isAllTimeout(Boolean value) { }
	// RVA: 0x348957c VA: 0x7595aa157c
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 actZoneModels) { }
	// RVA: 0x34898c0 VA: 0x7595aa18c0
	public Void SetSelectedZone(String zoneId) { }
	// RVA: 0x34899b8 VA: 0x7595aa19b8
	public Void .ctor() { }
}
```