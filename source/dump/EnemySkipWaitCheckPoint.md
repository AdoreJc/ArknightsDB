# EnemySkipWaitCheckPoint

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _useSkipInsteadOfSetToZero`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemySkipWaitCheckPoint : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _useSkipInsteadOfSetToZero; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc1c4c VA: 0x75945d9c4c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc1cb4 VA: 0x75945d9cb4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc1e70 VA: 0x75945d9e70
	public Void .ctor() { }
}
```