# TipData

**Namespace:** `Torappu`


## Fields

- `String tip`

- `Single weight`

- `Category category`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TipData : IItemWithWeight
{
	public String tip; // 0x10
	public Single weight; // 0x18
	public Category category; // 0x1c

	public Single weightValue { get; }

	// RVA: 0x34f8c5c VA: 0x7595b10c5c
	public Single get_weightValue() { }
	// RVA: 0x34f8c64 VA: 0x7595b10c64
	public Void .ctor() { }
}
```