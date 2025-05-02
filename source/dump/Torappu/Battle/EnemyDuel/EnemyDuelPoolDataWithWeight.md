# EnemyDuelPoolDataWithWeight

**Namespace:** `Torappu.Battle.EnemyDuel`


## Fields

- `String enemyId`

- `Single <weightValue>k__BackingField`


## Properties

- `Single weightValue`


## Methods

- `Single get_weightValue()`

- `Void set_weightValue(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.EnemyDuel
public class EnemyDuelPoolDataWithWeight : IItemWithWeight, IHotfixable
{
	public String enemyId; // 0x10
	private Single <weightValue>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_weightValue; // 0x0
	private static DelegateBridge __Hotfix0_set_weightValue; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Single weightValue { get; set; }

	// RVA: 0x1c62fec VA: 0x759427afec
	public Single get_weightValue() { }
	// RVA: 0x1c63054 VA: 0x759427b054
	public Void set_weightValue(Single value) { }
	// RVA: 0x1c630d0 VA: 0x759427b0d0
	public Void .ctor() { }
}
```