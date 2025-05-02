# SecT113R2Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT113R2Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64a3df0 VA: 0x7598abbdf0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a3f54 VA: 0x7598abbf54
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a4074 VA: 0x7598abc074
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a40b0 VA: 0x7598abc0b0
	protected override ECPoint Detach() { }
	// RVA: 0x64a4148 VA: 0x7598abc148
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64a4218 VA: 0x7598abc218
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64a4294 VA: 0x7598abc294
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64a49fc VA: 0x7598abc9fc
	public override ECPoint Twice() { }
	// RVA: 0x64a4d88 VA: 0x7598abcd88
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64a52c0 VA: 0x7598abd2c0
	public override ECPoint Negate() { }
}
```