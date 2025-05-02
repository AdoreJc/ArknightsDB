# AttributeModifier

**Namespace:** ` `


## Fields

- `AttributeType attributeType`

- `FormulaItemType formulaItem`

- `Single value`

- `Boolean loadFromBlackboard`

- `Boolean fetchBaseValueFromSourceEntity`


## Methods

- `AttributeModifier DeepClone()`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttributeModifier : IHotfixable
{
	public AttributeType attributeType; // 0x10
	public FormulaItemType formulaItem; // 0x14
	public Single value; // 0x18
	public Boolean loadFromBlackboard; // 0x1c
	public Boolean fetchBaseValueFromSourceEntity; // 0x1d
	private static DelegateBridge __Hotfix0_ToString; // 0x0
	private static DelegateBridge __Hotfix0_DeepClone; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33c1ad4 VA: 0x75959d9ad4
	public override String ToString() { }
	// RVA: 0x33c1a34 VA: 0x75959d9a34
	public AttributeModifier DeepClone() { }
	// RVA: 0x33c1bc4 VA: 0x75959d9bc4
	public Void .ctor() { }
	// RVA: 0x33c1c3c VA: 0x75959d9c3c
	private String <>xLuaBaseProxy_ToString() { }
}
```