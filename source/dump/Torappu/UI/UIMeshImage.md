# UIMeshImage

**Namespace:** `Torappu.UI`


## Fields

- `Texture _targetTexture`

- `Mesh _targetMesh`

- `Boolean _matchRect`

- `Boolean _matchByWidth`

- `Vector3 _targetRotation`

- `Boolean m_inited`

- `Vector3 m_origMeshScale`

- `Single m_cachedMatch`

- `Single m_scaleRatio`

- `Texture m_activeTexture`


## Methods

- `Void SetActiveTexture(Texture)`

- `Void _InitIfNot()`

- `Void _SetMeshScale()`

- `Void _MatchMeshWithRectTransform()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMeshImage : MaskableGraphic
{
	private Texture _targetTexture; // 0xe0
	private Mesh _targetMesh; // 0xe8
	private Boolean _matchRect; // 0xf0
	private Boolean _matchByWidth; // 0xf1
	private Vector3 _targetRotation; // 0xf4
	private Boolean m_inited; // 0x100
	private Vector3 m_origMeshScale; // 0x104
	private Single m_cachedMatch; // 0x110
	private Single m_scaleRatio; // 0x114
	private Texture m_activeTexture; // 0x118

	public override Texture mainTexture { get; }

	// RVA: 0x21ed6d4 VA: 0x75948056d4
	public override Texture get_mainTexture() { }
	// RVA: 0x21ed6dc VA: 0x75948056dc
	protected override Void OnEnable() { }
	// RVA: 0x21ed74c VA: 0x759480574c
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x21ede40 VA: 0x7594805e40
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x21edfe0 VA: 0x7594805fe0
	public Void SetActiveTexture(Texture texture) { }
	// RVA: 0x21ed6f8 VA: 0x75948056f8
	private Void _InitIfNot() { }
	// RVA: 0x21ee00c VA: 0x759480600c
	private Void _SetMeshScale() { }
	// RVA: 0x21ede74 VA: 0x7594805e74
	private Void _MatchMeshWithRectTransform() { }
	// RVA: 0x21ee170 VA: 0x7594806170
	public Void .ctor() { }
}
```