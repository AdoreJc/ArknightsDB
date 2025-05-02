# SecP224R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224R1Point : AbstractFpPoint
{


	// RVA: 0x649009c VA: 0x7598aa809c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64903d4 VA: 0x7598aa83d4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64904f4 VA: 0x7598aa84f4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6492840 VA: 0x7598aaa840
	protected override ECPoint Detach() { }
	// RVA: 0x64928d8 VA: 0x7598aaa8d8
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x6492fb0 VA: 0x7598aaafb0
	public override ECPoint Twice() { }
	// RVA: 0x64934ac VA: 0x7598aab4ac
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x6493578 VA: 0x7598aab578
	public override ECPoint ThreeTimes() { }
	// RVA: 0x64935e8 VA: 0x7598aab5e8
	public override ECPoint Negate() { }
}
```