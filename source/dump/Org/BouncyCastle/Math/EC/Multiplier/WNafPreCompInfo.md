# WNafPreCompInfo

**Namespace:** `Org.BouncyCastle.Math.EC.Multiplier`


## Fields

- `ECPoint m_twice`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Multiplier
public class WNafPreCompInfo : PreCompInfo
{
	protected ECPoint[] m_preComp; // 0x10
	protected ECPoint[] m_preCompNeg; // 0x18
	protected ECPoint m_twice; // 0x20

	public virtual ECPoint[] PreComp { get; set; }
	public virtual ECPoint[] PreCompNeg { get; set; }
	public virtual ECPoint Twice { get; set; }

	// RVA: 0x6742a80 VA: 0x7598d5aa80
	public virtual ECPoint[] get_PreComp() { }
	// RVA: 0x6742a88 VA: 0x7598d5aa88
	public virtual Void set_PreComp(ECPoint[] value) { }
	// RVA: 0x6742a90 VA: 0x7598d5aa90
	public virtual ECPoint[] get_PreCompNeg() { }
	// RVA: 0x6742a98 VA: 0x7598d5aa98
	public virtual Void set_PreCompNeg(ECPoint[] value) { }
	// RVA: 0x6742aa0 VA: 0x7598d5aaa0
	public virtual ECPoint get_Twice() { }
	// RVA: 0x6742aa8 VA: 0x7598d5aaa8
	public virtual Void set_Twice(ECPoint value) { }
	// RVA: 0x6742ab0 VA: 0x7598d5aab0
	public Void .ctor() { }
}
```