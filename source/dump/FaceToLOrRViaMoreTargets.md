# FaceToLOrRViaMoreTargets

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `TargetOptions _targetOptions`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FaceToLOrRViaMoreTargets : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private TargetOptions _targetOptions; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc820c VA: 0x75945e020c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc8274 VA: 0x75945e0274
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc88a0 VA: 0x75945e08a0
	public Void .ctor() { }
}
```