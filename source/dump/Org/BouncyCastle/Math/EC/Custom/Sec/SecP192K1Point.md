# SecP192K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP192K1Point : AbstractFpPoint
{


	// RVA: 0x6486da4 VA: 0x7598a9eda4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64870dc VA: 0x7598a9f0dc
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64871fc VA: 0x7598a9f1fc
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6488d48 VA: 0x7598aa0d48
	protected override ECPoint Detach() { }
	// RVA: 0x6488de0 VA: 0x7598aa0de0
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64894b8 VA: 0x7598aa14b8
	public override ECPoint Twice() { }
	// RVA: 0x6489934 VA: 0x7598aa1934
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x6489a00 VA: 0x7598aa1a00
	public override ECPoint ThreeTimes() { }
	// RVA: 0x6489a70 VA: 0x7598aa1a70
	public override ECPoint Negate() { }
}
```