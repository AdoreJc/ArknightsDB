# RoguelikeInput

**Namespace:** `Torappu.Battle.Roguelike`


## Fields

- `Int32 hp`

- `Int32 maxHp`

- `Int32 shield`

- `BattleRoguelikeMeta meta`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike
public class RoguelikeInput : IHotfixable
{
	public List`1 outerBuffs; // 0x10
	public List`1 relicBuffs; // 0x18
	public Int32 hp; // 0x20
	public Int32 maxHp; // 0x24
	public Int32 shield; // 0x28
	public BattleRoguelikeMeta meta; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1d43954 VA: 0x759435b954
	public Void .ctor() { }
}
```