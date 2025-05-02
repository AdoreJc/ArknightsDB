# TrailContextData

**Namespace:** ` `


## Fields

- `Camera camera`

- `BakeCache m_cache`

- `BuiltMesh dstMesh`

- `Pools pools`

- `Vector3 externParticleScale`

- `Single externWidthScale`

- `Transform srcTransform`

- `Vector3 renderScale`

- `ParticleSystem system`

- `ParticleSystemRenderer renderer`

- `ColorBySpeedModule colorBySpeed`

- `ColorOverLifetimeModule colorOverLifetime`

- `Boolean enableColorOverLifetime`

- `MinMaxGradient colorOverLifetimeGradient`

- `Boolean enableColorBySpeed`

- `MinMaxGradient colorBySpeedGradient`

- `Boolean use3DSize`

- `Boolean use3DRotation`

- `Boolean isMeshMode`

- `Boolean useWorldSpace`

- `Matrix4x4 worldToCameraMatrix`

- `Matrix4x4 cameraToWorldMatrix`

- `Matrix4x4 localToWorldMatrix`

- `Matrix4x4 worldMatrix`

- `TrailModule trailModule`

- `Ref m_particleArrayRef`

- `LineBuilderData lineBuilderData`


## Properties

- `Int32 particleCount`


## Methods

- `Int32 get_particleCount()`

- `Void _Init(BakeInput, BuiltMesh, Pools)`

- `Void _UpdateStatus()`

- `Void SortParticleIndexByRemainTimeIncreasing(List`1)`

- `Int32 <SortParticleIndexByRemainTimeIncreasing>b__45_0(Int32, Int32)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class TrailContextData
{
	public Camera camera; // 0x10
	private BakeCache m_cache; // 0x18
	public BuiltMesh dstMesh; // 0x20
	public Pools pools; // 0x28
	public Vector3 externParticleScale; // 0x30
	public Single externWidthScale; // 0x3c
	public Transform srcTransform; // 0x40
	public Vector3 renderScale; // 0x48
	public ParticleSystem system; // 0x58
	public ParticleSystemRenderer renderer; // 0x60
	public ColorBySpeedModule colorBySpeed; // 0x68
	public ColorOverLifetimeModule colorOverLifetime; // 0x70
	public Boolean enableColorOverLifetime; // 0x78
	public MinMaxGradient colorOverLifetimeGradient; // 0x80
	public Boolean enableColorBySpeed; // 0xb8
	public MinMaxGradient colorBySpeedGradient; // 0xc0
	public Boolean use3DSize; // 0xf8
	public Boolean use3DRotation; // 0xf9
	public Boolean isMeshMode; // 0xfa
	public Boolean useWorldSpace; // 0xfb
	public Matrix4x4 worldToCameraMatrix; // 0xfc
	public Matrix4x4 cameraToWorldMatrix; // 0x13c
	public Matrix4x4 localToWorldMatrix; // 0x17c
	public Matrix4x4 worldMatrix; // 0x1bc
	public TrailModule trailModule; // 0x200
	private Ref m_particleArrayRef; // 0x208
	public List`1 particleAliveTimePercent; // 0x218
	public List`1 particleRemainLifetime; // 0x220
	public List`1 particlePositions; // 0x228
	public LineBuilderData lineBuilderData; // 0x230
	private Comparison`1 m_sortParticleRemainTimeIncreasing; // 0x238

	public Particle[] particleBuffer { get; }
	public Int32 particleCount { get; }

	// RVA: 0x67a7888 VA: 0x7598dbf888
	public static Void OnRecycle(TrailContextData inst) { }
	// RVA: 0x67a59c8 VA: 0x7598dbd9c8
	public Particle[] get_particleBuffer() { }
	// RVA: 0x67a54e4 VA: 0x7598dbd4e4
	public Int32 get_particleCount() { }
	// RVA: 0x67a792c VA: 0x7598dbf92c
	public static TrailContextData Init(BakeInput input, Pools pools) { }
	// RVA: 0x67a7a0c VA: 0x7598dbfa0c
	private Void _Init(BakeInput input, BuiltMesh dstMesh, Pools pools) { }
	// RVA: 0x67a7f70 VA: 0x7598dbff70
	private Void _UpdateStatus() { }
	// RVA: 0x67a8940 VA: 0x7598dc0940
	private static MinMaxGradient _ReadParticleColorOverLifetime(TrailContextData context) { }
	// RVA: 0x67a898c VA: 0x7598dc098c
	private static MinMaxGradient _ReadParticleColorBySpeed(TrailContextData context) { }
	// RVA: 0x67a89d8 VA: 0x7598dc09d8
	private static MinMaxCurve _ReadParticleStartSize(TrailContextData context) { }
	// RVA: 0x67a8a2c VA: 0x7598dc0a2c
	private static MinMaxCurve _ReadParticleStartSizeX(TrailContextData context) { }
	// RVA: 0x67a8a80 VA: 0x7598dc0a80
	private static MinMaxCurve _ReadParticleStartSizeY(TrailContextData context) { }
	// RVA: 0x67a8ad4 VA: 0x7598dc0ad4
	private static MinMaxCurve _ReadParticleStartSizeZ(TrailContextData context) { }
	// RVA: 0x67a8b28 VA: 0x7598dc0b28
	public Void SortParticleIndexByRemainTimeIncreasing(List`1 outputList) { }
	// RVA: 0x67a8cc4 VA: 0x7598dc0cc4
	public Void .ctor() { }
	// RVA: 0x67a8e44 VA: 0x7598dc0e44
	private Int32 <SortParticleIndexByRemainTimeIncreasing>b__45_0(Int32 lhs, Int32 rhs) { }
}
```