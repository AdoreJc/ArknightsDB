# AttributeModifierWithLevelProgress

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `AttributeType _attributeType`

- `Boolean _isFinalScale`

- `String _guaranteedPercentageString`

- `String _maxPercentageString`

- `FormulaItemType _formulaType`

- `Single _levelProgressRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttributeModifierWithLevelProgress : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private AttributeType _attributeType; // 0x14
	private Boolean _isFinalScale; // 0x18
	private String _guaranteedPercentageString; // 0x20
	private String _maxPercentageString; // 0x28
	private FormulaItemType _formulaType; // 0x30
	private Single _levelProgressRatio; // 0x34
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd0074 VA: 0x75945e8074
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd00dc VA: 0x75945e80dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd0440 VA: 0x75945e8440
	public Void .ctor() { }
}
```