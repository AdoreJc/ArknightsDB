# SandboxCheckSpecialUniEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCheckSpecialUniEnemy : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8a414 VA: 0x75945a2414
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8a47c VA: 0x75945a247c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8a6a4 VA: 0x75945a26a4
	public Void .ctor() { }
}
```