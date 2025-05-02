# FaceToTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ActionTargetType _source`

- `Boolean _force`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FaceToTarget : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ActionTargetType _source; // 0x14
	private Boolean _force; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f56598 VA: 0x759456e598
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f56600 VA: 0x759456e600
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f5677c VA: 0x759456e77c
	public Void .ctor() { }
}
```