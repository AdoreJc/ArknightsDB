# SecT163R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64ad9d0 VA: 0x7598ac59d0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64adb34 VA: 0x7598ac5b34
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64adc54 VA: 0x7598ac5c54
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64adc90 VA: 0x7598ac5c90
	protected override ECPoint Detach() { }
	// RVA: 0x64add28 VA: 0x7598ac5d28
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64addf8 VA: 0x7598ac5df8
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64ade74 VA: 0x7598ac5e74
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64ae5dc VA: 0x7598ac65dc
	public override ECPoint Twice() { }
	// RVA: 0x64ae968 VA: 0x7598ac6968
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64aeea0 VA: 0x7598ac6ea0
	public override ECPoint Negate() { }
}
```