# VWallGenerator

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Material _wallMaterial`

- `Single _paddingX`

- `Single _paddingY`

- `MeshFilter m_meshFilter`

- `MeshRenderer m_meshRenderer`

- `EasyMeshGenerator m_generator`


## Properties

- `Boolean isEnabled`


## Methods

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Void Generate(List`1, Rect)`

- `Mesh _CreateMesh(IList`1, Rect)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VWallGenerator : MonoBehaviour
{
	private Material _wallMaterial; // 0x18
	private Single _paddingX; // 0x20
	private Single _paddingY; // 0x24
	private MeshFilter m_meshFilter; // 0x28
	private MeshRenderer m_meshRenderer; // 0x30
	private EasyMeshGenerator m_generator; // 0x38

	public Boolean isEnabled { get; set; }

	// RVA: 0x3d03c40 VA: 0x759631bc40
	public Boolean get_isEnabled() { }
	// RVA: 0x3d03c60 VA: 0x759631bc60
	private Void set_isEnabled(Boolean value) { }
	// RVA: 0x3d035b4 VA: 0x759631b5b4
	public Void Generate(List`1 layout, Rect boundingBox) { }
	// RVA: 0x3d0439c VA: 0x759631c39c
	private Mesh _CreateMesh(IList`1 bounds, Rect boundingBox) { }
	// RVA: 0x3d03cec VA: 0x759631bcec
	private List`1 _GenerateEmptySlots(List`1 layout, Rect boundingBox) { }
	// RVA: 0x3d0463c VA: 0x759631c63c
	private Void Awake() { }
	// RVA: 0x3d046d8 VA: 0x759631c6d8
	public Void .ctor() { }
}
```