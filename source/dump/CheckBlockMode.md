# CheckBlockMode

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `MotionMode _blockMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBlockMode : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private MotionMode _blockMode; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2c3a0 VA: 0x75945443a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2c408 VA: 0x7594544408
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2c580 VA: 0x7594544580
	public Void .ctor() { }
}
```