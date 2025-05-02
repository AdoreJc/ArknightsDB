# SecT193R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64b2450 VA: 0x7598aca450
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b25b4 VA: 0x7598aca5b4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b26d4 VA: 0x7598aca6d4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b2710 VA: 0x7598aca710
	protected override ECPoint Detach() { }
	// RVA: 0x64b27a8 VA: 0x7598aca7a8
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64b2878 VA: 0x7598aca878
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64b28f4 VA: 0x7598aca8f4
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64b305c VA: 0x7598acb05c
	public override ECPoint Twice() { }
	// RVA: 0x64b33e8 VA: 0x7598acb3e8
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64b3920 VA: 0x7598acb920
	public override ECPoint Negate() { }
}
```