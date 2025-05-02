# UpdateBuffAttributeModifier

**Namespace:** ` `


## Fields

- `Single _value`

- `Boolean _useBlackboard`

- `AttributeType _attributeType`

- `FormulaItemType _formulaType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpdateBuffAttributeModifier : ActionNode
{
	private Single _value; // 0x10
	private Boolean _useBlackboard; // 0x14
	private AttributeType _attributeType; // 0x18
	private FormulaItemType _formulaType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f01ff0 VA: 0x7594519ff0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f02058 VA: 0x759451a058
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f02208 VA: 0x759451a208
	public Void .ctor() { }
}
```