# SecT409R1Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT409R1Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64c5814 VA: 0x7598add814
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64c5978 VA: 0x7598add978
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64c5a98 VA: 0x7598adda98
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64c5ad4 VA: 0x7598addad4
	protected override ECPoint Detach() { }
	// RVA: 0x64c5b6c VA: 0x7598addb6c
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64c5c3c VA: 0x7598addc3c
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64c5cb8 VA: 0x7598addcb8
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64c63a4 VA: 0x7598ade3a4
	public override ECPoint Twice() { }
	// RVA: 0x64c66fc VA: 0x7598ade6fc
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64c6bec VA: 0x7598adebec
	public override ECPoint Negate() { }
}
```