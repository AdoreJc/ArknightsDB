# RacingEnemyFilterByMoveSpeed

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _compareType`

- `Boolean _isRealSpeed`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingEnemyFilterByMoveSpeed : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _compareType; // 0x14
	private Boolean _isRealSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7ad94 VA: 0x7594592d94
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7adfc VA: 0x7594592dfc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7b05c VA: 0x759459305c
	public Void .ctor() { }
}
```