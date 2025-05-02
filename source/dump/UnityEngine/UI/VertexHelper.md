# VertexHelper

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_ListsInitalized`


## Properties

- `Int32 currentVertCount`

- `Int32 currentIndexCount`


## Methods

- `Void InitializeListIfRequired()`

- `Void Dispose()`

- `Void Clear()`

- `Int32 get_currentVertCount()`

- `Int32 get_currentIndexCount()`

- `Void PopulateUIVertex(ref, Int32)`

- `Void SetUIVertex(UIVertex, Int32)`

- `Void FillMesh(Mesh)`

- `Void AddVert(Vector3, Color32, Vector4, Vector4, Vector4, Vector4, Vector3, Vector4)`

- `Void AddVert(Vector3, Color32, Vector4, Vector4, Vector3, Vector4)`

- `Void AddVert(Vector3, Color32, Vector4)`

- `Void AddVert(UIVertex)`

- `Void AddTriangle(Int32, Int32, Int32)`

- `Void AddUIVertexQuad(UIVertex[])`

- `Void AddUIVertexStream(List`1, List`1)`

- `Void AddUIVertexTriangleStream(List`1)`

- `Void GetUIVertexStream(List`1)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class VertexHelper : IDisposable
{
	private List`1 m_Positions; // 0x10
	private List`1 m_Colors; // 0x18
	private List`1 m_Uv0S; // 0x20
	private List`1 m_Uv1S; // 0x28
	private List`1 m_Uv2S; // 0x30
	private List`1 m_Uv3S; // 0x38
	private List`1 m_Normals; // 0x40
	private List`1 m_Tangents; // 0x48
	private List`1 m_Indices; // 0x50
	private static readonly Vector4 s_DefaultTangent; // 0x0
	private static readonly Vector3 s_DefaultNormal; // 0x10
	private Boolean m_ListsInitalized; // 0x58

	public Int32 currentVertCount { get; }
	public Int32 currentIndexCount { get; }

	// RVA: 0x6a6e14c VA: 0x759908614c
	public Void .ctor() { }
	// RVA: 0x6a6e154 VA: 0x7599086154
	public Void .ctor(Mesh m) { }
	// RVA: 0x6a6e38c VA: 0x759908638c
	private Void InitializeListIfRequired() { }
	// RVA: 0x6a6e588 VA: 0x7599086588
	public Void Dispose() { }
	// RVA: 0x6a5db04 VA: 0x7599075b04
	public Void Clear() { }
	// RVA: 0x6a6e7f0 VA: 0x75990867f0
	public Int32 get_currentVertCount() { }
	// RVA: 0x6a6e83c VA: 0x759908683c
	public Int32 get_currentIndexCount() { }
	// RVA: 0x6a6e888 VA: 0x7599086888
	public Void PopulateUIVertex(ref UIVertex vertex, Int32 i) { }
	// RVA: 0x6a6e9e8 VA: 0x75990869e8
	public Void SetUIVertex(UIVertex vertex, Int32 i) { }
	// RVA: 0x6a6eb44 VA: 0x7599086b44
	public Void FillMesh(Mesh mesh) { }
	// RVA: 0x6a6eca8 VA: 0x7599086ca8
	public Void AddVert(Vector3 position, Color32 color, Vector4 uv0, Vector4 uv1, Vector4 uv2, Vector4 uv3, Vector3 normal, Vector4 tangent) { }
	// RVA: 0x6a6f1a4 VA: 0x75990871a4
	public Void AddVert(Vector3 position, Color32 color, Vector4 uv0, Vector4 uv1, Vector3 normal, Vector4 tangent) { }
	// RVA: 0x6a5dc20 VA: 0x7599075c20
	public Void AddVert(Vector3 position, Color32 color, Vector4 uv0) { }
	// RVA: 0x6a6f2b4 VA: 0x75990872b4
	public Void AddVert(UIVertex v) { }
	// RVA: 0x6a5dd50 VA: 0x7599075d50
	public Void AddTriangle(Int32 idx0, Int32 idx1, Int32 idx2) { }
	// RVA: 0x6a6ae74 VA: 0x7599082e74
	public Void AddUIVertexQuad(UIVertex[] verts) { }
	// RVA: 0x6a6f348 VA: 0x7599087348
	public Void AddUIVertexStream(List`1 verts, List`1 indices) { }
	// RVA: 0x6a6f3f4 VA: 0x75990873f4
	public Void AddUIVertexTriangleStream(List`1 verts) { }
	// RVA: 0x6a6f444 VA: 0x7599087444
	public Void GetUIVertexStream(List`1 stream) { }
	// RVA: 0x6a6f494 VA: 0x7599087494
	private static Void .cctor() { }
}
```