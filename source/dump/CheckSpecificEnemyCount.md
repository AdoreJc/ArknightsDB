# CheckSpecificEnemyCount

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _enemyId`

- `String _limitAmountKey`

- `Int32 _limitAmount`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckSpecificEnemyCount : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _enemyId; // 0x18
	private String _limitAmountKey; // 0x20
	private Int32 _limitAmount; // 0x28
	private CompareType _condType; // 0x2c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2a8ac VA: 0x75945428ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2a914 VA: 0x7594542914
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2aca4 VA: 0x7594542ca4
	public Void .ctor() { }
}
```