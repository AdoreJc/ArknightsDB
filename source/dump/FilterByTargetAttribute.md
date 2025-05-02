# FilterByTargetAttribute

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `CompareType _condType`

- `AttributeType _attributeType`

- `Int32 _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterByTargetAttribute : ActionNode
{
	private ActionTargetType _target; // 0x10
	private CompareType _condType; // 0x14
	private AttributeType _attributeType; // 0x18
	private Int32 _value; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f20c64 VA: 0x7594538c64
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f20ccc VA: 0x7594538ccc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f20ec0 VA: 0x7594538ec0
	public Void .ctor() { }
}
```