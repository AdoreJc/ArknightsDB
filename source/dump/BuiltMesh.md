# BuiltMesh

**Namespace:** ` `


## Methods

- `Void set_vertices(List`1)`

- `Void set_uv0(List`1)`

- `Void set_uv1(List`1)`

- `Void set_triangles(List`1)`

- `Void set_colors(List`1)`

- `Void set_normals(List`1)`

- `Void set_tangents(List`1)`

- `Void Reset()`

- `Void PopulateMesh(Mesh)`

- `Void FromMesh(Mesh)`

- `Void AddVert(Vector3, Vector2, Vector2, Color32)`

- `Void AddVert(Vector3, Vector2, Vector2, Color32, Vector3, Vector4)`

- `Boolean CalcTriangleCenter(Int32, Int32, Int32, out)`

- `Boolean HasVerticeProperty(IList)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class BuiltMesh
{
	private List`1 <vertices>k__BackingField; // 0x10
	private List`1 <uv0>k__BackingField; // 0x18
	private List`1 <uv1>k__BackingField; // 0x20
	private List`1 <triangles>k__BackingField; // 0x28
	private List`1 <colors>k__BackingField; // 0x30
	private List`1 <normals>k__BackingField; // 0x38
	private List`1 <tangents>k__BackingField; // 0x40

	public List`1 vertices { get; set; }
	public List`1 uv0 { get; set; }
	public List`1 uv1 { get; set; }
	public List`1 triangles { get; set; }
	public List`1 colors { get; set; }
	public List`1 normals { get; set; }
	public List`1 tangents { get; set; }

	// RVA: 0x67a2334 VA: 0x7598dba334
	public List`1 get_vertices() { }
	// RVA: 0x67a233c VA: 0x7598dba33c
	private Void set_vertices(List`1 value) { }
	// RVA: 0x67a2344 VA: 0x7598dba344
	public List`1 get_uv0() { }
	// RVA: 0x67a234c VA: 0x7598dba34c
	private Void set_uv0(List`1 value) { }
	// RVA: 0x67a2354 VA: 0x7598dba354
	public List`1 get_uv1() { }
	// RVA: 0x67a235c VA: 0x7598dba35c
	private Void set_uv1(List`1 value) { }
	// RVA: 0x67a2364 VA: 0x7598dba364
	public List`1 get_triangles() { }
	// RVA: 0x67a236c VA: 0x7598dba36c
	private Void set_triangles(List`1 value) { }
	// RVA: 0x67a2374 VA: 0x7598dba374
	public List`1 get_colors() { }
	// RVA: 0x67a237c VA: 0x7598dba37c
	private Void set_colors(List`1 value) { }
	// RVA: 0x67a2384 VA: 0x7598dba384
	public List`1 get_normals() { }
	// RVA: 0x67a238c VA: 0x7598dba38c
	private Void set_normals(List`1 value) { }
	// RVA: 0x67a2394 VA: 0x7598dba394
	public List`1 get_tangents() { }
	// RVA: 0x67a239c VA: 0x7598dba39c
	private Void set_tangents(List`1 value) { }
	// RVA: 0x67a23a4 VA: 0x7598dba3a4
	public Void .ctor() { }
	// RVA: 0x67a2088 VA: 0x7598dba088
	public Void Reset() { }
	// RVA: 0x679ca00 VA: 0x7598db4a00
	public Void PopulateMesh(Mesh mesh) { }
	// RVA: 0x679cd74 VA: 0x7598db4d74
	public Void FromMesh(Mesh mesh) { }
	// RVA: 0x679fb74 VA: 0x7598db7b74
	public Void AddVert(Vector3 vert, Vector2 uv0, Vector2 uv1, Color32 color) { }
	// RVA: 0x679d9d8 VA: 0x7598db59d8
	public Void AddVert(Vector3 vert, Vector2 uv0, Vector2 uv1, Color32 color, Vector3 normal, Vector4 tangent) { }
	// RVA: 0x67a25cc VA: 0x7598dba5cc
	public Boolean CalcTriangleCenter(Int32 v1, Int32 v2, Int32 v3, out Vector3 center) { }
	// RVA: 0x679d6dc VA: 0x7598db56dc
	public Boolean HasVerticeProperty(IList propList) { }
}
```