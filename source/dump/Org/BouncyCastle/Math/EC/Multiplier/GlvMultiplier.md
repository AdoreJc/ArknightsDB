# GlvMultiplier

**Namespace:** `Org.BouncyCastle.Math.EC.Multiplier`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Multiplier
public class GlvMultiplier : AbstractECMultiplier
{
	protected readonly ECCurve curve; // 0x10
	protected readonly GlvEndomorphism glvEndomorphism; // 0x18


	// RVA: 0x672e974 VA: 0x7598d46974
	public Void .ctor(ECCurve curve, GlvEndomorphism glvEndomorphism) { }
	// RVA: 0x6741960 VA: 0x7598d59960
	protected override ECPoint MultiplyPositive(ECPoint p, BigInteger k) { }
}
```