# DerGeneralString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerGeneralString : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x659d934 VA: 0x7598bb5934
	public static DerGeneralString GetInstance(Object obj) { }
	// RVA: 0x659da24 VA: 0x7598bb5a24
	public static DerGeneralString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590b18 VA: 0x7598ba8b18
	public Void .ctor(Byte[] str) { }
	// RVA: 0x659db64 VA: 0x7598bb5b64
	public Void .ctor(String str) { }
	// RVA: 0x659dbe4 VA: 0x7598bb5be4
	public override String GetString() { }
	// RVA: 0x659dbec VA: 0x7598bb5bec
	public Byte[] GetOctets() { }
	// RVA: 0x659dbf8 VA: 0x7598bb5bf8
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659dc28 VA: 0x7598bb5c28
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
}
```