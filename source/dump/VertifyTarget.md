# VertifyTarget

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `TargetOptions _targetOptions`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class VertifyTarget : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private TargetOptions _targetOptions; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1e1b0 VA: 0x75945361b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1e218 VA: 0x7594536218
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1e3a4 VA: 0x75945363a4
	public Void .ctor() { }
}
```