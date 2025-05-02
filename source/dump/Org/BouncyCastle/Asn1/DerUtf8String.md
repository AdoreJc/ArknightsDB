# DerUtf8String

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerUtf8String : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x65a3800 VA: 0x7598bbb800
	public static DerUtf8String GetInstance(Object obj) { }
	// RVA: 0x65a38f0 VA: 0x7598bbb8f0
	public static DerUtf8String GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a39c4 VA: 0x7598bbb9c4
	public Void .ctor(Byte[] str) { }
	// RVA: 0x65a3a18 VA: 0x7598bbba18
	public Void .ctor(String str) { }
	// RVA: 0x65a3a98 VA: 0x7598bbba98
	public override String GetString() { }
	// RVA: 0x65a3aa0 VA: 0x7598bbbaa0
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a3b40 VA: 0x7598bbbb40
	internal override Void Encode(DerOutputStream derOut) { }
}
```