# ModifyOverlapSourceId

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _sourceId`

- `Boolean _isRemove`

- `Boolean _useBlackboardId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyOverlapSourceId : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _sourceId; // 0x18
	private Boolean _isRemove; // 0x20
	private Boolean _useBlackboardId; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc54ac VA: 0x75945dd4ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc5514 VA: 0x75945dd514
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc56d8 VA: 0x75945dd6d8
	public Void .ctor() { }
}
```