# SecP384R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP384R1Point : AbstractFpPoint
{


	// RVA: 0x649ab5c VA: 0x7598ab2b5c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x649ae94 VA: 0x7598ab2e94
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x649afb4 VA: 0x7598ab2fb4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x649ce68 VA: 0x7598ab4e68
	protected override ECPoint Detach() { }
	// RVA: 0x649cf00 VA: 0x7598ab4f00
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x649d634 VA: 0x7598ab5634
	public override ECPoint Twice() { }
	// RVA: 0x649db44 VA: 0x7598ab5b44
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x649dc10 VA: 0x7598ab5c10
	public override ECPoint ThreeTimes() { }
	// RVA: 0x649dc80 VA: 0x7598ab5c80
	public override ECPoint Negate() { }
}
```