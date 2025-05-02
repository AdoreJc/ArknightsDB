# SecT131R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64a7400 VA: 0x7598abf400
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a7564 VA: 0x7598abf564
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a7684 VA: 0x7598abf684
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a76c0 VA: 0x7598abf6c0
	protected override ECPoint Detach() { }
	// RVA: 0x64a7758 VA: 0x7598abf758
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64a7828 VA: 0x7598abf828
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64a78a4 VA: 0x7598abf8a4
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64a800c VA: 0x7598ac000c
	public override ECPoint Twice() { }
	// RVA: 0x64a8398 VA: 0x7598ac0398
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64a88d0 VA: 0x7598ac08d0
	public override ECPoint Negate() { }
}
```