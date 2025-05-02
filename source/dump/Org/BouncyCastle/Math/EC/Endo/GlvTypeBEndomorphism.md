# GlvTypeBEndomorphism

**Namespace:** `Org.BouncyCastle.Math.EC.Endo`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Endo
public class GlvTypeBEndomorphism : GlvEndomorphism, ECEndomorphism
{
	protected readonly ECCurve m_curve; // 0x10
	protected readonly GlvTypeBParameters m_parameters; // 0x18
	protected readonly ECPointMap m_pointMap; // 0x20

	public virtual ECPointMap PointMap { get; }
	public virtual Boolean HasEfficientPointMap { get; }

	// RVA: 0x647c1d0 VA: 0x7598a941d0
	public Void .ctor(ECCurve curve, GlvTypeBParameters parameters) { }
	// RVA: 0x647c2ac VA: 0x7598a942ac
	public virtual BigInteger[] DecomposeScalar(BigInteger k) { }
	// RVA: 0x647c524 VA: 0x7598a94524
	public virtual ECPointMap get_PointMap() { }
	// RVA: 0x647c52c VA: 0x7598a9452c
	public virtual Boolean get_HasEfficientPointMap() { }
	// RVA: 0x647c534 VA: 0x7598a94534
	protected virtual BigInteger CalculateB(BigInteger k, BigInteger g, Int32 t) { }
}
```