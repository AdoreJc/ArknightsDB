# SetAdditonalBuildCondition

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `BuildableType _buildableType`

- `AdvancedBuildableMask _advancedBuildableMask`

- `Boolean _additional`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetAdditonalBuildCondition : ActionNode
{
	private ActionTargetType _target; // 0x10
	private BuildableType _buildableType; // 0x14
	private AdvancedBuildableMask _advancedBuildableMask; // 0x18
	private Boolean _additional; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc5224 VA: 0x75945dd224
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc528c VA: 0x75945dd28c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc543c VA: 0x75945dd43c
	public Void .ctor() { }
}
```