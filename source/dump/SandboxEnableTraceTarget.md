# SandboxEnableTraceTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _enabled`

- `Boolean _traceTileInstead`

- `Boolean _wholeTraceInstead`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxEnableTraceTarget : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _enabled; // 0x14
	private Boolean _traceTileInstead; // 0x15
	private Boolean _wholeTraceInstead; // 0x16
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f83720 VA: 0x759459b720
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f83788 VA: 0x759459b788
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f83994 VA: 0x759459b994
	public Void .ctor() { }
}
```