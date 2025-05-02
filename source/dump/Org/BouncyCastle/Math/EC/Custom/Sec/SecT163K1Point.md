# SecT163K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64ac21c VA: 0x7598ac421c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64ac3dc VA: 0x7598ac43dc
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64ac4fc VA: 0x7598ac44fc
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64ac538 VA: 0x7598ac4538
	protected override ECPoint Detach() { }
	// RVA: 0x64ac5d0 VA: 0x7598ac45d0
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64ac6a0 VA: 0x7598ac46a0
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64ac71c VA: 0x7598ac471c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64acdf4 VA: 0x7598ac4df4
	public override ECPoint Twice() { }
	// RVA: 0x64ad14c VA: 0x7598ac514c
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64ad628 VA: 0x7598ac5628
	public override ECPoint Negate() { }
}
```