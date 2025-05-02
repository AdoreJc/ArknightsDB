# SecP160R2Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP160R2Point : AbstractFpPoint
{


	// RVA: 0x6484438 VA: 0x7598a9c438
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6484650 VA: 0x7598a9c650
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6484770 VA: 0x7598a9c770
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6485d48 VA: 0x7598a9dd48
	protected override ECPoint Detach() { }
	// RVA: 0x6485de0 VA: 0x7598a9dde0
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64864b8 VA: 0x7598a9e4b8
	public override ECPoint Twice() { }
	// RVA: 0x64869b4 VA: 0x7598a9e9b4
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x6486a80 VA: 0x7598a9ea80
	public override ECPoint ThreeTimes() { }
	// RVA: 0x6486af0 VA: 0x7598a9eaf0
	public override ECPoint Negate() { }
}
```