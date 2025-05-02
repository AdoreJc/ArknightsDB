# WorldViewTip

**Namespace:** `Torappu`


## Fields

- `String title`

- `String description`

- `String backgroundPicId`

- `Single weight`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class WorldViewTip : IItemWithWeight
{
	public String title; // 0x10
	public String description; // 0x18
	public String backgroundPicId; // 0x20
	public Single weight; // 0x28

	public Single weightValue { get; }

	// RVA: 0x34f8c78 VA: 0x7595b10c78
	public Single get_weightValue() { }
	// RVA: 0x34f8c80 VA: 0x7595b10c80
	public Void .ctor() { }
}
```