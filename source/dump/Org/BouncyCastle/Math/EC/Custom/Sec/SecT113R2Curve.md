# SecT113R2Curve

**Namespace:** `Org.BouncyCastle.Math.EC.Custom.Sec`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Custom.Sec
internal class SecT113R2Curve : AbstractF2mCurve
{
	private const Int32 SecT113R2_DEFAULT_COORDS; // 0x0
	protected readonly SecT113R2Point m_infinity; // 0x58

	public override ECPoint Infinity { get; }
	public override Int32 FieldSize { get; }
	public override Boolean IsKoblitz { get; }
	public virtual Int32 M { get; }
	public virtual Boolean IsTrinomial { get; }
	public virtual Int32 K1 { get; }
	public virtual Int32 K2 { get; }
	public virtual Int32 K3 { get; }

	// RVA: 0x64a3bb8 VA: 0x7598abbbb8
	public Void .ctor() { }
	// RVA: 0x64a3df8 VA: 0x7598abbdf8
	protected override ECCurve CloneCurve() { }
	// RVA: 0x64a3e50 VA: 0x7598abbe50
	public override Boolean SupportsCoordinateSystem(Int32 coord) { }
	// RVA: 0x64a3e5c VA: 0x7598abbe5c
	public override ECPoint get_Infinity() { }
	// RVA: 0x64a3e64 VA: 0x7598abbe64
	public override Int32 get_FieldSize() { }
	// RVA: 0x64a3e6c VA: 0x7598abbe6c
	public override ECFieldElement FromBigInteger(BigInteger x) { }
	// RVA: 0x64a3ecc VA: 0x7598abbecc
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, Boolean withCompression) { }
	// RVA: 0x64a3fe0 VA: 0x7598abbfe0
	protected internal override ECPoint CreateRawPoint(ECFieldElement x, ECFieldElement y, ECFieldElement[] zs, Boolean withCompression) { }
	// RVA: 0x64a4080 VA: 0x7598abc080
	public override Boolean get_IsKoblitz() { }
	// RVA: 0x64a4088 VA: 0x7598abc088
	public virtual Int32 get_M() { }
	// RVA: 0x64a4090 VA: 0x7598abc090
	public virtual Boolean get_IsTrinomial() { }
	// RVA: 0x64a4098 VA: 0x7598abc098
	public virtual Int32 get_K1() { }
	// RVA: 0x64a40a0 VA: 0x7598abc0a0
	public virtual Int32 get_K2() { }
	// RVA: 0x64a40a8 VA: 0x7598abc0a8
	public virtual Int32 get_K3() { }
}
```