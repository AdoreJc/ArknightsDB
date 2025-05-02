# ParticleDetailsHooker

**Namespace:** ` `


## Fields

- `ParticleSystem _particle`

- `Single _detailPercentage`

- `MinMaxCurve m_RateOverTime`

- `Boolean m_HasSavedOrigin`


## Methods

- `Void ApplyLowDetailPS()`

- `Void _RefreshCurveViaPercentage(ref, Single)`

- `Void RevertToHighDetailPS()`

- `Void SaveOrigin()`

- `Boolean CheckValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ParticleDetailsHooker
{
	private ParticleSystem _particle; // 0x10
	private Single _detailPercentage; // 0x18
	private MinMaxCurve m_RateOverTime; // 0x20
	private List`1 m_originBursts; // 0x40
	private Boolean m_HasSavedOrigin; // 0x48


	// RVA: 0x3efd848 VA: 0x7596515848
	public Void ApplyLowDetailPS() { }
	// RVA: 0x3efe248 VA: 0x7596516248
	private Void _RefreshCurveViaPercentage(ref MinMaxCurve curve, Single detailPercentage) { }
	// RVA: 0x3efde14 VA: 0x7596515e14
	public Void RevertToHighDetailPS() { }
	// RVA: 0x3efe048 VA: 0x7596516048
	public Void SaveOrigin() { }
	// RVA: 0x3efd7dc VA: 0x75965157dc
	public Boolean CheckValid() { }
	// RVA: 0x3efe31c VA: 0x759651631c
	public Void .ctor() { }
}
```