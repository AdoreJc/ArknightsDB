# FilterModifierTargetType

**Namespace:** ` `


## Fields

- `TargetType _modifierTargetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterModifierTargetType : ActionNode
{
	private TargetType _modifierTargetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7470c VA: 0x759458c70c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f74774 VA: 0x759458c774
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f74848 VA: 0x759458c848
	public Void .ctor() { }
}
```