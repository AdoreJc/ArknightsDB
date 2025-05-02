# SandboxLogEnemyEvent

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _eventId`

- `Int32 _count`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxLogEnemyEvent : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _eventId; // 0x18
	private Int32 _count; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f85e00 VA: 0x759459de00
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f85e68 VA: 0x759459de68
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f86030 VA: 0x759459e030
	public Void .ctor() { }
}
```