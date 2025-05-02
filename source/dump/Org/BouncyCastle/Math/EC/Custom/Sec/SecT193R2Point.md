# SecT193R2Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT193R2Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64b3cc8 VA: 0x7598acbcc8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b3e2c VA: 0x7598acbe2c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b3f4c VA: 0x7598acbf4c
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b3f88 VA: 0x7598acbf88
	protected override ECPoint Detach() { }
	// RVA: 0x64b4020 VA: 0x7598acc020
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64b40f0 VA: 0x7598acc0f0
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64b416c VA: 0x7598acc16c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64b48d4 VA: 0x7598acc8d4
	public override ECPoint Twice() { }
	// RVA: 0x64b4c60 VA: 0x7598accc60
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64b5198 VA: 0x7598acd198
	public override ECPoint Negate() { }
}
```