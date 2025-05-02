# SandboxOutput

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `String exploredMap`

- `Int32 usedLure`

- `NpcOutput npcOutput`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxOutput : IHotfixable
{
	public String exploredMap; // 0x10
	public List`1 killedEnemies; // 0x18
	public List`1 huntedUniEnemies; // 0x20
	public Dictionary`2 rushEnemies; // 0x28
	public Dictionary`2 catchedAnimals; // 0x30
	public Dictionary`2 caughtRacers; // 0x38
	public Int32 usedLure; // 0x40
	public List`1 entityStatus; // 0x48
	public Dictionary`2 bossStatus; // 0x50
	public List`1 placedItems; // 0x58
	public Dictionary`2 constructItems; // 0x60
	public Dictionary`2 entityDroppedThisLevel; // 0x68
	public Dictionary`2 enemyDeathDetail; // 0x70
	public Dictionary`2 uniEnemyDeathDetail; // 0x78
	public readonly Dictionary`2 enemyEvents; // 0x80
	public List`1 messengerReachExitUids; // 0x88
	public NpcOutput npcOutput; // 0x90
	public Dictionary`2 uniEnemyStatus; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1dfa8d8 VA: 0x75944128d8
	public Void .ctor() { }
}
```