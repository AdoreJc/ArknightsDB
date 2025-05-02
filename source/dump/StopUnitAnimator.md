# StopUnitAnimator

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StopUnitAnimator : ActionNode
{
	private ActionTargetType _target; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd5078 VA: 0x75945ed078
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd50e0 VA: 0x75945ed0e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd52ac VA: 0x75945ed2ac
	public Void .ctor() { }
}
```