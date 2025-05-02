# DescriptionPair

**Namespace:** `AdvancedInspector`


## Fields

- `Object value`

- `Description description`


## Properties

- `Object Value`

- `Description Description`


## Methods

- `Object get_Value()`

- `Description get_Description()`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class DescriptionPair
{
	private Object value; // 0x10
	private Description description; // 0x18

	public Object Value { get; }
	public Description Description { get; }

	// RVA: 0x1b219a8 VA: 0x75941399a8
	public Object get_Value() { }
	// RVA: 0x1b219b0 VA: 0x75941399b0
	public Description get_Description() { }
	// RVA: 0x1b1c920 VA: 0x7594134920
	public Void .ctor(Object value, Description descriptor) { }
	// RVA: 0x1b219b8 VA: 0x75941399b8
	public Void .ctor(Object value, String name) { }
	// RVA: 0x1b21a48 VA: 0x7594139a48
	public Void .ctor(Object value, String name, String description) { }
	// RVA: 0x1b21ad0 VA: 0x7594139ad0
	public static Boolean op_Equality(DescriptionPair a, DescriptionPair b) { }
	// RVA: 0x1b21afc VA: 0x7594139afc
	public static Boolean op_Inequality(DescriptionPair a, DescriptionPair b) { }
	// RVA: 0x1b21b38 VA: 0x7594139b38
	public override Boolean Equals(Object obj) { }
	// RVA: 0x1b21bd4 VA: 0x7594139bd4
	public override Int32 GetHashCode() { }
	// RVA: 0x1b21bdc VA: 0x7594139bdc
	public static DescriptionPair GetDescription(Object item) { }
	// RVA: 0x1b21d24 VA: 0x7594139d24
	public static IList`1 GetDescriptions(IList items) { }
}
```