# RandomActionPtr

**Namespace:** ` `


## Fields

- `RandomGroupKey key`

- `String packKey`

- `Int32 actionIndex`

- `Int32 weight`

- `Boolean isEmpty`

- `Int32 order`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`

- `Int32 CompareTo(RandomActionPtr)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RandomActionPtr : IItemWithWeight, IComparable`1
{
	public RandomGroupKey key; // 0x10
	public String packKey; // 0x20
	public Int32 actionIndex; // 0x28
	public Int32 weight; // 0x2c
	public Boolean isEmpty; // 0x30
	public Int32 order; // 0x34

	public Single weightValue { get; }

	// RVA: 0x40e3b80 VA: 0x75966fbb80
	public Single get_weightValue() { }
	// RVA: 0x40e3b8c VA: 0x75966fbb8c
	public Int32 CompareTo(RandomActionPtr action) { }
	// RVA: 0x40e3868 VA: 0x75966fb868
	public Void .ctor() { }
}
```