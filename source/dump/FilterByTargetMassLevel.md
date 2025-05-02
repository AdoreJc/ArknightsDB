# FilterByTargetMassLevel

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetMassLevel : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f20998 VA: 0x7594538998
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f20a00 VA: 0x7594538a00
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f20bf4 VA: 0x7594538bf4
	public Void .ctor() { }
}
```