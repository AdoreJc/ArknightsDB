# RoguelikeDungeonNode

**Namespace:** `Torappu`


## Fields

- `Int32 depth`

- `Int32 index`

- `RoguelikeEventType type`

- `Int64 fts`

- `Boolean canReach`

- `Boolean isNextStep`

- `Boolean isNextLocked`

- `RoguelikeShop shop`

- `BattleContent battle`

- `String stageId`

- `String topicId`

- `Boolean isDiscard`

- `Boolean isFutureNode`

- `Boolean isInTrace`

- `Boolean isCurrent`

- `Boolean isInSpecialZone`

- `PlayerNodeDetailContent detailContent`

- `PlayerNodeForesightType foresightType`

- `PlayerNodeRollInfo rollInfo`

- `String instId`


## Properties

- `Boolean isPassed`


## Methods

- `Boolean get_isPassed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeDungeonNode
{
	public Int32 depth; // 0x10
	public Int32 index; // 0x14
	public RoguelikeEventType type; // 0x18
	public Int64 fts; // 0x20
	public Boolean canReach; // 0x28
	public Boolean isNextStep; // 0x29
	public Boolean isNextLocked; // 0x2a
	public List`1 parents; // 0x30
	public List`1 children; // 0x38
	public List`1 brother; // 0x40
	public List`1 attach; // 0x48
	public RoguelikeShop shop; // 0x50
	public List`1 scenes; // 0x58
	public BattleContent battle; // 0x60
	public String stageId; // 0x68
	public String topicId; // 0x70
	public Boolean isDiscard; // 0x78
	public Boolean isFutureNode; // 0x79
	public Boolean isInTrace; // 0x7a
	public Boolean isCurrent; // 0x7b
	public Boolean isInSpecialZone; // 0x7c
	public PlayerNodeDetailContent detailContent; // 0x80
	public PlayerNodeForesightType foresightType; // 0x88
	public PlayerNodeRollInfo rollInfo; // 0x90
	public String instId; // 0x98

	public Boolean isPassed { get; }

	// RVA: 0x34a7ef0 VA: 0x7595abfef0
	public Boolean get_isPassed() { }
	// RVA: 0x34a7f10 VA: 0x7595abff10
	public override String ToString() { }
	// RVA: 0x34a7fb0 VA: 0x7595abffb0
	public Void .ctor() { }
}
```