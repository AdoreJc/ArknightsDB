# CheckTargetEnemyId

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetEnemyId : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isUnset; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f37ed0 VA: 0x759454fed0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f37f38 VA: 0x759454ff38
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f38138 VA: 0x7594550138
	public Void .ctor() { }
}
```