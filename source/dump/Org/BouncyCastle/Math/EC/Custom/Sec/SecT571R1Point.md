# SecT571R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT571R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64ca41c VA: 0x7598ae241c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64ca580 VA: 0x7598ae2580
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64ca6a0 VA: 0x7598ae26a0
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64ca884 VA: 0x7598ae2884
	protected override ECPoint Detach() { }
	// RVA: 0x64ca91c VA: 0x7598ae291c
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64ca9ec VA: 0x7598ae29ec
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64caa68 VA: 0x7598ae2a68
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64cb19c VA: 0x7598ae319c
	public override ECPoint Twice() { }
	// RVA: 0x64cb4f0 VA: 0x7598ae34f0
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64cb9dc VA: 0x7598ae39dc
	public override ECPoint Negate() { }
}
```