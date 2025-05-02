# CheckEnemyLevelType

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `EnemyLevelType _targetLevelType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyLevelType : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private EnemyLevelType _targetLevelType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1a25c VA: 0x759453225c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1a2c4 VA: 0x75945322c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1a444 VA: 0x7594532444
	public Void .ctor() { }
}
```