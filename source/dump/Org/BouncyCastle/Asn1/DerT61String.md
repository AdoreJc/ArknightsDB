# DerT61String

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerT61String : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x65a1320 VA: 0x7598bb9320
	public static DerT61String GetInstance(Object obj) { }
	// RVA: 0x65a1410 VA: 0x7598bb9410
	public static DerT61String GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590c24 VA: 0x7598ba8c24
	public Void .ctor(Byte[] str) { }
	// RVA: 0x65a14f8 VA: 0x7598bb94f8
	public Void .ctor(String str) { }
	// RVA: 0x65a1578 VA: 0x7598bb9578
	public override String GetString() { }
	// RVA: 0x65a1580 VA: 0x7598bb9580
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a15b0 VA: 0x7598bb95b0
	public Byte[] GetOctets() { }
	// RVA: 0x65a15bc VA: 0x7598bb95bc
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
}
```