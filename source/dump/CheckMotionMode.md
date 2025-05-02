# CheckMotionMode

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `MotionMode _mode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckMotionMode : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private MotionMode _mode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2c188 VA: 0x7594544188
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2c1f0 VA: 0x75945441f0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2c324 VA: 0x7594544324
	public Void .ctor() { }
}
```