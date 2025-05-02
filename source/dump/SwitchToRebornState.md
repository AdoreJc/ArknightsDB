# SwitchToRebornState

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isForce`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchToRebornState : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isForce; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8fad8 VA: 0x75945a7ad8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8fb40 VA: 0x75945a7b40
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8fdf8 VA: 0x75945a7df8
	public Void .ctor() { }
}
```