# CheckEnemyCountWhenAttackDoCast

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `CompareType _condType`

- `String _countKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyCountWhenAttackDoCast : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private CompareType _condType; // 0x14
	private String _countKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f33eb4 VA: 0x759454beb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f33f1c VA: 0x759454bf1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f341ec VA: 0x759454c1ec
	public Void .ctor() { }
}
```