# SecT283R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT283R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64c0f14 VA: 0x7598ad8f14
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c107c VA: 0x7598ad907c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c119c VA: 0x7598ad919c
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c11d8 VA: 0x7598ad91d8
	protected override ECPoint Detach() { }
	// RVA: 0x64c1270 VA: 0x7598ad9270
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64c1340 VA: 0x7598ad9340
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64c13bc VA: 0x7598ad93bc
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64c1aa8 VA: 0x7598ad9aa8
	public override ECPoint Twice() { }
	// RVA: 0x64c1e00 VA: 0x7598ad9e00
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64c22f0 VA: 0x7598ada2f0
	public override ECPoint Negate() { }
}
```