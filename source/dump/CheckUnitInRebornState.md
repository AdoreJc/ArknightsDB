# CheckUnitInRebornState

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckUnitInRebornState : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f29d18 VA: 0x7594541d18
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f29d80 VA: 0x7594541d80
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f29f00 VA: 0x7594541f00
	public Void .ctor() { }
}
```