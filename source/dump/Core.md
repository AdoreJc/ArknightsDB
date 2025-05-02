# Core

**Namespace:** ` `


## Fields

- `ActivityStageBridge m_closure`

- `ActivityBasicInfo basicInfo`

- `ActivityStageController controller`

- `Action <exitActDelegate>k__BackingField`


## Properties

- `Action exitActDelegate`

- `String currentSelectedZone`


## Methods

- `Void set_getZonesDelegate(Action`1)`

- `Void set_getCurrentSelectedZoneDelegate(Func`1)`

- `Void set_focusZoneDelegate(Func`2)`

- `Void set_findZoneDelegate(Func`2)`

- `Action get_exitActDelegate()`

- `Void set_exitActDelegate(Action)`

- `String get_currentSelectedZone()`

- `Boolean FocusZone(String)`

- `Void NotifyZoneSelected(String)`

- `Void ExitActivity()`

- `Boolean _CheckIfRetroZoneUnlock(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Core
{
	private List`1 m_zones; // 0x10
	private ActivityStageBridge m_closure; // 0x18
	public ActivityBasicInfo basicInfo; // 0x20
	public ActivityStageController controller; // 0x98
	private Action`1 <getZonesDelegate>k__BackingField; // 0xa0
	private Func`1 <getCurrentSelectedZoneDelegate>k__BackingField; // 0xa8
	private Func`2 <focusZoneDelegate>k__BackingField; // 0xb0
	private Func`2 <findZoneDelegate>k__BackingField; // 0xb8
	private Action <exitActDelegate>k__BackingField; // 0xc0

	private Action`1 getZonesDelegate { get; set; }
	private Func`1 getCurrentSelectedZoneDelegate { get; set; }
	private Func`2 focusZoneDelegate { get; set; }
	private Func`2 findZoneDelegate { get; set; }
	private Action exitActDelegate { get; set; }
	public List`1 zones { get; }
	public String currentSelectedZone { get; }

	// RVA: 0x30b6290 VA: 0x75956ce290
	public Void .ctor(ActivityStageBridge closure) { }
	// RVA: 0x30b65fc VA: 0x75956ce5fc
	private Action`1 get_getZonesDelegate() { }
	// RVA: 0x30b6604 VA: 0x75956ce604
	public Void set_getZonesDelegate(Action`1 value) { }
	// RVA: 0x30b660c VA: 0x75956ce60c
	private Func`1 get_getCurrentSelectedZoneDelegate() { }
	// RVA: 0x30b6614 VA: 0x75956ce614
	public Void set_getCurrentSelectedZoneDelegate(Func`1 value) { }
	// RVA: 0x30b661c VA: 0x75956ce61c
	private Func`2 get_focusZoneDelegate() { }
	// RVA: 0x30b6624 VA: 0x75956ce624
	public Void set_focusZoneDelegate(Func`2 value) { }
	// RVA: 0x30b662c VA: 0x75956ce62c
	private Func`2 get_findZoneDelegate() { }
	// RVA: 0x30b6634 VA: 0x75956ce634
	public Void set_findZoneDelegate(Func`2 value) { }
	// RVA: 0x30b663c VA: 0x75956ce63c
	private Action get_exitActDelegate() { }
	// RVA: 0x30b6644 VA: 0x75956ce644
	public Void set_exitActDelegate(Action value) { }
	// RVA: 0x30b6394 VA: 0x75956ce394
	public List`1 get_zones() { }
	// RVA: 0x30b64cc VA: 0x75956ce4cc
	public String get_currentSelectedZone() { }
	// RVA: 0x30b6578 VA: 0x75956ce578
	public Boolean FocusZone(String targetZoneId) { }
	// RVA: 0x30b66b0 VA: 0x75956ce6b0
	public Void NotifyZoneSelected(String selectedZoneId) { }
	// RVA: 0x30b65cc VA: 0x75956ce5cc
	public Void ExitActivity() { }
	// RVA: 0x30b664c VA: 0x75956ce64c
	private Boolean _CheckIfRetroZoneUnlock(String retroZoneId) { }
}
```