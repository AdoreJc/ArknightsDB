# Act1ArcadeSquadPlugin

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeSquadPluginData m_pluginData`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `Void InitPluginData(DataBundle)`

- `Void SaveSquadCache(List`1)`

- `IStartBattleServiceConfig GetStartBattleServiceConfig(SquadModel, SquadFriendData)`

- `IFinishBattleServiceConfig GetFinishBattleServiceConfig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSquadPlugin : ICommonSquadPlugin
{
	public const String KEY_ACT_ID; // 0x0
	public const String KEY_STAGE_ID; // 0x0
	public const String KEY_ZONE_ID; // 0x0
	private Data`1 m_memData; // 0x10
	private Act1ArcadeSquadPluginData m_pluginData; // 0x18


	// RVA: 0x340b304 VA: 0x7595a23304
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x340b3cc VA: 0x7595a233cc
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x340b4e8 VA: 0x7595a234e8
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x340b550 VA: 0x7595a23550
	private Void _SaveData(ActData data) { }
	// RVA: 0x340b5b0 VA: 0x7595a235b0
	public Void InitPluginData(DataBundle pluginDataBundle) { }
	// RVA: 0x340b720 VA: 0x7595a23720
	public List`1 LoadSquadCache() { }
	// RVA: 0x340b7d0 VA: 0x7595a237d0
	public Void SaveSquadCache(List`1 slotList) { }
	// RVA: 0x340b8f0 VA: 0x7595a238f0
	public IStartBattleServiceConfig GetStartBattleServiceConfig(SquadModel squadModel, SquadFriendData assistFriend) { }
	// RVA: 0x340b984 VA: 0x7595a23984
	public IFinishBattleServiceConfig GetFinishBattleServiceConfig() { }
	// RVA: 0x340ba14 VA: 0x7595a23a14
	public Void .ctor() { }
}
```