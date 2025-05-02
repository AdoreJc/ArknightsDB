# ContextData

**Namespace:** ` `


## Fields

- `BuiltMesh dstMesh`

- `BakeCache m_cache`

- `ParticleSystem system`

- `ParticleSystemRenderer renderer`

- `Transform srcTransform`

- `Camera camera`

- `Vector3 externParticleScale`

- `Matrix4x4 worldRotation`

- `Matrix4x4 worldMatrix`

- `Matrix4x4 worldViewMatrix`

- `Matrix4x4 viewMatrix`

- `Matrix4x4 invViewMatrix`

- `Vector3 cameraPos`

- `Vector3 cameraVelocityVS`

- `Vector3 cameraUp`

- `Vector2 minMaxParticleSize`

- `Vector3 xSpan`

- `Vector3 ySpan`

- `Vector3 renderScale`

- `Int32 numUVFrame`

- `Int32 numTilesX`

- `Int32 numTilesY`

- `Single animUScale`

- `Single animVScale`

- `UVChannelFlags animateUVChannels`

- `Boolean animateUVs`

- `Boolean flipUVs`

- `Vector3 bentNormalVector`

- `Single bentNormalFactor`

- `Vector4 minMaxScaleVector`

- `Vector2 minMaxPlaneScale`

- `Vector2 minMaxOrthoSize`

- `Boolean use3DRotation`

- `Boolean use3DSize`

- `UVModule uvModule`

- `Boolean useMesh`

- `Int32 meshCount`

- `Pools pools`

- `Ref m_particleArrayRef`


## Properties

- `Int32 particleCount`


## Methods

- `Int32 get_particleCount()`

- `Boolean IsValid()`

- `Void _Init(BakeInput, BuiltMesh, Pools)`

- `Void _PrepareData()`

- `Single GetParticleUVFrameIndex(Int32)`

- `Mesh GetMesh(Int32)`

- `MinMaxCurve ReadFrameOverTimeWithCache(TextureSheetAnimationModule)`

- `Void PrepareVertBuffer()`

- `Void FlushVertBufferBillboard(Vector3, Vector3, Vector3, Vector3)`

- `Vector3 CalcViewSpaceCenter(Vector3, Vector3, Vector3)`

- `ParticleTriangle MakeBaseTriangle(Int32, Particle)`

- `Void AddParticleTriangleOfDstMesh(ParticleTriangle, Int32, IList`1)`

- `Void SortAndWriteTrianglesToDstMesh()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class ContextData
{
	public BuiltMesh dstMesh; // 0x10
	private BakeCache m_cache; // 0x18
	public ParticleSystem system; // 0x20
	public ParticleSystemRenderer renderer; // 0x28
	public Transform srcTransform; // 0x30
	public Camera camera; // 0x38
	public Vector3 externParticleScale; // 0x40
	public Matrix4x4 worldRotation; // 0x4c
	public Matrix4x4 worldMatrix; // 0x8c
	public Matrix4x4 worldViewMatrix; // 0xcc
	public Matrix4x4 viewMatrix; // 0x10c
	public Matrix4x4 invViewMatrix; // 0x14c
	public Vector3 cameraPos; // 0x18c
	public Vector3 cameraVelocityVS; // 0x198
	public Vector3 cameraUp; // 0x1a4
	public Vector2 minMaxParticleSize; // 0x1b0
	public Vector3 xSpan; // 0x1b8
	public Vector3 ySpan; // 0x1c4
	public Vector3 renderScale; // 0x1d0
	public Int32 numUVFrame; // 0x1dc
	public Int32 numTilesX; // 0x1e0
	public Int32 numTilesY; // 0x1e4
	public Single animUScale; // 0x1e8
	public Single animVScale; // 0x1ec
	public UVChannelFlags animateUVChannels; // 0x1f0
	public Boolean animateUVs; // 0x1f4
	public Boolean flipUVs; // 0x1f5
	public Vector3 bentNormalVector; // 0x1f8
	public Single bentNormalFactor; // 0x204
	public Vector4 minMaxScaleVector; // 0x208
	public Vector2 minMaxPlaneScale; // 0x218
	public Vector2 minMaxOrthoSize; // 0x220
	public Boolean use3DRotation; // 0x228
	public Boolean use3DSize; // 0x229
	public UVModule uvModule; // 0x230
	public Boolean useMesh; // 0x238
	public Int32 meshCount; // 0x23c
	public Mesh[] m_meshBuffer; // 0x240
	public Pools pools; // 0x248
	private Ref m_particleArrayRef; // 0x250
	private List`1 m_vertBuffer; // 0x260
	private Int32[] m_uvOrderBuffer; // 0x268
	private Vector2[] m_uvBuffer; // 0x270
	private Vector4[] m_uv2Buffer; // 0x278
	private LocalGenericPool`1 m_sortInfoPool; // 0x280
	private List`1 m_trianglesToSort; // 0x288

	public Particle[] particleBuffer { get; }
	public Int32 particleCount { get; }

	// RVA: 0x679ccdc VA: 0x7598db4cdc
	public Particle[] get_particleBuffer() { }
	// RVA: 0x679cc90 VA: 0x7598db4c90
	public Int32 get_particleCount() { }
	// RVA: 0x67a2794 VA: 0x7598dba794
	public static Void OnRecycle(ContextData inst) { }
	// RVA: 0x67a29f0 VA: 0x7598dba9f0
	public Boolean IsValid() { }
	// RVA: 0x679a58c VA: 0x7598db258c
	public static ContextData Init(BakeInput input, Pools pools) { }
	// RVA: 0x67a2ab8 VA: 0x7598dbaab8
	private Void _Init(BakeInput input, BuiltMesh dstMesh, Pools pools) { }
	// RVA: 0x67a2bec VA: 0x7598dbabec
	private Void _PrepareData() { }
	// RVA: 0x679d908 VA: 0x7598db5908
	public Single GetParticleUVFrameIndex(Int32 pIndex) { }
	// RVA: 0x679cd28 VA: 0x7598db4d28
	public Mesh GetMesh(Int32 index) { }
	// RVA: 0x67a3b64 VA: 0x7598dbbb64
	public MinMaxCurve ReadFrameOverTimeWithCache(TextureSheetAnimationModule tsaModule) { }
	// RVA: 0x67a3c4c VA: 0x7598dbbc4c
	private static MinMaxCurve _ReadFrameOverTime(TextureSheetAnimationModule tsaModule) { }
	// RVA: 0x679e4a8 VA: 0x7598db64a8
	public Void PrepareVertBuffer() { }
	// RVA: 0x679fdbc VA: 0x7598db7dbc
	public Void FlushVertBufferBillboard(Vector3 v1, Vector3 v2, Vector3 v3, Vector3 v4) { }
	// RVA: 0x67a3c84 VA: 0x7598dbbc84
	public IList`1 GetVertBuffer() { }
	// RVA: 0x679e174 VA: 0x7598db6174
	public Int32[] MakeUVOrderBuffer() { }
	// RVA: 0x679e210 VA: 0x7598db6210
	public Vector2[] MakeUVBuffer() { }
	// RVA: 0x679e35c VA: 0x7598db635c
	public Vector4[] MakeUV2Buffer() { }
	// RVA: 0x67a3c8c VA: 0x7598dbbc8c
	public Vector3 CalcViewSpaceCenter(Vector3 v1WS, Vector3 v2WS, Vector3 v3WS) { }
	// RVA: 0x679d7ac VA: 0x7598db57ac
	public ParticleTriangle MakeBaseTriangle(Int32 index, Particle particle) { }
	// RVA: 0x679dd68 VA: 0x7598db5d68
	public Void AddParticleTriangleOfDstMesh(ParticleTriangle baseTriangle, Int32 offset, IList`1 indexList) { }
	// RVA: 0x679c608 VA: 0x7598db4608
	public Void SortAndWriteTrianglesToDstMesh() { }
	// RVA: 0x67a3cc8 VA: 0x7598dbbcc8
	private static Int32 _ComparisonSortModeNone(TriangleSortInfo lhs, TriangleSortInfo rhs) { }
	// RVA: 0x67a3cec VA: 0x7598dbbcec
	private static Int32 _ComparisonSortModeDistance(TriangleSortInfo lhs, TriangleSortInfo rhs) { }
	// RVA: 0x67a3d54 VA: 0x7598dbbd54
	private static Int32 _ComparisonSortModeYoungestFront(TriangleSortInfo lhs, TriangleSortInfo rhs) { }
	// RVA: 0x67a3dbc VA: 0x7598dbbdbc
	private static Int32 _ComparisonSortModeOldestFront(TriangleSortInfo lhs, TriangleSortInfo rhs) { }
	// RVA: 0x67a3e24 VA: 0x7598dbbe24
	public Void .ctor() { }
}
```