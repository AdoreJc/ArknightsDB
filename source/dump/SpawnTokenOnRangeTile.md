# SpawnTokenOnRangeTile

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `AdvancedCharacterInst _tokenToSpawn`

- `Boolean _checkBuildableType`

- `String _tileEffect`

- `Boolean _tileHoldEffect`

- `String _rangeId`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpawnTokenOnRangeTile : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private AdvancedCharacterInst _tokenToSpawn; // 0x18
	private Boolean _checkBuildableType; // 0x20
	private String _tileEffect; // 0x28
	private Boolean _tileHoldEffect; // 0x30
	private String _rangeId; // 0x38
	private Boolean _force; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcb160 VA: 0x75945e3160
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcb1c8 VA: 0x75945e31c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcb5fc VA: 0x75945e35fc
	public Void .ctor() { }
}
```