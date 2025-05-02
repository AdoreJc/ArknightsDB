# TryResetCharacterFaceIdleDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TryResetCharacterFaceIdleDirection : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f56350 VA: 0x759456e350
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f563b8 VA: 0x759456e3b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f56528 VA: 0x759456e528
	public Void .ctor() { }
}
```