# CreatePreviewCursor

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _targetAsStart`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreatePreviewCursor : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _targetAsStart; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fdb170 VA: 0x75945f3170
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fdb1d8 VA: 0x75945f31d8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fdb4e0 VA: 0x75945f34e0
	public Void .ctor() { }
}
```