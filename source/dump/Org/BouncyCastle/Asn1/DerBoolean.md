# DerBoolean

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `Boolean IsTrue`


## Methods

- `Boolean get_IsTrue()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerBoolean : Asn1Object
{
	private readonly Byte value; // 0x10
	public static readonly DerBoolean False; // 0x0
	public static readonly DerBoolean True; // 0x8

	public Boolean IsTrue { get; }

	// RVA: 0x659b6c4 VA: 0x7598bb36c4
	public static DerBoolean GetInstance(Object obj) { }
	// RVA: 0x659b7b4 VA: 0x7598bb37b4
	public static DerBoolean GetInstance(Boolean value) { }
	// RVA: 0x659b81c VA: 0x7598bb381c
	public static DerBoolean GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x659b96c VA: 0x7598bb396c
	public Void .ctor(Byte[] val) { }
	// RVA: 0x659ba0c VA: 0x7598bb3a0c
	private Void .ctor(Boolean value) { }
	// RVA: 0x659ba40 VA: 0x7598bb3a40
	public Boolean get_IsTrue() { }
	// RVA: 0x659ba50 VA: 0x7598bb3a50
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659bad4 VA: 0x7598bb3ad4
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659bb78 VA: 0x7598bb3b78
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659bbec VA: 0x7598bb3bec
	public override String ToString() { }
	// RVA: 0x6590304 VA: 0x7598ba8304
	internal static DerBoolean FromOctetString(Byte[] value) { }
	// RVA: 0x659bc58 VA: 0x7598bb3c58
	private static Void .cctor() { }
}
```