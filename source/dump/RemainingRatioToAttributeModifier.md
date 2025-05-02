# RemainingRatioToAttributeModifier

**Namespace:** ` `


## Fields

- `AttributeType _attributeType`

- `FormulaItemType _formulaType`

- `Boolean _isInversed`

- `Single _endTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RemainingRatioToAttributeModifier : ActionNode
{
	private AttributeType _attributeType; // 0x10
	private FormulaItemType _formulaType; // 0x14
	private Boolean _isInversed; // 0x18
	private Single _endTime; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1efff24 VA: 0x7594517f24
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efff8c VA: 0x7594517f8c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0043c VA: 0x759451843c
	public Void .ctor() { }
}
```