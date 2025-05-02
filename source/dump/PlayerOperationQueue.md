# PlayerOperationQueue

**Namespace:** ` `


## Fields

- `Boolean m_shouldQueueOps`

- `BattleController m_controller`


## Properties

- `Boolean shouldQueueOps`


## Methods

- `Boolean get_shouldQueueOps()`

- `Void set_shouldQueueOps(Boolean)`

- `Void Clear()`

- `Boolean AppendSpawn(UInt32, Direction, Tile, PlayerSide)`

- `Boolean AppendWithdraw(Character, PlayerSide)`

- `Boolean AppendTrigSkill(Character, PlayerSide)`

- `Void Drain()`

- `Boolean _DoExecuteOperation(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerOperationQueue
{
	private Boolean m_shouldQueueOps; // 0x10
	private BattleController m_controller; // 0x18
	private Queue`1 m_queue; // 0x20

	public Boolean shouldQueueOps { get; set; }

	// RVA: 0x3f6c3e4 VA: 0x75965843e4
	public Boolean get_shouldQueueOps() { }
	// RVA: 0x3f6c3ec VA: 0x75965843ec
	public Void set_shouldQueueOps(Boolean value) { }
	// RVA: 0x3f6c3f8 VA: 0x75965843f8
	public Void .ctor(BattleController controller, Boolean shouldQueueOps) { }
	// RVA: 0x3f6c4ac VA: 0x75965844ac
	public Void Clear() { }
	// RVA: 0x3f6c4fc VA: 0x75965844fc
	public Boolean AppendSpawn(UInt32 uniqueId, Direction direction, Tile tile, PlayerSide side) { }
	// RVA: 0x3f6c818 VA: 0x7596584818
	public Boolean AppendWithdraw(Character target, PlayerSide side) { }
	// RVA: 0x3f6c980 VA: 0x7596584980
	public Boolean AppendTrigSkill(Character target, PlayerSide side) { }
	// RVA: 0x3f6ca80 VA: 0x7596584a80
	public Void Drain() { }
	// RVA: 0x3f6c690 VA: 0x7596584690
	private Boolean _DoExecuteOperation(ref OperationEntry entry) { }
}
```