# ChangeCharBlockMode

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _resetToDefault`

- `MotionMode _blockMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChangeCharBlockMode : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _resetToDefault; // 0x14
	private MotionMode _blockMode; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f97328 VA: 0x75945af328
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f97390 VA: 0x75945af390
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f97550 VA: 0x75945af550
	public Void .ctor() { }
}
```