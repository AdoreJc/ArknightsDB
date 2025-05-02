# SpawnTokenOnTargetTileWithCondition

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `AdvancedCharacterInst _tokenToSpawn`

- `Boolean _specifierSideType`

- `SideType _spawnedTokenSideType`

- `Boolean _checkBuildableType`

- `String _tileEffect`

- `Boolean _tileFromBlackboard`

- `Options _options`

- `String _tileBlackList`

- `String _tileBlackListKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpawnTokenOnTargetTileWithCondition : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private AdvancedCharacterInst _tokenToSpawn; // 0x18
	private Boolean _specifierSideType; // 0x20
	private SideType _spawnedTokenSideType; // 0x24
	private Boolean _checkBuildableType; // 0x28
	private String _tileEffect; // 0x30
	private Boolean _tileFromBlackboard; // 0x38
	private List`1 _buffs; // 0x40
	private Options _options; // 0x48
	private String _tileBlackList; // 0x80
	private String _tileBlackListKey; // 0x88
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fca53c VA: 0x75945e253c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fca5a4 VA: 0x75945e25a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcaa5c VA: 0x75945e2a5c
	public Void .ctor() { }
}
```