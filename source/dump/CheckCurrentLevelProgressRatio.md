# CheckCurrentLevelProgressRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _levelProgressKey`

- `CompareType _condType`

- `FP _levelProgressRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCurrentLevelProgressRatio : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _levelProgressKey; // 0x18
	private CompareType _condType; // 0x20
	private FP _levelProgressRatio; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f289b0 VA: 0x75945409b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f28a18 VA: 0x7594540a18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f28c94 VA: 0x7594540c94
	public Void .ctor() { }
}
```