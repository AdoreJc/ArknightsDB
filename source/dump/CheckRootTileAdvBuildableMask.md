# CheckRootTileAdvBuildableMask

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `AdvancedBuildableMask _buildableMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckRootTileAdvBuildableMask : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private AdvancedBuildableMask _buildableMask; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f26200 VA: 0x759453e200
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f26268 VA: 0x759453e268
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f26404 VA: 0x759453e404
	public Void .ctor() { }
}
```