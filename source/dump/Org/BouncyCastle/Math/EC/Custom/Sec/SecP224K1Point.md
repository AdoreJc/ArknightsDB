# SecP224K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP224K1Point : AbstractFpPoint
{


	// RVA: 0x648cf80 VA: 0x7598aa4f80
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x648d2b8 VA: 0x7598aa52b8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x648d3d8 VA: 0x7598aa53d8
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x648f044 VA: 0x7598aa7044
	protected override ECPoint Detach() { }
	// RVA: 0x648f0dc VA: 0x7598aa70dc
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x648f7b4 VA: 0x7598aa77b4
	public override ECPoint Twice() { }
	// RVA: 0x648fc30 VA: 0x7598aa7c30
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x648fcfc VA: 0x7598aa7cfc
	public override ECPoint ThreeTimes() { }
	// RVA: 0x648fd6c VA: 0x7598aa7d6c
	public override ECPoint Negate() { }
}
```