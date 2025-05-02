# SecT239K1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT239K1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64bbce8 VA: 0x7598ad3ce8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64bbea8 VA: 0x7598ad3ea8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64bbfc8 VA: 0x7598ad3fc8
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64bc004 VA: 0x7598ad4004
	protected override ECPoint Detach() { }
	// RVA: 0x64bc09c VA: 0x7598ad409c
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64bc16c VA: 0x7598ad416c
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64bc1e8 VA: 0x7598ad41e8
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64bc8b0 VA: 0x7598ad48b0
	public override ECPoint Twice() { }
	// RVA: 0x64bcc48 VA: 0x7598ad4c48
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64bd10c VA: 0x7598ad510c
	public override ECPoint Negate() { }
}
```