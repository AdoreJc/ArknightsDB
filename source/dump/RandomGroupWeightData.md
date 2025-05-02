# RandomGroupWeightData

**Namespace:** ` `


## Fields

- `RandomGroupKey randomGroupKey`

- `Single totalWeight`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RandomGroupWeightData : IItemWithWeight
{
	public RandomGroupKey randomGroupKey; // 0x10
	public Single totalWeight; // 0x20

	public Single weightValue { get; }

	// RVA: 0x40e3bbc VA: 0x75966fbbbc
	public Single get_weightValue() { }
	// RVA: 0x40e3870 VA: 0x75966fb870
	public Void .ctor() { }
}
```