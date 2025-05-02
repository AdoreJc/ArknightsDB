# SpawnTokenOnTileByIDAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _tokenId`

- `Boolean _addBuffsIfOverlay`

- `Boolean _addBuffsToSpawnedToken`

- `Boolean _refreshTokenCardCooldown`

- `Boolean _useOwnerHost`

- `Boolean _useOwnerDirection`

- `Boolean _checkTokenMaxDeployCnt`

- `Boolean _forceSpawn`


## Properties

- `Boolean addBuffsIfOverlay`


## Methods

- `Boolean get_addBuffsIfOverlay()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class SpawnTokenOnTileByIDAbility : AbstractSpawnTokenOnTileAbility
{
	private String _tokenId; // 0x208
	private Boolean _addBuffsIfOverlay; // 0x210
	private BuffData[] _buffsToExistToken; // 0x218
	private Boolean _addBuffsToSpawnedToken; // 0x220
	private BuffData[] _buffsToToken; // 0x228
	private Boolean _refreshTokenCardCooldown; // 0x230
	private Boolean _useOwnerHost; // 0x231
	private Boolean _useOwnerDirection; // 0x232
	private Boolean _checkTokenMaxDeployCnt; // 0x233
	private Boolean _forceSpawn; // 0x234
	private static DelegateBridge __Hotfix0_get_addBuffsIfOverlay; // 0x0
	private static DelegateBridge __Hotfix0_DoSpawnOnTile; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean addBuffsIfOverlay { get; }

	// RVA: 0x1e2a080 VA: 0x7594442080
	private Boolean get_addBuffsIfOverlay() { }
	// RVA: 0x1e2a0e8 VA: 0x75944420e8
	protected override Void DoSpawnOnTile(Tile tile) { }
	// RVA: 0x1e2a514 VA: 0x7594442514
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e2a5f8 VA: 0x75944425f8
	public Void .ctor() { }
	// RVA: 0x1e2a6bc VA: 0x75944426bc
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```