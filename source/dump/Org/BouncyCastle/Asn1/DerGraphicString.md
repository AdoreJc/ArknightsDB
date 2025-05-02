# DerGraphicString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerGraphicString : DerStringBase
{
	private readonly Byte[] mString; // 0x10


	// RVA: 0x659df6c VA: 0x7598bb5f6c
	public static DerGraphicString GetInstance(Object obj) { }
	// RVA: 0x659e188 VA: 0x7598bb6188
	public static DerGraphicString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590b3c VA: 0x7598ba8b3c
	public Void .ctor(Byte[] encoding) { }
	// RVA: 0x659e2b8 VA: 0x7598bb62b8
	public override String GetString() { }
	// RVA: 0x659e2c4 VA: 0x7598bb62c4
	public Byte[] GetOctets() { }
	// RVA: 0x659e2d0 VA: 0x7598bb62d0
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659e2f4 VA: 0x7598bb62f4
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659e300 VA: 0x7598bb6300
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
}
```