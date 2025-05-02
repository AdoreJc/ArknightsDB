# CheckBlockEnemysLevelType

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `EnemyLevelType _targetLevelType`

- `Boolean isAND`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBlockEnemysLevelType : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private EnemyLevelType _targetLevelType; // 0x14
	private Boolean isAND; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1a4b4 VA: 0x75945324b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1a51c VA: 0x759453251c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1ac3c VA: 0x7594532c3c
	public Void .ctor() { }
}
```