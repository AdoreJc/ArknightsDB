# SecT283K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64bf788 VA: 0x7598ad7788
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bf948 VA: 0x7598ad7948
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64bfa68 VA: 0x7598ad7a68
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64bfaa4 VA: 0x7598ad7aa4
	protected override ECPoint Detach() { }
	// RVA: 0x64bfb3c VA: 0x7598ad7b3c
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64bfc0c VA: 0x7598ad7c0c
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64bfc88 VA: 0x7598ad7c88
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64c0350 VA: 0x7598ad8350
	public override ECPoint Twice() { }
	// RVA: 0x64c06e8 VA: 0x7598ad86e8
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64c0bac VA: 0x7598ad8bac
	public override ECPoint Negate() { }
}
```