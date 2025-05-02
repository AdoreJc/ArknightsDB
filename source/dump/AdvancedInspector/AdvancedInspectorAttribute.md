# AdvancedInspectorAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Boolean inspectDefaultItems`

- `Boolean showScript`


## Properties

- `Boolean InspectDefaultItems`

- `Boolean ShowScript`


## Methods

- `Boolean get_InspectDefaultItems()`

- `Void set_InspectDefaultItems(Boolean)`

- `Boolean get_ShowScript()`

- `Void set_ShowScript(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class AdvancedInspectorAttribute : Attribute
{
	private static AdvancedInspectorForceRefresh OnForceRefresh; // 0x0
	private Boolean inspectDefaultItems; // 0x10
	private Boolean showScript; // 0x11

	public Boolean InspectDefaultItems { get; set; }
	public Boolean ShowScript { get; set; }

	// RVA: 0x1b11384 VA: 0x7594129384
	public static Void add_OnForceRefresh(AdvancedInspectorForceRefresh value) { }
	// RVA: 0x1b1143c VA: 0x759412943c
	public static Void remove_OnForceRefresh(AdvancedInspectorForceRefresh value) { }
	// RVA: 0x1b114f4 VA: 0x75941294f4
	public static Void Refresh(Boolean rebuild) { }
	// RVA: 0x1b11560 VA: 0x7594129560
	public Boolean get_InspectDefaultItems() { }
	// RVA: 0x1b11568 VA: 0x7594129568
	public Void set_InspectDefaultItems(Boolean value) { }
	// RVA: 0x1b11574 VA: 0x7594129574
	public Boolean get_ShowScript() { }
	// RVA: 0x1b1157c VA: 0x759412957c
	public Void set_ShowScript(Boolean value) { }
	// RVA: 0x1b11588 VA: 0x7594129588
	public Void .ctor() { }
	// RVA: 0x1b11598 VA: 0x7594129598
	public Void .ctor(Boolean inspectDefaultItems) { }
	// RVA: 0x1b115c8 VA: 0x75941295c8
	public Void .ctor(Boolean inspectDefaultItems, Boolean showScript) { }
}
```