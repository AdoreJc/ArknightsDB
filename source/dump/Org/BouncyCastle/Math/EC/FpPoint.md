# FpPoint

**Namespace:** `Org.BouncyCastle.Math.EC`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class FpPoint : AbstractFpPoint
{


	// RVA: 0x673038c VA: 0x7598d4838c
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y) { }
	// RVA: 0x6730774 VA: 0x7598d48774
	public Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x673088c VA: 0x7598d4888c
	internal Void .ctor(ECCurve curve, ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x6738138 VA: 0x7598d50138
	protected override ECPoint Detach() { }
	// RVA: 0x67381d0 VA: 0x7598d501d0
	public override ECFieldElement GetZCoord(Int32 index) { }
	// RVA: 0x6738230 VA: 0x7598d50230
	public override ECPoint Add(ECPoint b) { }
	// RVA: 0x6738e50 VA: 0x7598d50e50
	public override ECPoint Twice() { }
	// RVA: 0x6739968 VA: 0x7598d51968
	public override ECPoint TwicePlus(ECPoint b) { }
	// RVA: 0x6739ddc VA: 0x7598d51ddc
	public override ECPoint ThreeTimes() { }
	// RVA: 0x673a1e0 VA: 0x7598d521e0
	public override ECPoint TimesPow2(Int32 e) { }
	// RVA: 0x673a9e0 VA: 0x7598d529e0
	protected virtual ECFieldElement Two(ECFieldElement x) { }
	// RVA: 0x673aa00 VA: 0x7598d52a00
	protected virtual ECFieldElement Three(ECFieldElement x) { }
	// RVA: 0x673aa34 VA: 0x7598d52a34
	protected virtual ECFieldElement Four(ECFieldElement x) { }
	// RVA: 0x673aa68 VA: 0x7598d52a68
	protected virtual ECFieldElement Eight(ECFieldElement x) { }
	// RVA: 0x673aa9c VA: 0x7598d52a9c
	protected virtual ECFieldElement DoubleProductFromSquares(ECFieldElement a, ECFieldElement b, ECFieldElement aSquared, ECFieldElement bSquared) { }
	// RVA: 0x673ab10 VA: 0x7598d52b10
	public override ECPoint Negate() { }
	// RVA: 0x673ac2c VA: 0x7598d52c2c
	protected virtual ECFieldElement CalculateJacobianModifiedW(ECFieldElement Z, ECFieldElement ZSquared) { }
	// RVA: 0x673ad80 VA: 0x7598d52d80
	protected virtual ECFieldElement GetJacobianModifiedW() { }
	// RVA: 0x673ae1c VA: 0x7598d52e1c
	protected virtual FpPoint TwiceJacobianModified(Boolean calculateW) { }
}
```