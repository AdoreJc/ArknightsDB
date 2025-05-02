# IsRallyPoint

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _checkIsInRallyPointMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IsRallyPoint : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _checkIsInRallyPointMode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f29ab0 VA: 0x7594541ab0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f29b18 VA: 0x7594541b18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f29ca0 VA: 0x7594541ca0
	public Void .ctor() { }
}
```