# EnemyLrtsiaCheckDamageBlocked

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `String _abilityName`

- `Single _blockAngle`

- `String _angleKey`

- `Boolean _clockWise`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyLrtsiaCheckDamageBlocked : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private String _abilityName; // 0x18
	private Single _blockAngle; // 0x20
	private String _angleKey; // 0x28
	private Boolean _clockWise; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc33b8 VA: 0x75945db3b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc3420 VA: 0x75945db420
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc3ba4 VA: 0x75945dbba4
	public Void .ctor() { }
}
```