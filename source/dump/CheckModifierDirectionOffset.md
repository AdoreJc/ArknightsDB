# CheckModifierDirectionOffset

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _targetToSource`

- `Boolean _exceptThisOffset`

- `GridPosition _offset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckModifierDirectionOffset : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _targetToSource; // 0x18
	private Boolean _exceptThisOffset; // 0x19
	private GridPosition _offset; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f72f08 VA: 0x759458af08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f72f70 VA: 0x759458af70
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f731fc VA: 0x759458b1fc
	public Void .ctor() { }
}
```