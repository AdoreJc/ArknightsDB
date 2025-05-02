# IfTargetEqual

**Namespace:** ` `


## Fields

- `ActionTargetType _target1`

- `ActionTargetType _target2`

- `Boolean _equalIfBothNull`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IfTargetEqual : ActionNode
{
	private ActionTargetType _target1; // 0x10
	private ActionTargetType _target2; // 0x14
	private Boolean _equalIfBothNull; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2a65c VA: 0x759454265c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2a6c4 VA: 0x75945426c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2a83c VA: 0x759454283c
	public Void .ctor() { }
}
```