# BerOctetString

**Namespace:** `Org.BouncyCastle.Asn1`


## Methods

- `IEnumerator GetEnumerator()`

- `IEnumerator GetObjects()`

- `IList GenerateOcts()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class BerOctetString : DerOctetString, IEnumerable
{
	private const Int32 MaxLength; // 0x0
	private readonly IEnumerable octs; // 0x18


	// RVA: 0x6591628 VA: 0x7598ba9628
	public static BerOctetString FromSequence(Asn1Sequence seq) { }
	// RVA: 0x6596d60 VA: 0x7598baed60
	private static Byte[] ToBytes(IEnumerable octs) { }
	// RVA: 0x6597120 VA: 0x7598baf120
	public Void .ctor(Byte[] str) { }
	// RVA: 0x658e5f0 VA: 0x7598ba65f0
	public Void .ctor(IEnumerable octets) { }
	// RVA: 0x6597124 VA: 0x7598baf124
	public Void .ctor(Asn1Object obj) { }
	// RVA: 0x659712c VA: 0x7598baf12c
	public Void .ctor(Asn1Encodable obj) { }
	// RVA: 0x6597160 VA: 0x7598baf160
	public override Byte[] GetOctets() { }
	// RVA: 0x6597168 VA: 0x7598baf168
	public IEnumerator GetEnumerator() { }
	// RVA: 0x6597414 VA: 0x7598baf414
	public IEnumerator GetObjects() { }
	// RVA: 0x659724c VA: 0x7598baf24c
	private IList GenerateOcts() { }
	// RVA: 0x6597418 VA: 0x7598baf418
	internal override Void Encode(DerOutputStream derOut) { }
}
```