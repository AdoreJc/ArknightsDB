# FestivalVoiceWeightData

**Namespace:** `Torappu`


## Fields

- `CharWordShowType showType`

- `Single weight`

- `Int32 priority`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FestivalVoiceWeightData : IItemWithWeight
{
	public CharWordShowType showType; // 0x10
	public Single weight; // 0x14
	public Int32 priority; // 0x18

	public Single weightValue { get; }

	// RVA: 0x349ba04 VA: 0x7595ab3a04
	public Single get_weightValue() { }
	// RVA: 0x349ba0c VA: 0x7595ab3a0c
	public Void .ctor() { }
}
```