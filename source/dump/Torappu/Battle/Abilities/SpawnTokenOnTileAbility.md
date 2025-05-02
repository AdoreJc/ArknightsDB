# SpawnTokenOnTileAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _spawnSelf`

- `AdvancedCharacterInst _tokenToSpawn`

- `Boolean _checkBuildableType`

- `Boolean _addBuffsToSpawnedToken`

- `Boolean _specifySide`

- `SideType _sideType`

- `BattleCharacterData m_tokenData`


## Properties

- `Boolean spawnSelf`


## Methods

- `Boolean get_spawnSelf()`

- `Void _ConvertToBattleCharacterData()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SpawnTokenOnTileAbility : AbstractSpawnTokenOnTileAbility
{
	private Boolean _spawnSelf; // 0x208
	private AdvancedCharacterInst _tokenToSpawn; // 0x210
	private Boolean _checkBuildableType; // 0x218
	private Boolean _addBuffsToSpawnedToken; // 0x219
	private BuffData[] _buffsToToken; // 0x220
	private Boolean _specifySide; // 0x228
	private SideType _sideType; // 0x22c
	private List`1 _tileBlackList; // 0x230
	private BattleCharacterData m_tokenData; // 0x238
	private static DelegateBridge __Hotfix0_get_spawnSelf; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_DoSpawnOnTile; // 0x10
	private static DelegateBridge __Hotfix0__ConvertToBattleCharacterData; // 0x18
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean spawnSelf { get; }

	// RVA: 0x1e298cc VA: 0x75944418cc
	public Boolean get_spawnSelf() { }
	// RVA: 0x1e29934 VA: 0x7594441934
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e29bf8 VA: 0x7594441bf8
	protected override Void DoSpawnOnTile(Tile tile) { }
	// RVA: 0x1e299f0 VA: 0x75944419f0
	private Void _ConvertToBattleCharacterData() { }
	// RVA: 0x1e29e50 VA: 0x7594441e50
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e29f18 VA: 0x7594441f18
	public Void .ctor() { }
	// RVA: 0x1e2a050 VA: 0x7594442050
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2a078 VA: 0x7594442078
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```