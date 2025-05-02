# AttributeModifierWithCertainBuffCount

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `AttributeType _attributeType`

- `FormulaItemType _formulaType`

- `Int32 _maxCnt`

- `String _buffKey`

- `Boolean _useOneAsMinCnt`

- `Boolean _writeModifyValueToBB`

- `String _writeToBBKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttributeModifierWithCertainBuffCount : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private AttributeType _attributeType; // 0x14
	private FormulaItemType _formulaType; // 0x18
	private Int32 _maxCnt; // 0x1c
	private String _buffKey; // 0x20
	private Boolean _useOneAsMinCnt; // 0x28
	private Boolean _writeModifyValueToBB; // 0x29
	private String _writeToBBKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f004b4 VA: 0x75945184b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0051c VA: 0x759451851c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f00944 VA: 0x7594518944
	public Void .ctor() { }
}
```