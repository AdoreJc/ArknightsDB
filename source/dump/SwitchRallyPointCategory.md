# SwitchRallyPointCategory

**Namespace:** ` `


## Fields

- `EntityCategory _category`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchRallyPointCategory : ActionNode
{
	private EntityCategory _category; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0dd70 VA: 0x7594525d70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0ddd8 VA: 0x7594525dd8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0df50 VA: 0x7594525f50
	public Void .ctor() { }
}
```