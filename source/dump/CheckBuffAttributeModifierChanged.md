# CheckBuffAttributeModifierChanged

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `AttributeType _sourceAttributeType`

- `AttributeType _buffAttributeType`

- `FormulaItemType _formulaType`

- `Boolean _useFirstDerivedBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBuffAttributeModifierChanged : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private AttributeType _sourceAttributeType; // 0x14
	private AttributeType _buffAttributeType; // 0x18
	private FormulaItemType _formulaType; // 0x1c
	private Boolean _useFirstDerivedBuff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f34950 VA: 0x759454c950
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f349b8 VA: 0x759454c9b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f34d4c VA: 0x759454cd4c
	public Void .ctor() { }
}
```