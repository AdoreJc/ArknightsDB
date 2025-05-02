# GlvTypeBParameters

**Namespace:** `Org.BouncyCastle.Math.EC.Endo`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Endo
public class GlvTypeBParameters
{
	protected readonly BigInteger m_beta; // 0x10
	protected readonly BigInteger m_lambda; // 0x18
	protected readonly BigInteger[] m_v1; // 0x20
	protected readonly BigInteger[] m_v2; // 0x28
	protected readonly BigInteger m_g1; // 0x30
	protected readonly BigInteger m_g2; // 0x38
	protected readonly Int32 m_bits; // 0x40

	public virtual BigInteger Beta { get; }
	public virtual BigInteger Lambda { get; }
	public virtual BigInteger[] V1 { get; }
	public virtual BigInteger[] V2 { get; }
	public virtual BigInteger G1 { get; }
	public virtual BigInteger G2 { get; }
	public virtual Int32 Bits { get; }

	// RVA: 0x647c634 VA: 0x7598a94634
	public Void .ctor(BigInteger beta, BigInteger lambda, BigInteger[] v1, BigInteger[] v2, BigInteger g1, BigInteger g2, Int32 bits) { }
	// RVA: 0x647c6ec VA: 0x7598a946ec
	public virtual BigInteger get_Beta() { }
	// RVA: 0x647c6f4 VA: 0x7598a946f4
	public virtual BigInteger get_Lambda() { }
	// RVA: 0x647c6fc VA: 0x7598a946fc
	public virtual BigInteger[] get_V1() { }
	// RVA: 0x647c704 VA: 0x7598a94704
	public virtual BigInteger[] get_V2() { }
	// RVA: 0x647c70c VA: 0x7598a9470c
	public virtual BigInteger get_G1() { }
	// RVA: 0x647c714 VA: 0x7598a94714
	public virtual BigInteger get_G2() { }
	// RVA: 0x647c71c VA: 0x7598a9471c
	public virtual Int32 get_Bits() { }
}
```