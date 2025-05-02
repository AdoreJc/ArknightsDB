# ClearFirstBuffBlackboardByKey

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _buffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearFirstBuffBlackboardByKey : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _buffKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f013a4 VA: 0x75945193a4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0140c VA: 0x759451940c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f015d0 VA: 0x75945195d0
	public Void .ctor() { }
}
```