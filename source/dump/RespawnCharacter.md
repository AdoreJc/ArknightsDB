# RespawnCharacter

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _ignoreAdvancedBuildableMask`

- `Boolean _canRespawnInPlace`

- `Boolean _forceRespawnInPlace`

- `String _rowKey`

- `String _colKey`

- `Boolean _recordRespawnToSharedData`

- `String _respawnBBKey`

- `String _respawnInPlaceBBKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RespawnCharacter : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _ignoreAdvancedBuildableMask; // 0x14
	private Boolean _canRespawnInPlace; // 0x15
	private Boolean _forceRespawnInPlace; // 0x16
	private String _rowKey; // 0x18
	private String _colKey; // 0x20
	private Boolean _recordRespawnToSharedData; // 0x28
	private String _respawnBBKey; // 0x30
	private String _respawnInPlaceBBKey; // 0x38
	private List`1 _respawnBlackboardKeys; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd679c VA: 0x75945ee79c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd6804 VA: 0x75945ee804
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd6ca4 VA: 0x75945eeca4
	public Void .ctor() { }
}
```