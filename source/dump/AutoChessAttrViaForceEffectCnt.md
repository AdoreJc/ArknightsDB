# AutoChessAttrViaForceEffectCnt

**Namespace:** ` `


## Fields

- `FormulaItemType _formulaItemType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessAttrViaForceEffectCnt : ActionNode
{
	private AttributeType[] _attributeTypes; // 0x10
	private FormulaItemType _formulaItemType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee7794 VA: 0x75944ff794
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee77fc VA: 0x75944ff7fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee7bb0 VA: 0x75944ffbb0
	public Void .ctor() { }
}
```