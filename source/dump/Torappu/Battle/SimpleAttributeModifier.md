# SimpleAttributeModifier

**Namespace:** `Torappu.Battle`


## Fields

- `Attributes <attributes>k__BackingField`

- `Int64 <attributeMask>k__BackingField`

- `Int64 <abnormalFlagMask>k__BackingField`

- `Int64 <abnormalImmuneMask>k__BackingField`

- `Int64 <abnormalAntiMask>k__BackingField`

- `Int64 <abnormalComboMask>k__BackingField`

- `Int64 <abnormalComboImmuneMask>k__BackingField`


## Properties

- `Attributes attributes`

- `Int64 attributeMask`

- `Int64 abnormalFlagMask`

- `Int64 abnormalImmuneMask`

- `Int64 abnormalAntiMask`

- `Int64 abnormalComboMask`

- `Int64 abnormalComboImmuneMask`


## Methods

- `Attributes get_attributes()`

- `Void set_attributes(Attributes)`

- `Int64 get_attributeMask()`

- `Void set_attributeMask(Int64)`

- `Int64 get_abnormalFlagMask()`

- `Void set_abnormalFlagMask(Int64)`

- `Int64 get_abnormalImmuneMask()`

- `Void set_abnormalImmuneMask(Int64)`

- `Int64 get_abnormalAntiMask()`

- `Void set_abnormalAntiMask(Int64)`

- `Int64 get_abnormalComboMask()`

- `Void set_abnormalComboMask(Int64)`

- `Int64 get_abnormalComboImmuneMask()`

- `Void set_abnormalComboImmuneMask(Int64)`

- `Boolean GetValue(AttributeType, out, out, out, out)`

- `Void RegisterSelf()`

- `Void UnregisterSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SimpleAttributeModifier : IAttributesModifier
{
	private FP[] m_attributeAdditions; // 0x10
	private FP[] m_attributeMultipliers; // 0x18
	private FP[] m_attributeFinalAdditions; // 0x20
	private FP[] m_attributeFinalScalers; // 0x28
	private Attributes <attributes>k__BackingField; // 0x30
	private Int64 <attributeMask>k__BackingField; // 0x38
	private Int64 <abnormalFlagMask>k__BackingField; // 0x40
	private Int64 <abnormalImmuneMask>k__BackingField; // 0x48
	private Int64 <abnormalAntiMask>k__BackingField; // 0x50
	private Int64 <abnormalComboMask>k__BackingField; // 0x58
	private Int64 <abnormalComboImmuneMask>k__BackingField; // 0x60

	protected Attributes attributes { get; set; }
	public Int64 attributeMask { get; set; }
	public Int64 abnormalFlagMask { get; set; }
	public Int64 abnormalImmuneMask { get; set; }
	public Int64 abnormalAntiMask { get; set; }
	public Int64 abnormalComboMask { get; set; }
	public Int64 abnormalComboImmuneMask { get; set; }

	// RVA: 0x3f69e00 VA: 0x7596581e00
	protected Attributes get_attributes() { }
	// RVA: 0x3f69e08 VA: 0x7596581e08
	private Void set_attributes(Attributes value) { }
	// RVA: 0x3f69e10 VA: 0x7596581e10
	public Int64 get_attributeMask() { }
	// RVA: 0x3f69e18 VA: 0x7596581e18
	private Void set_attributeMask(Int64 value) { }
	// RVA: 0x3f69e20 VA: 0x7596581e20
	public Int64 get_abnormalFlagMask() { }
	// RVA: 0x3f69e28 VA: 0x7596581e28
	private Void set_abnormalFlagMask(Int64 value) { }
	// RVA: 0x3f69e30 VA: 0x7596581e30
	public Int64 get_abnormalImmuneMask() { }
	// RVA: 0x3f69e38 VA: 0x7596581e38
	private Void set_abnormalImmuneMask(Int64 value) { }
	// RVA: 0x3f69e40 VA: 0x7596581e40
	public Int64 get_abnormalAntiMask() { }
	// RVA: 0x3f69e48 VA: 0x7596581e48
	private Void set_abnormalAntiMask(Int64 value) { }
	// RVA: 0x3f69e50 VA: 0x7596581e50
	public Int64 get_abnormalComboMask() { }
	// RVA: 0x3f69e58 VA: 0x7596581e58
	private Void set_abnormalComboMask(Int64 value) { }
	// RVA: 0x3f69e60 VA: 0x7596581e60
	public Int64 get_abnormalComboImmuneMask() { }
	// RVA: 0x3f69e68 VA: 0x7596581e68
	private Void set_abnormalComboImmuneMask(Int64 value) { }
	// RVA: 0x3f69e70 VA: 0x7596581e70
	public Void .ctor(Attributes attributes, AttributeModifierData modifierData) { }
	// RVA: 0x3f6a03c VA: 0x759658203c
	public Boolean GetValue(AttributeType attributeType, out FP addition, out FP multiplier, out FP finalAddition, out FP finalScaler) { }
	// RVA: 0x3f6a0d8 VA: 0x75965820d8
	public Void RegisterSelf() { }
	// RVA: 0x3f6a0f4 VA: 0x75965820f4
	public Void UnregisterSelf() { }
}
```