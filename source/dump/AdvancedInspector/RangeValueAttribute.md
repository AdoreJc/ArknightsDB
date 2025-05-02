# RangeValueAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `Single min`

- `Single max`


## Properties

- `Single Min`

- `Single Max`


## Methods

- `Single get_Min()`

- `Void set_Min(Single)`

- `Single get_Max()`

- `Void set_Max(Single)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class RangeValueAttribute : Attribute, IListAttribute
{
	private Single min; // 0x10
	private Single max; // 0x14

	public Single Min { get; set; }
	public Single Max { get; set; }

	// RVA: 0x1b18438 VA: 0x7594130438
	public Single get_Min() { }
	// RVA: 0x1b18440 VA: 0x7594130440
	public Void set_Min(Single value) { }
	// RVA: 0x1b18448 VA: 0x7594130448
	public Single get_Max() { }
	// RVA: 0x1b18450 VA: 0x7594130450
	public Void set_Max(Single value) { }
	// RVA: 0x1b18458 VA: 0x7594130458
	public Void .ctor(Single min, Single max) { }
}
```