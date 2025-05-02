# SecT163R2Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT163R2Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64af208 VA: 0x7598ac7208
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64af36c VA: 0x7598ac736c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64af48c VA: 0x7598ac748c
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64af4c8 VA: 0x7598ac74c8
	protected override ECPoint Detach() { }
	// RVA: 0x64af560 VA: 0x7598ac7560
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64af630 VA: 0x7598ac7630
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64af6ac VA: 0x7598ac76ac
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64afd98 VA: 0x7598ac7d98
	public override ECPoint Twice() { }
	// RVA: 0x64b00f0 VA: 0x7598ac80f0
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64b05e0 VA: 0x7598ac85e0
	public override ECPoint Negate() { }
}
```