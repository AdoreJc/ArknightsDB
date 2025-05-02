# CheckBuildableTypeOfCharacterRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `BuildableType _buildableType`

- `Boolean _filterAllUnit`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBuildableTypeOfCharacterRootTile : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private BuildableType _buildableType; // 0x14
	private Boolean _filterAllUnit; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f27064 VA: 0x759453f064
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f270cc VA: 0x759453f0cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f27268 VA: 0x759453f268
	public Void .ctor() { }
}
```