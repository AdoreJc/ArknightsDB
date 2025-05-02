# ApplyForceOnRogue4DLC2BounceEnemy

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`

- `Boolean _applyForceDirectly`

- `String _directionKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyForceOnRogue4DLC2BounceEnemy : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private Boolean _applyForceDirectly; // 0x18
	private String _directionKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f76708 VA: 0x759458e708
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f76770 VA: 0x759458e770
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f76b60 VA: 0x759458eb60
	public Void .ctor() { }
}
```