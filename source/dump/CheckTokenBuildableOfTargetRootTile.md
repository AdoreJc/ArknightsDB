# CheckTokenBuildableOfTargetRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _tokenOwnerType`

- `ActionTargetType _targetType`

- `Boolean _freely`

- `Boolean _ignoreAdvancedBuildableMask`

- `Boolean _spawnManually`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTokenBuildableOfTargetRootTile : ActionNode
{
	private ActionTargetType _tokenOwnerType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private Boolean _freely; // 0x18
	private Boolean _ignoreAdvancedBuildableMask; // 0x19
	private Boolean _spawnManually; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f272e4 VA: 0x759453f2e4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2734c VA: 0x759453f34c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f275c8 VA: 0x759453f5c8
	public Void .ctor() { }
}
```