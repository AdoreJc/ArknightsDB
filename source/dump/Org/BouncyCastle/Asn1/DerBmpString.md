# DerBmpString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerBmpString : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x659b2d8 VA: 0x7598bb32d8
	public static DerBmpString GetInstance(Object obj) { }
	// RVA: 0x659b3c8 VA: 0x7598bb33c8
	public static DerBmpString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65909a4 VA: 0x7598ba89a4
	public Void .ctor(Byte[] str) { }
	// RVA: 0x659b4a0 VA: 0x7598bb34a0
	public Void .ctor(String str) { }
	// RVA: 0x659b520 VA: 0x7598bb3520
	public override String GetString() { }
	// RVA: 0x659b528 VA: 0x7598bb3528
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659b5c8 VA: 0x7598bb35c8
	internal override Void Encode(DerOutputStream derOut) { }
}
```