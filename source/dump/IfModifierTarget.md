# IfModifierTarget

**Namespace:** ` `


## Fields

- `MotionMask _motionMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfModifierTarget : ActionNode
{
	private MotionMask _motionMask; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f727f0 VA: 0x759458a7f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f72858 VA: 0x759458a858
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f729c8 VA: 0x759458a9c8
	public Void .ctor() { }
}
```