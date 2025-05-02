# DerNumericString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerNumericString : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x659eefc VA: 0x7598bb6efc
	public static DerNumericString GetInstance(Object obj) { }
	// RVA: 0x659efec VA: 0x7598bb6fec
	public static DerNumericString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590bd0 VA: 0x7598ba8bd0
	public Void .ctor(Byte[] str) { }
	// RVA: 0x659f1b8 VA: 0x7598bb71b8
	public Void .ctor(String str) { }
	// RVA: 0x659f0d8 VA: 0x7598bb70d8
	public Void .ctor(String str, Boolean validate) { }
	// RVA: 0x659f284 VA: 0x7598bb7284
	public override String GetString() { }
	// RVA: 0x659f28c VA: 0x7598bb728c
	public Byte[] GetOctets() { }
	// RVA: 0x659f298 VA: 0x7598bb7298
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659f2c8 VA: 0x7598bb72c8
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659f1c0 VA: 0x7598bb71c0
	public static Boolean IsNumericString(String str) { }
}
```