# Data

**Namespace:** ` `


## Fields

- `Int32 version`

- `Boolean <isDirty>k__BackingField`


## Properties

- `Boolean isDirty`


## Methods

- `Boolean get_isDirty()`

- `Void set_isDirty(Boolean)`

- `Void SetChannel(LogChannel, Boolean)`

- `Void SaveToDisk()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Data
{
	public Dictionary`2 channels; // 0x10
	public Int32 version; // 0x18
	private Boolean <isDirty>k__BackingField; // 0x1c

	public Boolean isDirty { get; set; }

	// RVA: 0x67b6b90 VA: 0x7598dceb90
	public Boolean get_isDirty() { }
	// RVA: 0x67b6b98 VA: 0x7598dceb98
	private Void set_isDirty(Boolean value) { }
	// RVA: 0x67b698c VA: 0x7598dce98c
	public Void SetChannel(LogChannel channel, Boolean enabled) { }
	// RVA: 0x67b6ba4 VA: 0x7598dceba4
	public Void SaveToDisk() { }
	// RVA: 0x67b6724 VA: 0x7598dce724
	public Void .ctor() { }
}
```