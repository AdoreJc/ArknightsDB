# ECAlgorithms

**Namespace:** `Org.BouncyCastle.Math.EC`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC
public class ECAlgorithms
{


	// RVA: 0x672bc90 VA: 0x7598d43c90
	public static Boolean IsF2mCurve(ECCurve c) { }
	// RVA: 0x672bcb4 VA: 0x7598d43cb4
	public static Boolean IsF2mField(IFiniteField field) { }
	// RVA: 0x672be38 VA: 0x7598d43e38
	public static Boolean IsFpCurve(ECCurve c) { }
	// RVA: 0x672be5c VA: 0x7598d43e5c
	public static Boolean IsFpField(IFiniteField field) { }
	// RVA: 0x672bf08 VA: 0x7598d43f08
	public static ECPoint SumOfMultiplies(ECPoint[] ps, BigInteger[] ks) { }
	// RVA: 0x672c18c VA: 0x7598d4418c
	public static ECPoint SumOfTwoMultiplies(ECPoint P, BigInteger a, ECPoint Q, BigInteger b) { }
	// RVA: 0x672cef0 VA: 0x7598d44ef0
	public static ECPoint ShamirsTrick(ECPoint P, BigInteger k, ECPoint Q, BigInteger l) { }
	// RVA: 0x672c430 VA: 0x7598d44430
	public static ECPoint ImportPoint(ECCurve c, ECPoint p) { }
	// RVA: 0x672d4d4 VA: 0x7598d454d4
	public static Void MontgomeryTrick(ECFieldElement[] zs, Int32 off, Int32 len) { }
	// RVA: 0x672d4dc VA: 0x7598d454dc
	public static Void MontgomeryTrick(ECFieldElement[] zs, Int32 off, Int32 len, ECFieldElement scale) { }
	// RVA: 0x672d7d0 VA: 0x7598d457d0
	public static ECPoint ReferenceMultiply(ECPoint p, BigInteger k) { }
	// RVA: 0x672c96c VA: 0x7598d4496c
	public static ECPoint ValidatePoint(ECPoint p) { }
	// RVA: 0x672cf4c VA: 0x7598d44f4c
	internal static ECPoint ImplShamirsTrickJsf(ECPoint P, BigInteger k, ECPoint Q, BigInteger l) { }
	// RVA: 0x672cc8c VA: 0x7598d44c8c
	internal static ECPoint ImplShamirsTrickWNaf(ECPoint P, BigInteger k, ECPoint Q, BigInteger l) { }
	// RVA: 0x672dbcc VA: 0x7598d45bcc
	internal static ECPoint ImplShamirsTrickWNaf(ECPoint P, BigInteger k, ECPointMap pointMapQ, BigInteger l) { }
	// RVA: 0x672d910 VA: 0x7598d45910
	private static ECPoint ImplShamirsTrickWNaf(ECPoint[] preCompP, ECPoint[] preCompNegP, Byte[] wnafP, ECPoint[] preCompQ, ECPoint[] preCompNegQ, Byte[] wnafQ) { }
	// RVA: 0x672c9fc VA: 0x7598d449fc
	internal static ECPoint ImplSumOfMultiplies(ECPoint[] ps, BigInteger[] ks) { }
	// RVA: 0x672c4e4 VA: 0x7598d444e4
	internal static ECPoint ImplSumOfMultipliesGlv(ECPoint[] ps, BigInteger[] ks, GlvEndomorphism glvEndomorphism) { }
	// RVA: 0x672e12c VA: 0x7598d4612c
	internal static ECPoint ImplSumOfMultiplies(ECPoint[] ps, ECPointMap pointMap, BigInteger[] ks) { }
	// RVA: 0x672de24 VA: 0x7598d45e24
	private static ECPoint ImplSumOfMultiplies(Boolean[] negs, WNafPreCompInfo[] infos, Byte[][] wnafs) { }
	// RVA: 0x672e558 VA: 0x7598d46558
	public Void .ctor() { }
}
```