# SecP256K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecP256K1Point : AbstractFpPoint
{


	// RVA: 0x649489c VA: 0x7598aac89c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6494bd4 VA: 0x7598aacbd4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x6494cf4 VA: 0x7598aaccf4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6496864 VA: 0x7598aae864
	protected override ECPoint Detach() { }
	// RVA: 0x64968fc VA: 0x7598aae8fc
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x6496fd4 VA: 0x7598aaefd4
	public override ECPoint Twice() { }
	// RVA: 0x6497450 VA: 0x7598aaf450
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x649751c VA: 0x7598aaf51c
	public override ECPoint ThreeTimes() { }
	// RVA: 0x649758c VA: 0x7598aaf58c
	public override ECPoint Negate() { }
}
```