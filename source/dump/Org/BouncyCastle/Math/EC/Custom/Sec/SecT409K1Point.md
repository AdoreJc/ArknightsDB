# SecT409K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64c4088 VA: 0x7598adc088
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c4248 VA: 0x7598adc248
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c4368 VA: 0x7598adc368
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c43a4 VA: 0x7598adc3a4
	protected override ECPoint Detach() { }
	// RVA: 0x64c443c VA: 0x7598adc43c
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64c450c VA: 0x7598adc50c
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64c4588 VA: 0x7598adc588
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64c4c50 VA: 0x7598adcc50
	public override ECPoint Twice() { }
	// RVA: 0x64c4fe8 VA: 0x7598adcfe8
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64c54ac VA: 0x7598add4ac
	public override ECPoint Negate() { }
}
```