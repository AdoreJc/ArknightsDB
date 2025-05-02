# SecP128R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP128R1Point : AbstractFpPoint
{


	// RVA: 0x647c97c VA: 0x7598a9497c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x647ccb4 VA: 0x7598a94cb4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x647cdd4 VA: 0x7598a94dd4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x647e8e8 VA: 0x7598a968e8
	protected override ECPoint Detach() { }
	// RVA: 0x647e980 VA: 0x7598a96980
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x647f058 VA: 0x7598a97058
	public override ECPoint Twice() { }
	// RVA: 0x647f554 VA: 0x7598a97554
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x647f620 VA: 0x7598a97620
	public override ECPoint ThreeTimes() { }
	// RVA: 0x647f690 VA: 0x7598a97690
	public override ECPoint Negate() { }
}
```