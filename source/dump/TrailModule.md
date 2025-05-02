# TrailModule

**Namespace:** ` `


## Fields

- `TrailContextData m_context`

- `TrailModule trails`

- `ParticleLineParameters lineParams`

- `Int32 trailStripLength`

- `MinMaxGradient colorOverLifetime`

- `MinMaxCurve lifetime`

- `Single minVertexDist`

- `Boolean sizeAffectsLifetime`

- `Single ratio`

- `TrailContext m_trailRecords`


## Methods

- `Void Init(TrailContextData, BakeCache)`

- `Void ReadTrailPositions(Int32, List`1)`

- `Int32 GetTrailCount()`

- `Single CalcTrailLifetime(Int32)`

- `Single MinPointDistance()`

- `Boolean CheckTrailExpired(Int32)`

- `Boolean GetCurrentPosition(Int32, out)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class TrailModule : IHost
{
	private TrailContextData m_context; // 0x10
	public TrailModule trails; // 0x18
	public ParticleLineParameters lineParams; // 0x20
	public Int32 trailStripLength; // 0x98
	public MinMaxGradient colorOverLifetime; // 0xa0
	public MinMaxCurve lifetime; // 0xd8
	public Single minVertexDist; // 0xf8
	public Boolean sizeAffectsLifetime; // 0xfc
	public List`1 lastParticleRemainLifetime; // 0x100
	public Single ratio; // 0x108
	private TrailContext m_trailRecords; // 0x110


	// RVA: 0x67a4fc8 VA: 0x7598dbcfc8
	public Void Init(TrailContextData context, BakeCache nullableCache) { }
	// RVA: 0x67a5530 VA: 0x7598dbd530
	public Void ReadTrailPositions(Int32 index, List`1 output) { }
	// RVA: 0x67a576c VA: 0x7598dbd76c
	public Int32 GetTrailCount() { }
	// RVA: 0x67a57c0 VA: 0x7598dbd7c0
	public Single CalcTrailLifetime(Int32 index) { }
	// RVA: 0x67a5a14 VA: 0x7598dbda14
	public Single MinPointDistance() { }
	// RVA: 0x67a5a1c VA: 0x7598dbda1c
	public Boolean CheckTrailExpired(Int32 index) { }
	// RVA: 0x67a5adc VA: 0x7598dbdadc
	public Boolean GetCurrentPosition(Int32 index, out Vector3 position) { }
	// RVA: 0x67a5cd0 VA: 0x7598dbdcd0
	private static MinMaxCurve _ReadTrailWidth(TrailModule context) { }
	// RVA: 0x67a5d08 VA: 0x7598dbdd08
	private static MinMaxCurve _ReadTrailLifetime(TrailModule context) { }
	// RVA: 0x67a5d40 VA: 0x7598dbdd40
	private static MinMaxGradient _ReadTrailColor(TrailModule context) { }
	// RVA: 0x67a5d8c VA: 0x7598dbdd8c
	private static MinMaxGradient _ReadTrailColorOverLifetime(TrailModule context) { }
	// RVA: 0x67a5dd8 VA: 0x7598dbddd8
	public Void .ctor() { }
}
```