# CheckBlocked

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _checkBlockedBySource`

- `Boolean _checkBlockedBySourceToken`

- `ActionTargetType _sourceType`

- `Boolean _checkBlockedCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBlocked : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _checkBlockedBySource; // 0x14
	private Boolean _checkBlockedBySourceToken; // 0x15
	private ActionTargetType _sourceType; // 0x18
	private Boolean _checkBlockedCount; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1570c VA: 0x759452d70c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f15774 VA: 0x759452d774
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f15e64 VA: 0x759452de64
	public Void .ctor() { }
}
```