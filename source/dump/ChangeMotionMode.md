# ChangeMotionMode

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _resetToDefault`

- `MotionMode _motionMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeMotionMode : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _resetToDefault; // 0x14
	private MotionMode _motionMode; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f970c4 VA: 0x75945af0c4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9712c VA: 0x75945af12c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f972b8 VA: 0x75945af2b8
	public Void .ctor() { }
}
```