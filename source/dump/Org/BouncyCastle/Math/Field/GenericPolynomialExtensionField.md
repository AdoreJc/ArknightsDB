# GenericPolynomialExtensionField

**Namespace:** `Org.BouncyCastle.Math.Field`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.Field
internal class GenericPolynomialExtensionField : IPolynomialExtensionField, IExtensionField, IFiniteField
{
	protected readonly IFiniteField subfield; // 0x10
	protected readonly IPolynomial minimalPolynomial; // 0x18

	public virtual BigInteger Characteristic { get; }
	public virtual Int32 Dimension { get; }
	public virtual IFiniteField Subfield { get; }
	public virtual Int32 Degree { get; }
	public virtual IPolynomial MinimalPolynomial { get; }

	// RVA: 0x672b410 VA: 0x7598d43410
	internal Void .ctor(IFiniteField subfield, IPolynomial polynomial) { }
	// RVA: 0x672b71c VA: 0x7598d4371c
	public virtual BigInteger get_Characteristic() { }
	// RVA: 0x672b7bc VA: 0x7598d437bc
	public virtual Int32 get_Dimension() { }
	// RVA: 0x672b8e0 VA: 0x7598d438e0
	public virtual IFiniteField get_Subfield() { }
	// RVA: 0x672b8e8 VA: 0x7598d438e8
	public virtual Int32 get_Degree() { }
	// RVA: 0x672b988 VA: 0x7598d43988
	public virtual IPolynomial get_MinimalPolynomial() { }
	// RVA: 0x672b990 VA: 0x7598d43990
	public override Boolean Equals(Object obj) { }
	// RVA: 0x672ba60 VA: 0x7598d43a60
	public override Int32 GetHashCode() { }
}
```