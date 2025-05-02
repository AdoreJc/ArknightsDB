# X9ECPoint

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Fields

- `ECCurve c`

- `ECPoint p`


## Properties

- `ECPoint Point`

- `Boolean IsPointCompressed`


## Methods

- `ECPoint get_Point()`

- `Boolean get_IsPointCompressed()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X9ECPoint : Asn1Encodable
{
	private readonly Asn1OctetString encoding; // 0x10
	private ECCurve c; // 0x18
	private ECPoint p; // 0x20

	public ECPoint Point { get; }
	public Boolean IsPointCompressed { get; }

	// RVA: 0x65ad340 VA: 0x7598bc5340
	public Void .ctor(ECPoint p) { }
	// RVA: 0x65adcb4 VA: 0x7598bc5cb4
	public Void .ctor(ECPoint p, Boolean compressed) { }
	// RVA: 0x65a78d0 VA: 0x7598bbf8d0
	public Void .ctor(ECCurve c, Byte[] encoding) { }
	// RVA: 0x65ad240 VA: 0x7598bc5240
	public Void .ctor(ECCurve c, Asn1OctetString s) { }
	// RVA: 0x65add84 VA: 0x7598bc5d84
	public Byte[] GetPointEncoding() { }
	// RVA: 0x65ad880 VA: 0x7598bc5880
	public ECPoint get_Point() { }
	// RVA: 0x65addac VA: 0x7598bc5dac
	public Boolean get_IsPointCompressed() { }
	// RVA: 0x65addfc VA: 0x7598bc5dfc
	public override Asn1Object ToAsn1Object() { }
}
```