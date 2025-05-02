# CheckIdInBlackboardFunLiveModeOnly

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckIdInBlackboardFunLiveModeOnly : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f54148 VA: 0x759456c148
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f541b0 VA: 0x759456c1b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f543a8 VA: 0x759456c3a8
	public Void .ctor() { }
}
```