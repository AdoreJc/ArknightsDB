# SecT131R2Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT131R2Point : AbstractF2mPoint
{

	public override ECFieldElement YCoord { get; }
	protected internal override Boolean CompressionYTilde { get; }

	// RVA: 0x64a8c78 VA: 0x7598ac0c78
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64a8dd4 VA: 0x7598ac0dd4
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a8ef4 VA: 0x7598ac0ef4
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a8f38 VA: 0x7598ac0f38
	protected override ECPoint Detach() { }
	// RVA: 0x64a8fd0 VA: 0x7598ac0fd0
	public override ECFieldElement get_YCoord() { }
	// RVA: 0x64a90a0 VA: 0x7598ac10a0
	protected internal override Boolean get_CompressionYTilde() { }
	// RVA: 0x64a911c VA: 0x7598ac111c
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64a9884 VA: 0x7598ac1884
	public override ECPoint Twice() { }
	// RVA: 0x64a9c10 VA: 0x7598ac1c10
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64aa148 VA: 0x7598ac2148
	public override ECPoint Negate() { }
}
```