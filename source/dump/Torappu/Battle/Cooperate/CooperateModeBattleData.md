# CooperateModeBattleData

**Namespace:** `Torappu.Battle.Cooperate`


## Fields

- `Int32 costTransferred`

- `Int32 getMaxMsgCntInOneUpdate`

- `Int32 footballHardTypeFactor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Cooperate
public class CooperateModeBattleData : IHotfixable
{
	public Int32 costTransferred; // 0x10
	public Int32 getMaxMsgCntInOneUpdate; // 0x14
	public Dictionary`2 endTileInfo; // 0x18
	public List`1 footballAheadGoalCntFactor; // 0x20
	public Int32 footballHardTypeFactor; // 0x28
	public Dictionary`2 footballLastRoundResultFactor; // 0x30
	public Dictionary`2 footballLevelOfWaveFactor; // 0x38
	public List`1 footballTeamWeights; // 0x40
	public Dictionary`2 footballTeamPlayers; // 0x48
	public Dictionary`2 footballPlayersName; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1c64ff8 VA: 0x759427cff8
	public Void .ctor() { }
}
```