# PlayerRoguelikeNode

**Namespace:** `Torappu`


## Fields

- `RoguelikeNodePosition pos`

- `RoguelikeEventType type`

- `Int64 fts`

- `PlayerNodeDetailContent realContent`

- `RoguelikeShop shop`

- `String stage`

- `PlayerNodeForesightType visibility`

- `PlayerNodeRollInfo refresh`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerRoguelikeNode
{
	public RoguelikeNodePosition pos; // 0x10
	public List`1 next; // 0x18
	public RoguelikeEventType type; // 0x20
	public Int64 fts; // 0x28
	public PlayerNodeDetailContent realContent; // 0x30
	public List`1 attach; // 0x38
	public RoguelikeShop shop; // 0x40
	public List`1 scenes; // 0x48
	public String stage; // 0x50
	public PlayerNodeForesightType visibility; // 0x58
	public PlayerNodeRollInfo refresh; // 0x60


	// RVA: 0x32d87fc VA: 0x75958f07fc
	public Void .ctor() { }
}
```