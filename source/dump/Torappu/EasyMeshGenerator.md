# EasyMeshGenerator

**Namespace:** `Torappu`


## Methods

- `Void Begin()`

- `Void AddSquare(Bounds)`

- `Void AddSquare(Bounds, Rect)`

- `Void AddSquare(Bounds, Color)`

- `Void AddSquare(Bounds, Rect, Color)`

- `Void AddVertex(Vector3, Vector2, Color)`

- `Void AddTriangle(Int32, Int32, Int32)`

- `Mesh Generate()`

- `Void _ClearAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EasyMeshGenerator
{
	private static readonly Color DEFAULT_COLOR; // 0x0
	private List`1 m_vertices; // 0x10
	private List`1 m_uvs; // 0x18
	private List`1 m_colors; // 0x20
	private List`1 m_indices; // 0x28


	// RVA: 0x2f45cec VA: 0x759555dcec
	public Void Begin() { }
	// RVA: 0x2f45da0 VA: 0x759555dda0
	public Void AddSquare(Bounds bounds) { }
	// RVA: 0x2f45ebc VA: 0x759555debc
	public Void AddSquare(Bounds bounds, Rect uvBounds) { }
	// RVA: 0x2f45e40 VA: 0x759555de40
	public Void AddSquare(Bounds bounds, Color color) { }
	// RVA: 0x2f45f8c VA: 0x759555df8c
	public Void AddSquare(Bounds bounds, Rect uvBounds, Color color) { }
	// RVA: 0x2f461b4 VA: 0x759555e1b4
	public Void AddVertex(Vector3 vertex, Vector2 uv, Color color) { }
	// RVA: 0x2f463ac VA: 0x759555e3ac
	public Void AddTriangle(Int32 a, Int32 b, Int32 c) { }
	// RVA: 0x2f46520 VA: 0x759555e520
	public Mesh Generate() { }
	// RVA: 0x2f45cf0 VA: 0x759555dcf0
	private Void _ClearAll() { }
	// RVA: 0x2f465f0 VA: 0x759555e5f0
	public Void .ctor() { }
	// RVA: 0x2f46768 VA: 0x759555e768
	private static Void .cctor() { }
}
```