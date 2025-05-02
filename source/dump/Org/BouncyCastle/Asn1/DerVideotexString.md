# DerVideotexString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerVideotexString : DerStringBase
{
	private readonly Byte[] mString; // 0x10


	// RVA: 0x65a3b94 VA: 0x7598bbbb94
	public static DerVideotexString GetInstance(Object obj) { }
	// RVA: 0x65a3db4 VA: 0x7598bbbdb4
	public static DerVideotexString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a3edc VA: 0x7598bbbedc
	public Void .ctor(Byte[] encoding) { }
	// RVA: 0x65a3f18 VA: 0x7598bbbf18
	public override String GetString() { }
	// RVA: 0x65a3f24 VA: 0x7598bbbf24
	public Byte[] GetOctets() { }
	// RVA: 0x65a3f30 VA: 0x7598bbbf30
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a3f58 VA: 0x7598bbbf58
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x65a3f64 VA: 0x7598bbbf64
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
}
```