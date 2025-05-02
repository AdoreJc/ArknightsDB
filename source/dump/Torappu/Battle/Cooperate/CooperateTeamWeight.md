# CooperateTeamWeight

**Namespace:** `Torappu.Battle.Cooperate`


## Fields

- `String teamName`

- `Int32 weight`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Cooperate
public class CooperateTeamWeight : IHotfixable, IItemWithWeight
{
	public String teamName; // 0x10
	public Int32 weight; // 0x18
	private static DelegateBridge __Hotfix0_get_weightValue; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Single weightValue { get; }

	// RVA: 0x1c65d58 VA: 0x759427dd58
	public Single get_weightValue() { }
	// RVA: 0x1c65dc4 VA: 0x759427ddc4
	public Void .ctor() { }
}
```