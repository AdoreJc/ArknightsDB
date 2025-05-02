# AttributeModifierData

**Namespace:** `Torappu`


## Methods

- `AttributeModifierData DeepClone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AttributeModifierData : IHotfixable
{
	public List`1 abnormalFlags; // 0x10
	public List`1 abnormalImmunes; // 0x18
	public List`1 abnormalAntis; // 0x20
	public List`1 abnormalCombos; // 0x28
	public List`1 abnormalComboImmunes; // 0x30
	public AttributeModifier[] attributeModifiers; // 0x38
	private static DelegateBridge __Hotfix0_DeepClone; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33c1688 VA: 0x75959d9688
	public AttributeModifierData DeepClone() { }
	// RVA: 0x33c19c4 VA: 0x75959d99c4
	public Void .ctor() { }
}
```