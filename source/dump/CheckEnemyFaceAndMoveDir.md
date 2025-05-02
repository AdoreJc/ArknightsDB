# CheckEnemyFaceAndMoveDir

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CheckType _checkType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyFaceAndMoveDir : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CheckType _checkType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2e380 VA: 0x7594546380
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2e3e8 VA: 0x75945463e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2e620 VA: 0x7594546620
	public Void .ctor() { }
}
```