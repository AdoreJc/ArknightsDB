# CheckEnemyLevelMask

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `EnemyLevelMask _targetLevelMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyLevelMask : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private EnemyLevelMask _targetLevelMask; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1acb4 VA: 0x7594532cb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1ad1c VA: 0x7594532d1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1aea4 VA: 0x7594532ea4
	public Void .ctor() { }
}
```