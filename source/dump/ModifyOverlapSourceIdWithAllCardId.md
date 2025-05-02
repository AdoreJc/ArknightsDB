# ModifyOverlapSourceIdWithAllCardId

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _exceptTokenAndTrap`

- `Boolean _isRemove`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyOverlapSourceIdWithAllCardId : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _exceptTokenAndTrap; // 0x14
	private Boolean _isRemove; // 0x15
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc5748 VA: 0x75945dd748
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc57b0 VA: 0x75945dd7b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc5a24 VA: 0x75945dda24
	public Void .ctor() { }
}
```