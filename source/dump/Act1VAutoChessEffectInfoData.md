# Act1VAutoChessEffectInfoData

**Namespace:** ` `


## Fields

- `String effectId`

- `Act1VAutoChessEffectType effectType`

- `Act1VAutoChessEffectCounterType effectCounterType`

- `Int32 continuedRound`

- `String effectName`

- `String effectDesc`

- `String effectDecoIconId`

- `Boolean isMainEnemyEffect`


## Methods

- `Boolean ShouldSerializeeffectCounterType()`

- `Boolean ShouldSerializeeffectDecoIconId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act1VAutoChessEffectInfoData
{
	public String effectId; // 0x10
	public Act1VAutoChessEffectType effectType; // 0x18
	public Act1VAutoChessEffectCounterType effectCounterType; // 0x1c
	public Int32 continuedRound; // 0x20
	public String effectName; // 0x28
	public String effectDesc; // 0x30
	public String effectDecoIconId; // 0x38
	public Boolean isMainEnemyEffect; // 0x40


	// RVA: 0x33b98d0 VA: 0x75959d18d0
	public Boolean ShouldSerializeeffectCounterType() { }
	// RVA: 0x33b98e0 VA: 0x75959d18e0
	public Boolean ShouldSerializeeffectDecoIconId() { }
	// RVA: 0x33b9900 VA: 0x75959d1900
	public Void .ctor() { }
}
```