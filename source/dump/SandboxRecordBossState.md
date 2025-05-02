# SandboxRecordBossState

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _forceModeKey`

- `String _ignoreModeKey`

- `Boolean _considerReborn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxRecordBossState : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _forceModeKey; // 0x18
	private String _ignoreModeKey; // 0x20
	private Boolean _considerReborn; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f88dbc VA: 0x75945a0dbc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f88e24 VA: 0x75945a0e24
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8920c VA: 0x75945a120c
	public Void .ctor() { }
}
```