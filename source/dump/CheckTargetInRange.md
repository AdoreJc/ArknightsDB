# CheckTargetInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `ActionTargetType _soureceType`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetInRange : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private ActionTargetType _soureceType; // 0x14
	private String _rangeId; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1b4e8 VA: 0x75945334e8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1b550 VA: 0x7594533550
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1b734 VA: 0x7594533734
	public Void .ctor() { }
}
```