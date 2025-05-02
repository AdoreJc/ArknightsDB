# DerIA5String

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerIA5String : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x659e39c VA: 0x7598bb639c
	public static DerIA5String GetInstance(Object obj) { }
	// RVA: 0x659e48c VA: 0x7598bb648c
	public static DerIA5String GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6590b78 VA: 0x7598ba8b78
	public Void .ctor(Byte[] str) { }
	// RVA: 0x659e6b0 VA: 0x7598bb66b0
	public Void .ctor(String str) { }
	// RVA: 0x659e5d0 VA: 0x7598bb65d0
	public Void .ctor(String str, Boolean validate) { }
	// RVA: 0x659e720 VA: 0x7598bb6720
	public override String GetString() { }
	// RVA: 0x659e728 VA: 0x7598bb6728
	public Byte[] GetOctets() { }
	// RVA: 0x659e734 VA: 0x7598bb6734
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659e764 VA: 0x7598bb6764
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659e784 VA: 0x7598bb6784
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659e6b8 VA: 0x7598bb66b8
	public static Boolean IsIA5String(String str) { }
}
```