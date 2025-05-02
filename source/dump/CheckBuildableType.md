# CheckBuildableType

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `BuildableType _buildableType`

- `Boolean _checkOriginCondition`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBuildableType : ActionNode
{
	private ActionTargetType _target; // 0x10
	private BuildableType _buildableType; // 0x14
	private Boolean _checkOriginCondition; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1df34 VA: 0x7594535f34
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1df9c VA: 0x7594535f9c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1e140 VA: 0x7594536140
	public Void .ctor() { }
}
```