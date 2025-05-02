# SecT571K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT571K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64c8cb0 VA: 0x7598ae0cb0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c8e70 VA: 0x7598ae0e70
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c8f90 VA: 0x7598ae0f90
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c8fcc VA: 0x7598ae0fcc
	protected override ECPoint Detach() { }
	// RVA: 0x64c9064 VA: 0x7598ae1064
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64c9134 VA: 0x7598ae1134
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64c91b0 VA: 0x7598ae11b0
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64c9888 VA: 0x7598ae1888
	public override ECPoint Twice() { }
	// RVA: 0x64c9c20 VA: 0x7598ae1c20
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64ca0e4 VA: 0x7598ae20e4
	public override ECPoint Negate() { }
}
```