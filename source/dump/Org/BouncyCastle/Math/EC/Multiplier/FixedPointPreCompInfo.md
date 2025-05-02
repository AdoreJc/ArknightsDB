# FixedPointPreCompInfo

**Namespace:** `Org.BouncyCastle.Math.EC.Multiplier`


## Fields

- `Int32 m_width`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Multiplier
public class FixedPointPreCompInfo : PreCompInfo
{
	protected ECPoint[] m_preComp; // 0x10
	protected Int32 m_width; // 0x18

	public virtual ECPoint[] PreComp { get; set; }
	public virtual Int32 Width { get; set; }

	// RVA: 0x6741828 VA: 0x7598d59828
	public virtual ECPoint[] get_PreComp() { }
	// RVA: 0x6741830 VA: 0x7598d59830
	public virtual Void set_PreComp(ECPoint[] value) { }
	// RVA: 0x6741838 VA: 0x7598d59838
	public virtual Int32 get_Width() { }
	// RVA: 0x6741840 VA: 0x7598d59840
	public virtual Void set_Width(Int32 value) { }
	// RVA: 0x6741848 VA: 0x7598d59848
	public Void .ctor() { }
}
```