# SpawnTokenOnTileByBlackboard

**Namespace:** ` `


## Fields

- `AdvancedCharacterInst _tokenToSpawn`

- `String _rangeId`

- `String _validTileBlackboard`

- `String _dirBlackboard`

- `Boolean _excludeTileInBlackboard`

- `Boolean _onlySpawnOnNoCharacterTile`


## Methods

- `Boolean _ValidateTile(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpawnTokenOnTileByBlackboard : ActionNode
{
	private AdvancedCharacterInst _tokenToSpawn; // 0x10
	private String _rangeId; // 0x18
	private String _validTileBlackboard; // 0x20
	private String _dirBlackboard; // 0x28
	private Boolean _excludeTileInBlackboard; // 0x30
	private Boolean _onlySpawnOnNoCharacterTile; // 0x31
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__ValidateTile; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcab14 VA: 0x75945e2b14
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcab7c VA: 0x75945e2b7c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcaf64 VA: 0x75945e2f64
	private Boolean _ValidateTile(Tile tile) { }
	// RVA: 0x1fcb078 VA: 0x75945e3078
	public Void .ctor() { }
}
```