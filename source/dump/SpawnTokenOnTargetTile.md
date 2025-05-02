# SpawnTokenOnTargetTile

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `Boolean _ignoreSourceType`

- `Boolean _ignoreTargetType`

- `Boolean _spawnTokenFromCards`

- `Boolean _refreshTokenCardCooldown`

- `Boolean _useTokenKeyDirectly`

- `String _spawnTokenKey`

- `Boolean _respawnSameToken`

- `AdvancedCharacterInst _tokenToSpawn`

- `Boolean _specifierSideType`

- `SideType _spawnedTokenSideType`

- `Boolean _specifierPlayerSideType`

- `PlayerSide _playerSide`

- `Boolean _checkBuildableType`

- `String _tileEffect`

- `Boolean _createEffectOnTokenTile`

- `Boolean _tileFromBlackboard`

- `Boolean _tileFromSnapshot`

- `Boolean _loadTileFromCharacterSharedData`

- `String _locatedColBBKey`

- `String _locatedRowBBKey`

- `Boolean _ignoreAdvancedBuildableMask`


## Properties

- `Boolean spawnTokenFromCards`

- `Boolean notSpawnTokenFromCards`

- `Boolean hasTileEffect`


## Methods

- `Boolean get_spawnTokenFromCards()`

- `Boolean get_notSpawnTokenFromCards()`

- `Boolean get_hasTileEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpawnTokenOnTargetTile : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _ignoreSourceType; // 0x18
	private Boolean _ignoreTargetType; // 0x19
	private Boolean _spawnTokenFromCards; // 0x1a
	private Boolean _refreshTokenCardCooldown; // 0x1b
	private Boolean _useTokenKeyDirectly; // 0x1c
	private String _spawnTokenKey; // 0x20
	private Boolean _respawnSameToken; // 0x28
	private AdvancedCharacterInst _tokenToSpawn; // 0x30
	private Boolean _specifierSideType; // 0x38
	private SideType _spawnedTokenSideType; // 0x3c
	private Boolean _specifierPlayerSideType; // 0x40
	private PlayerSide _playerSide; // 0x44
	private Boolean _checkBuildableType; // 0x48
	private String _tileEffect; // 0x50
	private Boolean _createEffectOnTokenTile; // 0x58
	private Boolean _tileFromBlackboard; // 0x59
	private Boolean _tileFromSnapshot; // 0x5a
	private Boolean _loadTileFromCharacterSharedData; // 0x5b
	private String _locatedColBBKey; // 0x60
	private String _locatedRowBBKey; // 0x68
	private Boolean _ignoreAdvancedBuildableMask; // 0x70
	private List`1 _buffs; // 0x78
	private static DelegateBridge __Hotfix0_get_spawnTokenFromCards; // 0x0
	private static DelegateBridge __Hotfix0_get_notSpawnTokenFromCards; // 0x8
	private static DelegateBridge __Hotfix0_get_hasTileEffect; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x18
	private static DelegateBridge __Hotfix0_Execute; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean spawnTokenFromCards { get; }
	public Boolean notSpawnTokenFromCards { get; }
	public Boolean hasTileEffect { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fc9aa4 VA: 0x75945e1aa4
	public Boolean get_spawnTokenFromCards() { }
	// RVA: 0x1fc9b0c VA: 0x75945e1b0c
	public Boolean get_notSpawnTokenFromCards() { }
	// RVA: 0x1fc9b7c VA: 0x75945e1b7c
	public Boolean get_hasTileEffect() { }
	// RVA: 0x1fc9bf4 VA: 0x75945e1bf4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc9c5c VA: 0x75945e1c5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fca434 VA: 0x75945e2434
	public Void .ctor() { }
}
```