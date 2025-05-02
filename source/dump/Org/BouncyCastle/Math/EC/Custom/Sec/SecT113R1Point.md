# SecT113R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT113R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64a2154 VA: 0x7598aba154
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a22b8 VA: 0x7598aba2b8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a23d8 VA: 0x7598aba3d8
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a2838 VA: 0x7598aba838
	protected override ECPoint Detach() { }
	// RVA: 0x64a28d0 VA: 0x7598aba8d0
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64a29a0 VA: 0x7598aba9a0
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64a2a1c VA: 0x7598abaa1c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64a3184 VA: 0x7598abb184
	public override ECPoint Twice() { }
	// RVA: 0x64a3510 VA: 0x7598abb510
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64a3a48 VA: 0x7598abba48
	public override ECPoint Negate() { }
}
```