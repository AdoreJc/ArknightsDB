# ReleaseFromBlocker

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReleaseFromBlocker : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9ad08 VA: 0x75945b2d08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9ad70 VA: 0x75945b2d70
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9aee0 VA: 0x75945b2ee0
	public Void .ctor() { }
}
```