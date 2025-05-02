# NpcBattleInput

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `String npcId`

- `String trapId`

- `Direction dir`

- `Int32 reactSkillIndex`

- `GridPosition pos`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class NpcBattleInput : IHotfixable
{
	public String npcId; // 0x10
	public String trapId; // 0x18
	public Direction dir; // 0x20
	public Int32 reactSkillIndex; // 0x24
	public ListDict`2 dialogData; // 0x28
	public GridPosition pos; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1dfa7f8 VA: 0x75944127f8
	public Void .ctor() { }
}
```