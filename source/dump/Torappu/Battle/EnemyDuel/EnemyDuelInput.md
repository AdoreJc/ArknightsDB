# EnemyDuelInput

**Namespace:** `Torappu.Battle.EnemyDuel`


## Fields

- `Int32 randomSeed`

- `String subModeID`

- `String sceneId`

- `Boolean isRoomOwner`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.EnemyDuel
public class EnemyDuelInput : IHotfixable
{
	public Int32 randomSeed; // 0x10
	public String subModeID; // 0x18
	public String sceneId; // 0x20
	public List`1 players; // 0x28
	public Boolean isRoomOwner; // 0x30
	public List`1 npcIds; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1c62e04 VA: 0x759427ae04
	public Void .ctor() { }
}
```