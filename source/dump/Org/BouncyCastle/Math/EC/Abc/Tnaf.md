# Tnaf

**Namespace:** `Org.BouncyCastle.Math.EC.Abc`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Abc
internal class Tnaf
{
	private static readonly BigInteger MinusOne; // 0x0
	private static readonly BigInteger MinusTwo; // 0x8
	private static readonly BigInteger MinusThree; // 0x10
	private static readonly BigInteger Four; // 0x18
	public const SByte Width; // 0x0
	public const SByte Pow2Width; // 0x0
	public static readonly ZTauElement[] Alpha0; // 0x20
	public static readonly SByte[][] Alpha0Tnaf; // 0x28
	public static readonly ZTauElement[] Alpha1; // 0x30
	public static readonly SByte[][] Alpha1Tnaf; // 0x38


	// RVA: 0x64cffb0 VA: 0x7598ae7fb0
	public static BigInteger Norm(SByte mu, ZTauElement lambda) { }
	// RVA: 0x64d00cc VA: 0x7598ae80cc
	public static SimpleBigDecimal Norm(SByte mu, SimpleBigDecimal u, SimpleBigDecimal v) { }
	// RVA: 0x64d01c8 VA: 0x7598ae81c8
	public static ZTauElement Round(SimpleBigDecimal lambda0, SimpleBigDecimal lambda1, SByte mu) { }
	// RVA: 0x64d05c4 VA: 0x7598ae85c4
	public static SimpleBigDecimal ApproximateDivisionByN(BigInteger k, BigInteger s, BigInteger vm, SByte a, Int32 m, Int32 c) { }
	// RVA: 0x64d073c VA: 0x7598ae873c
	public static SByte[] TauAdicNaf(SByte mu, ZTauElement lambda) { }
	// RVA: 0x64d0ae0 VA: 0x7598ae8ae0
	public static AbstractF2mPoint Tau(AbstractF2mPoint p) { }
	// RVA: 0x64d0b00 VA: 0x7598ae8b00
	public static SByte GetMu(AbstractF2mCurve curve) { }
	// RVA: 0x64d0c04 VA: 0x7598ae8c04
	public static SByte GetMu(ECFieldElement curveA) { }
	// RVA: 0x64d0c34 VA: 0x7598ae8c34
	public static SByte GetMu(Int32 curveA) { }
	// RVA: 0x64d0c44 VA: 0x7598ae8c44
	public static BigInteger[] GetLucas(SByte mu, Int32 k, Boolean doV) { }
	// RVA: 0x64d0e40 VA: 0x7598ae8e40
	public static BigInteger GetTw(SByte mu, Int32 w) { }
	// RVA: 0x64d0fac VA: 0x7598ae8fac
	public static BigInteger[] GetSi(AbstractF2mCurve curve) { }
	// RVA: 0x64d138c VA: 0x7598ae938c
	public static BigInteger[] GetSi(Int32 fieldSize, Int32 curveA, BigInteger cofactor) { }
	// RVA: 0x64d12f4 VA: 0x7598ae92f4
	protected static Int32 GetShiftsForCofactor(BigInteger h) { }
	// RVA: 0x64d1618 VA: 0x7598ae9618
	public static ZTauElement PartModReduction(BigInteger k, Int32 m, SByte a, BigInteger[] s, SByte mu, SByte c) { }
	// RVA: 0x64d18a0 VA: 0x7598ae98a0
	public static AbstractF2mPoint MultiplyRTnaf(AbstractF2mPoint p, BigInteger k) { }
	// RVA: 0x64d19f0 VA: 0x7598ae99f0
	public static AbstractF2mPoint MultiplyTnaf(AbstractF2mPoint p, ZTauElement lambda) { }
	// RVA: 0x64d1b14 VA: 0x7598ae9b14
	public static AbstractF2mPoint MultiplyFromTnaf(AbstractF2mPoint p, SByte[] u) { }
	// RVA: 0x64d1d20 VA: 0x7598ae9d20
	public static SByte[] TauAdicWNaf(SByte mu, ZTauElement lambda, SByte width, BigInteger pow2w, BigInteger tw, ZTauElement[] alpha) { }
	// RVA: 0x64d20e0 VA: 0x7598aea0e0
	public static AbstractF2mPoint[] GetPreComp(AbstractF2mPoint p, SByte a) { }
	// RVA: 0x64d2298 VA: 0x7598aea298
	public Void .ctor() { }
	// RVA: 0x64d22a0 VA: 0x7598aea2a0
	private static Void .cctor() { }
}
```