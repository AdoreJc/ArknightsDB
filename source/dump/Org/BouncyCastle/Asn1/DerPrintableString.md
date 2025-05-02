# DerPrintableString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerPrintableString : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x65a0904 VA: 0x7598bb8904
	public static DerPrintableString GetInstance(Object obj) { }
	// RVA: 0x65a09f4 VA: 0x7598bb89f4
	public static DerPrintableString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590bfc VA: 0x7598ba8bfc
	public Void .ctor(Byte[] str) { }
	// RVA: 0x65a0bc0 VA: 0x7598bb8bc0
	public Void .ctor(String str) { }
	// RVA: 0x65a0ae0 VA: 0x7598bb8ae0
	public Void .ctor(String str, Boolean validate) { }
	// RVA: 0x65a0cd4 VA: 0x7598bb8cd4
	public override String GetString() { }
	// RVA: 0x65a0cdc VA: 0x7598bb8cdc
	public Byte[] GetOctets() { }
	// RVA: 0x65a0ce8 VA: 0x7598bb8ce8
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a0d18 VA: 0x7598bb8d18
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a0bc8 VA: 0x7598bb8bc8
	public static Boolean IsPrintableString(String str) { }
}
```