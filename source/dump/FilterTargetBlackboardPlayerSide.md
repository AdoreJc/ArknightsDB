# FilterTargetBlackboardPlayerSide

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterTargetBlackboardPlayerSide : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f74e88 VA: 0x759458ce88
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f74ef0 VA: 0x759458cef0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f750dc VA: 0x759458d0dc
	public Void .ctor() { }
}
```