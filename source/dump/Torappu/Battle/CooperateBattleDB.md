# CooperateBattleDB

**Namespace:** `Torappu.Battle`


## Properties

- `Int32 costTransferCnt`

- `Int32 getMaxMsgCntInOneUpdate`

- `Int32 footballHardTypeFactor`


## Methods

- `Int32 get_costTransferCnt()`

- `Int32 get_getMaxMsgCntInOneUpdate()`

- `Int32 get_footballHardTypeFactor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateBattleDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_get_endTileInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_costTransferCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_getMaxMsgCntInOneUpdate; // 0x10
	private static DelegateBridge __Hotfix0_get_footballHardTypeFactor; // 0x18
	private static DelegateBridge __Hotfix0_get_footballAheadGoalCntFactor; // 0x20
	private static DelegateBridge __Hotfix0_get_footballLastRoundResultFactor; // 0x28
	private static DelegateBridge __Hotfix0_get_footballLevelOfWaveFactor; // 0x30
	private static DelegateBridge __Hotfix0_get_footballTeamWeights; // 0x38
	private static DelegateBridge __Hotfix0_get_footballTeamPlayers; // 0x40
	private static DelegateBridge __Hotfix0_get_footballPlayersName; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Dictionary`2 endTileInfo { get; }
	public Int32 costTransferCnt { get; }
	public Int32 getMaxMsgCntInOneUpdate { get; }
	public Int32 footballHardTypeFactor { get; }
	public List`1 footballAheadGoalCntFactor { get; }
	public Dictionary`2 footballLastRoundResultFactor { get; }
	public Dictionary`2 footballLevelOfWaveFactor { get; }
	public List`1 footballTeamWeights { get; }
	public Dictionary`2 footballTeamPlayers { get; }
	public Dictionary`2 footballPlayersName { get; }

	// RVA: 0x1c5577c VA: 0x759426d77c
	public Dictionary`2 get_endTileInfo() { }
	// RVA: 0x1c55808 VA: 0x759426d808
	public Int32 get_costTransferCnt() { }
	// RVA: 0x1c55894 VA: 0x759426d894
	public Int32 get_getMaxMsgCntInOneUpdate() { }
	// RVA: 0x1c55920 VA: 0x759426d920
	public Int32 get_footballHardTypeFactor() { }
	// RVA: 0x1c559ac VA: 0x759426d9ac
	public List`1 get_footballAheadGoalCntFactor() { }
	// RVA: 0x1c55a38 VA: 0x759426da38
	public Dictionary`2 get_footballLastRoundResultFactor() { }
	// RVA: 0x1c55ac4 VA: 0x759426dac4
	public Dictionary`2 get_footballLevelOfWaveFactor() { }
	// RVA: 0x1c55b50 VA: 0x759426db50
	public List`1 get_footballTeamWeights() { }
	// RVA: 0x1c55bdc VA: 0x759426dbdc
	public Dictionary`2 get_footballTeamPlayers() { }
	// RVA: 0x1c55c68 VA: 0x759426dc68
	public Dictionary`2 get_footballPlayersName() { }
	// RVA: 0x1c55cf4 VA: 0x759426dcf4
	public Void .ctor() { }
}
```