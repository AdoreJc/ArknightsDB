# DerEnumerated

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `BigInteger Value`


## Methods

- `BigInteger get_Value()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerEnumerated : Asn1Object
{
	private readonly Byte[] bytes; // 0x10
	private static readonly DerEnumerated[] cache; // 0x0

	public BigInteger Value { get; }

	// RVA: 0x659bd00 VA: 0x7598bb3d00
	public static DerEnumerated GetInstance(Object obj) { }
	// RVA: 0x659bdf0 VA: 0x7598bb3df0
	public static DerEnumerated GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x659bf40 VA: 0x7598bb3f40
	public Void .ctor(Int32 val) { }
	// RVA: 0x659bfd0 VA: 0x7598bb3fd0
	public Void .ctor(BigInteger val) { }
	// RVA: 0x659c014 VA: 0x7598bb4014
	public Void .ctor(Byte[] bytes) { }
	// RVA: 0x659c044 VA: 0x7598bb4044
	public BigInteger get_Value() { }
	// RVA: 0x659c0ac VA: 0x7598bb40ac
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659c0d0 VA: 0x7598bb40d0
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659c16c VA: 0x7598bb416c
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x6590424 VA: 0x7598ba8424
	internal static DerEnumerated FromOctetString(Byte[] enc) { }
	// RVA: 0x659c178 VA: 0x7598bb4178
	private static Void .cctor() { }
}
```