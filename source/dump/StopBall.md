# StopBall

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _ignoreUnstoppable`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StopBall : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _ignoreUnstoppable; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4fdc0 VA: 0x7594567dc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4fe28 VA: 0x7594567e28
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4ffa4 VA: 0x7594567fa4
	public Void .ctor() { }
}
```