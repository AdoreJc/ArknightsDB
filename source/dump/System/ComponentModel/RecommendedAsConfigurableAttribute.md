# RecommendedAsConfigurableAttribute

**Namespace:** `System.ComponentModel`


## Properties

- `Boolean RecommendedAsConfigurable`


## Methods

- `Boolean get_RecommendedAsConfigurable()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class RecommendedAsConfigurableAttribute : Attribute
{
	private readonly Boolean <RecommendedAsConfigurable>k__BackingField; // 0x10
	public static readonly RecommendedAsConfigurableAttribute No; // 0x0
	public static readonly RecommendedAsConfigurableAttribute Yes; // 0x8
	public static readonly RecommendedAsConfigurableAttribute Default; // 0x10

	public Boolean RecommendedAsConfigurable { get; }

	// RVA: 0x63d4880 VA: 0x75989ec880
	public Void .ctor(Boolean recommendedAsConfigurable) { }
	// RVA: 0x63d48a8 VA: 0x75989ec8a8
	public Boolean get_RecommendedAsConfigurable() { }
	// RVA: 0x63d48b0 VA: 0x75989ec8b0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63d4964 VA: 0x75989ec964
	public override Int32 GetHashCode() { }
	// RVA: 0x63d496c VA: 0x75989ec96c
	public override Boolean IsDefaultAttribute() { }
	// RVA: 0x63d497c VA: 0x75989ec97c
	private static Void .cctor() { }
}
```