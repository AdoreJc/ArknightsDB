# SecT233K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT233K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64b7154 VA: 0x7598acf154
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b730c VA: 0x7598acf30c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b742c VA: 0x7598acf42c
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b7470 VA: 0x7598acf470
	protected override ECPoint Detach() { }
	// RVA: 0x64b7508 VA: 0x7598acf508
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64b75d8 VA: 0x7598acf5d8
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64b7654 VA: 0x7598acf654
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64b7d1c VA: 0x7598acfd1c
	public override ECPoint Twice() { }
	// RVA: 0x64b80b4 VA: 0x7598ad00b4
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64b8578 VA: 0x7598ad0578
	public override ECPoint Negate() { }
}
```