# DerUniversalString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerUniversalString : DerStringBase
{
	private static readonly Char[] table; // 0x0
	private readonly Byte[] str; // 0x10


	// RVA: 0x65a16d0 VA: 0x7598bb96d0
	public static DerUniversalString GetInstance(Object obj) { }
	// RVA: 0x65a17c0 VA: 0x7598bb97c0
	public static DerUniversalString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590c48 VA: 0x7598ba8c48
	public Void .ctor(Byte[] str) { }
	// RVA: 0x65a18bc VA: 0x7598bb98bc
	public override String GetString() { }
	// RVA: 0x65a1a28 VA: 0x7598bb9a28
	public Byte[] GetOctets() { }
	// RVA: 0x65a1aa0 VA: 0x7598bb9aa0
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a1ac4 VA: 0x7598bb9ac4
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a1b60 VA: 0x7598bb9b60
	private static Void .cctor() { }
}
```