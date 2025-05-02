# GameCityArcgachaObjectData

**Namespace:** ` `


## Fields

- `String tokenKey`

- `Int32 maxCnt`

- `Int32 weight`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCityArcgachaObjectData : IItemWithWeight
{
	public String tokenKey; // 0x10
	public Int32 maxCnt; // 0x18
	public Int32 weight; // 0x1c

	public Single weightValue { get; }

	// RVA: 0x1c582f8 VA: 0x75942702f8
	public Single get_weightValue() { }
	// RVA: 0x1c58304 VA: 0x7594270304
	public Void .ctor() { }
}
```