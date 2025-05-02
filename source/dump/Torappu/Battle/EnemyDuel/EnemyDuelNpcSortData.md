# EnemyDuelNpcSortData

**Namespace:** `Torappu.Battle.EnemyDuel`


## Fields

- `String npcId`

- `Single priority`

- `ActivityEnemyDuelNpcData data`

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
public class EnemyDuelNpcSortData : IItemWithWeight
{
	public String npcId; // 0x10
	public Single priority; // 0x18
	public ActivityEnemyDuelNpcData data; // 0x20
	private Single <weightValue>k__BackingField; // 0x28

	public Single weightValue { get; set; }

	// RVA: 0x1c642e0 VA: 0x759427c2e0
	public Single get_weightValue() { }
	// RVA: 0x1c642e8 VA: 0x759427c2e8
	public Void set_weightValue(Single value) { }
	// RVA: 0x1c642f0 VA: 0x759427c2f0
	public Void .ctor() { }
}
```