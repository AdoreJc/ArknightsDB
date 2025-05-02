# AdvancedGachaResponse

**Namespace:** `Torappu`


## Fields

- `Int32 result`

- `GachaResult charGet`


## Methods

- `GachaResult GetGachaResult()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AdvancedGachaResponse : PlayerDeltaResponse, IGachaResultHolder
{
	public Int32 result; // 0x28
	public GachaResult charGet; // 0x30


	// RVA: 0x32cb974 VA: 0x75958e3974
	public GachaResult GetGachaResult() { }
	// RVA: 0x32cb97c VA: 0x75958e397c
	public Void .ctor() { }
}
```