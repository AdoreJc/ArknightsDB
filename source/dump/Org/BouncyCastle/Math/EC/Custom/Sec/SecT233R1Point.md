# SecT233R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT233R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64b88e0 VA: 0x7598ad08e0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64b8a44 VA: 0x7598ad0a44
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64b8b64 VA: 0x7598ad0b64
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64b8ba0 VA: 0x7598ad0ba0
	protected override ECPoint Detach() { }
	// RVA: 0x64b8c38 VA: 0x7598ad0c38
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64b8d08 VA: 0x7598ad0d08
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64b8d84 VA: 0x7598ad0d84
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64b9470 VA: 0x7598ad1470
	public override ECPoint Twice() { }
	// RVA: 0x64b97c8 VA: 0x7598ad17c8
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64b9cb8 VA: 0x7598ad1cb8
	public override ECPoint Negate() { }
}
```