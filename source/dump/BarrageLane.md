# BarrageLane

**Namespace:** ` `


## Fields

- `Single samplePos`

- `Int64 lastBarrageTs`

- `Single <weightValue>k__BackingField`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`

- `Void set_weightValue(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BarrageLane : IItemWithWeight
{
	public Single samplePos; // 0x10
	public Int64 lastBarrageTs; // 0x18
	private Single <weightValue>k__BackingField; // 0x20

	public Single weightValue { get; set; }

	// RVA: 0x2985788 VA: 0x7594f9d788
	public Single get_weightValue() { }
	// RVA: 0x2985790 VA: 0x7594f9d790
	public Void set_weightValue(Single value) { }
	// RVA: 0x2985798 VA: 0x7594f9d798
	public Void .ctor() { }
}
```