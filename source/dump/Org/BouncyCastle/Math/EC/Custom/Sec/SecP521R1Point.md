# SecP521R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP521R1Point : AbstractFpPoint
{


	// RVA: 0x649dfb0 VA: 0x7598ab5fb0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x649e2e8 VA: 0x7598ab62e8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x649e408 VA: 0x7598ab6408
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x649fb50 VA: 0x7598ab7b50
	protected override ECPoint Detach() { }
	// RVA: 0x649fbe8 VA: 0x7598ab7be8
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64a02dc VA: 0x7598ab82dc
	public override ECPoint Twice() { }
	// RVA: 0x64a07ec VA: 0x7598ab87ec
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64a08b8 VA: 0x7598ab88b8
	public override ECPoint ThreeTimes() { }
	// RVA: 0x64a0928 VA: 0x7598ab8928
	public override ECPoint Negate() { }
}
```