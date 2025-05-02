# SandboxIsPlacedItem

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxIsPlacedItem : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f869f4 VA: 0x759459e9f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f86a5c VA: 0x759459ea5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f86bd0 VA: 0x759459ebd0
	public Void .ctor() { }
}
```