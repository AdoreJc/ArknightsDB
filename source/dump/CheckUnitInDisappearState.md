# CheckUnitInDisappearState

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckUnitInDisappearState : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2931c VA: 0x759454131c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f29384 VA: 0x7594541384
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f294f0 VA: 0x75945414f0
	public Void .ctor() { }
}
```