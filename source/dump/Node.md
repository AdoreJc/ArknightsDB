# Node

**Namespace:** ` `


## Fields

- `String index`

- `RoguelikeNodePosition position`

- `RoguelikeEventType type`

- `ShopNode shop`

- `BattleNode battle`

- `SceneNode scenes`

- `Exchange exchange`

- `ModuleChange module`

- `Alchemy alchemy`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Node
{
	public String index; // 0x10
	public RoguelikeNodePosition position; // 0x18
	public RoguelikeEventType type; // 0x20
	public List`1 recruits; // 0x28
	public List`1 upgrades; // 0x30
	public List`1 got; // 0x38
	public ShopNode shop; // 0x40
	public BattleNode battle; // 0x48
	public SceneNode scenes; // 0x50
	public Exchange exchange; // 0x58
	public ModuleChange module; // 0x60
	public Alchemy alchemy; // 0x68


	// RVA: 0x2a8cd9c VA: 0x75950a4d9c
	public Void .ctor() { }
}
```