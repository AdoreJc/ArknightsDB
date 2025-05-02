# Curve25519Point

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Djb`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Djb
internal class Curve25519Point : AbstractFpPoint
{


	// RVA: 0x64cbda8 VA: 0x7598ae3da8
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x64cc0e0 VA: 0x7598ae40e0
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64cc200 VA: 0x7598ae4200
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64cdff4 VA: 0x7598ae5ff4
	protected override ECPoint Detach() { }
	// RVA: 0x64ce08c VA: 0x7598ae608c
	public override ECFieldElement GetZCoord(Int32 index) { }
	// RVA: 0x64ce0ac VA: 0x7598ae60ac
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x64ce7fc VA: 0x7598ae67fc
	public override ECPoint Twice() { }
	// RVA: 0x64ce89c VA: 0x7598ae689c
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x64ce96c VA: 0x7598ae696c
	public override ECPoint ThreeTimes() { }
	// RVA: 0x64ce9e0 VA: 0x7598ae69e0
	public override ECPoint Negate() { }
	// RVA: 0x64ceab8 VA: 0x7598ae6ab8
	protected virtual Curve25519FieldElement CalculateJacobianModifiedW(Curve25519FieldElement Z, UInt32[] ZSquared) { }
	// RVA: 0x64cec14 VA: 0x7598ae6c14
	protected virtual Curve25519FieldElement GetJacobianModifiedW() { }
	// RVA: 0x64ced54 VA: 0x7598ae6d54
	protected virtual Curve25519Point TwiceJacobianModified(Boolean calculateW) { }
}
```