# SecP160R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R1Point : AbstractFpPoint
{


	// RVA: 0x6481438 VA: 0x7598a99438
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6481770 VA: 0x7598a99770
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6481890 VA: 0x7598a99890
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6483360 VA: 0x7598a9b360
	protected override ECPoint Detach() { }
	// RVA: 0x64833f8 VA: 0x7598a9b3f8
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x6483ad0 VA: 0x7598a9bad0
	public override ECPoint Twice() { }
	// RVA: 0x6483fcc VA: 0x7598a9bfcc
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x6484098 VA: 0x7598a9c098
	public override ECPoint ThreeTimes() { }
	// RVA: 0x6484108 VA: 0x7598a9c108
	public override ECPoint Negate() { }
}
```