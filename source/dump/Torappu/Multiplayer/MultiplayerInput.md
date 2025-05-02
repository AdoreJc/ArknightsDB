# MultiplayerInput

**Namespace:** `Torappu.Multiplayer`


## Fields

- `Int32 randomSeed`

- `String levelId`

- `MultiplayerSquadData myPlayerSquadData`

- `MultiplayerSquadData anotherPlayerSquadData`

- `BattlePlayerData anotherPlayerData`

- `SubGameModeType gameModeType`

- `Boolean isMatch`

- `Boolean isInversed`

- `ProfessionCategory myBuff`

- `ProfessionCategory mateBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MultiplayerInput : IHotfixable
{
	public Int32 randomSeed; // 0x10
	public String levelId; // 0x18
	public MultiplayerSquadData myPlayerSquadData; // 0x20
	public MultiplayerSquadData anotherPlayerSquadData; // 0x28
	public BattlePlayerData anotherPlayerData; // 0x30
	public SubGameModeType gameModeType; // 0x38
	public List`1 playerInfos; // 0x40
	public Boolean isMatch; // 0x48
	public Boolean isInversed; // 0x49
	public ProfessionCategory myBuff; // 0x4c
	public ProfessionCategory mateBuff; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x3588aec VA: 0x7595ba0aec
	public Void .ctor() { }
}
```