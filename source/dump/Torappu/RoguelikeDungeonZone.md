# RoguelikeDungeonZone

**Namespace:** `Torappu`


## Fields

- `String zoneId`

- `Int32 zoneIndex`


## Methods

- `RoguelikeDungeonLayer GetLayer(Int32)`

- `RoguelikeDungeonNode GetNode(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeDungeonZone
{
	public String zoneId; // 0x10
	public Int32 zoneIndex; // 0x18
	public List`1 layers; // 0x20
	public List`1 variations; // 0x28


	// RVA: 0x34a81dc VA: 0x7595ac01dc
	public RoguelikeDungeonLayer GetLayer(Int32 depth) { }
	// RVA: 0x34a8278 VA: 0x7595ac0278
	public RoguelikeDungeonNode GetNode(Int32 depth, Int32 index) { }
	// RVA: 0x34a832c VA: 0x7595ac032c
	public Void .ctor() { }
}
```