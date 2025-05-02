# CooperateWaveWeight

**Namespace:** `Torappu.Battle.Cooperate`


## Fields

- `Int32 wave`

- `Int32 weight`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Cooperate
public class CooperateWaveWeight : IHotfixable, IItemWithWeight
{
	public Int32 wave; // 0x10
	public Int32 weight; // 0x14
	private static DelegateBridge __Hotfix0_get_weightValue; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Single weightValue { get; }

	// RVA: 0x1c65e34 VA: 0x759427de34
	public Single get_weightValue() { }
	// RVA: 0x1c65ea0 VA: 0x759427dea0
	public Void .ctor() { }
}
```