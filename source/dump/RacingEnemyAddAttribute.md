# RacingEnemyAddAttribute

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isFinish`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingEnemyAddAttribute : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _isFinish; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7a554 VA: 0x7594592554
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7a5bc VA: 0x75945925bc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7a788 VA: 0x7594592788
	public Void .ctor() { }
}
```