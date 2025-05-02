# F2mPoint

**Namespace:** `Org.BouncyCastle.Math.EC`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class F2mPoint : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x673207c VA: 0x7598d4a07c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x673263c VA: 0x7598d4a63c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6732794 VA: 0x7598d4a794
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x673bebc VA: 0x7598d53ebc
	public Void .ctor(ECCurve curve) { }
	// RVA: 0x673becc VA: 0x7598d53ecc
	protected override ECPoint Detach() { }
	// RVA: 0x673bf64 VA: 0x7598d53f64
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x673c064 VA: 0x7598d54064
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x673c12c VA: 0x7598d5412c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x673cdcc VA: 0x7598d54dcc
	public override ECPoint Twice() { }
	// RVA: 0x673d6c4 VA: 0x7598d556c4
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x673dc10 VA: 0x7598d55c10
	public override ECPoint Negate() { }
}
```