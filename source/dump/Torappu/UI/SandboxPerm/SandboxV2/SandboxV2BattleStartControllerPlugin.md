# SandboxV2BattleStartControllerPlugin

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Param m_param`


## Methods

- `Void OverrideInParams(ref, CommonStartBattleResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BattleStartControllerPlugin : IPlugin
{
	private Param m_param; // 0x10


	// RVA: 0x261db3c VA: 0x7594c35b3c
	public Void .ctor(Param param) { }
	// RVA: 0x261db6c VA: 0x7594c35b6c
	public Void OverrideInParams(ref InParams inParams, CommonStartBattleResponse response) { }
	// RVA: 0x2620de4 VA: 0x7594c38de4
	private static Void _ParseMonthlyNode(SandboxInput sandboxMeta, SandboxV2MonthRushData data) { }
	// RVA: 0x2621050 VA: 0x7594c39050
	private static Void _ParseNormalNode(Dungeon dungeon, SandboxInput sandboxMeta, PlayerSandboxV2 playerSandboxV2, SandboxV2Data gameData, String nodeId) { }
	// RVA: 0x2620d14 VA: 0x7594c38d14
	private static Void _ParseSelectionNode(SandboxInput sandboxMeta, PlayerSandboxV2 playerSandboxV2, SandboxV2Data gameData, SandboxV2BattleStartResponse response) { }
	// RVA: 0x2621c74 VA: 0x7594c39c74
	private static Void _ParseLureInsects(List`1 lureInsect, SandboxInput input, SandboxV2Data gameData) { }
	// RVA: 0x261eee0 VA: 0x7594c36ee0
	private static Void _ParseCollectItems(SandboxInput input, PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x26205f4 VA: 0x7594c385f4
	private static Void _ParseRiftData(SandboxInput input, PlayerSandboxV2 playerSandboxV2) { }
	// RVA: 0x2621080 VA: 0x7594c39080
	private static Void _ParseRushEnemies(Dungeon dungeon, SandboxInput input, PlayerSandboxV2 playerSandboxV2, SandboxV2Data gameData, String nodeId) { }
	// RVA: 0x2621880 VA: 0x7594c39880
	private static Void _ParseRareAnimals(Dungeon dungeon, SandboxInput input, String nodeId) { }
	// RVA: 0x261e31c VA: 0x7594c3631c
	private static Void _ParseLevelActions(SandboxInput input, NodeStage nodeStage) { }
	// RVA: 0x261e360 VA: 0x7594c36360
	private static Void _ParseEntityStatus(SandboxInput input, NodeStage nodeStage) { }
	// RVA: 0x261ed58 VA: 0x7594c36d58
	private static Void _ParsePlacedItems(SandboxInput input, NodeStage nodeStage) { }
	// RVA: 0x261f6fc VA: 0x7594c376fc
	private static Void _ParseNpc(SandboxInput input, List`1 npcs, SandboxV2Data data, Dictionary`2 favor) { }
	// RVA: 0x26206f0 VA: 0x7594c386f0
	private static Void _ParseIdInCompleteProgressCount(SandboxInput input, NodeStage nodeStage) { }
	// RVA: 0x26206c0 VA: 0x7594c386c0
	private static Void _ParseAvgToTrigger(SandboxInput input, String topicId) { }
}
```