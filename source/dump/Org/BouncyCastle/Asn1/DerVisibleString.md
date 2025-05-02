# DerVisibleString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerVisibleString : DerStringBase
{
	private readonly String str; // 0x10


	// RVA: 0x65a4000 VA: 0x7598bbc000
	public static DerVisibleString GetInstance(Object obj) { }
	// RVA: 0x65a41dc VA: 0x7598bbc1dc
	public static DerVisibleString GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65a41b8 VA: 0x7598bbc1b8
	public Void .ctor(Byte[] str) { }
	// RVA: 0x65a41f8 VA: 0x7598bbc1f8
	public Void .ctor(String str) { }
	// RVA: 0x65a4278 VA: 0x7598bbc278
	public override String GetString() { }
	// RVA: 0x65a4280 VA: 0x7598bbc280
	public Byte[] GetOctets() { }
	// RVA: 0x65a428c VA: 0x7598bbc28c
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a42c0 VA: 0x7598bbc2c0
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a4360 VA: 0x7598bbc360
	protected override Int32 Asn1GetHashCode() { }
}
```