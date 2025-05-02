# SecP256R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256R1Point : AbstractFpPoint
{


	// RVA: 0x64978bc VA: 0x7598aaf8bc
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6497bf4 VA: 0x7598aafbf4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6497d14 VA: 0x7598aafd14
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6499a84 VA: 0x7598ab1a84
	protected override ECPoint Detach() { }
	// RVA: 0x6499b1c VA: 0x7598ab1b1c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x649a1f4 VA: 0x7598ab21f4
	public override ECPoint Twice() { }
	// RVA: 0x649a6f0 VA: 0x7598ab26f0
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x649a7bc VA: 0x7598ab27bc
	public override ECPoint ThreeTimes() { }
	// RVA: 0x649a82c VA: 0x7598ab282c
	public override ECPoint Negate() { }
}
```