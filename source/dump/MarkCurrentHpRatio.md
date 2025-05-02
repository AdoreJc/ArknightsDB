# MarkCurrentHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _markInBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MarkCurrentHpRatio : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _markInBlackboard; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9a830 VA: 0x75945b2830
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9a898 VA: 0x75945b2898
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9aa50 VA: 0x75945b2a50
	public Void .ctor() { }
}
```