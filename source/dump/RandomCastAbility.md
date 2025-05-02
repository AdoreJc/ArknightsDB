# RandomCastAbility

**Namespace:** ` `


## Methods

- `Void GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RandomCastAbility : ActionNode, IActionNodeSource
{
	private TriggerAbility[] _abilities; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7c578 VA: 0x7594594578
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7c5e0 VA: 0x75945945e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7c72c VA: 0x759459472c
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1f7c7b4 VA: 0x75945947b4
	public Void .ctor() { }
}
```