# Act13sideZoneDescGroupViewModel

**Namespace:** `Torappu.UI.ActivityStage`


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
// Namespace : Torappu.UI.ActivityStage
public class Act13sideZoneDescGroupViewModel
{
	public List`1 zoneDescModelList; // 0x10
	private String <selectedZoneId>k__BackingField; // 0x18
	private ActZoneClass <selectedZoneClass>k__BackingField; // 0x20
	private Boolean <isAllTimeOut>k__BackingField; // 0x24

	public String selectedZoneId { get; set; }
	public ActZoneClass selectedZoneClass { get; set; }
	public Boolean isAllTimeOut { get; set; }

	// RVA: 0x3093854 VA: 0x75956ab854
	public String get_selectedZoneId() { }
	// RVA: 0x309385c VA: 0x75956ab85c
	private Void set_selectedZoneId(String value) { }
	// RVA: 0x3093864 VA: 0x75956ab864
	public ActZoneClass get_selectedZoneClass() { }
	// RVA: 0x309386c VA: 0x75956ab86c
	private Void set_selectedZoneClass(ActZoneClass value) { }
	// RVA: 0x3093874 VA: 0x75956ab874
	public Boolean get_isAllTimeOut() { }
	// RVA: 0x309387c VA: 0x75956ab87c
	private Void set_isAllTimeOut(Boolean value) { }
	// RVA: 0x3093888 VA: 0x75956ab888
	public Void LoadData(ActivityBasicInfo actBasicInfo, List`1 actZoneModels) { }
	// RVA: 0x3093cb8 VA: 0x75956abcb8
	public Void SetSelectedZone(String activityId, String zoneId) { }
	// RVA: 0x3093bdc VA: 0x75956abbdc
	private Void _UpdateSelectedZoneClass() { }
	// RVA: 0x3093ef4 VA: 0x75956abef4
	public Void .ctor() { }
}
```