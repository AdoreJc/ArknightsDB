# MakeTargetDyingInCooperate

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class MakeTargetDyingInCooperate : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f383fc VA: 0x75945503fc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f38464 VA: 0x7594550464
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f385d4 VA: 0x75945505d4
	public Void .ctor() { }
}
```