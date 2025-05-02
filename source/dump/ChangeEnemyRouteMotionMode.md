# ChangeEnemyRouteMotionMode

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `MotionMode _motionMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeEnemyRouteMotionMode : ActionNode
{
	private ActionTargetType _target; // 0x10
	private MotionMode _motionMode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f975c0 VA: 0x75945af5c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f97628 VA: 0x75945af628
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f977d4 VA: 0x75945af7d4
	public Void .ctor() { }
}
```