# Time

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Methods

- `String GetTime()`

- `DateTime ToDateTime()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class Time : Asn1Encodable, IAsn1Choice
{
	private readonly Asn1Object time; // 0x10


	// RVA: 0x65b7820 VA: 0x7598bcf820
	public static Time GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65b783c VA: 0x7598bcf83c
	public Void .ctor(Asn1Object time) { }
	// RVA: 0x65b7984 VA: 0x7598bcf984
	public Void .ctor(DateTime date) { }
	// RVA: 0x65b68a4 VA: 0x7598bce8a4
	public static Time GetInstance(Object obj) { }
	// RVA: 0x65b7b2c VA: 0x7598bcfb2c
	public String GetTime() { }
	// RVA: 0x65b7c1c VA: 0x7598bcfc1c
	public DateTime ToDateTime() { }
	// RVA: 0x65b7e00 VA: 0x7598bcfe00
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65b7e08 VA: 0x7598bcfe08
	public override String ToString() { }
}
```