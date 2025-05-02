# UIOutlineExpand

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_outlineWidth`

- `Material m_currMat`

- `String m_currShader`


## Properties

- `Boolean hasSetMaterial`


## Methods

- `Void _ModifyShaderChannels()`

- `Boolean get_hasSetMaterial()`

- `Void _Refresh()`

- `Void _SaveCurrMatInfo()`

- `Void _ProcessVertices()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIOutlineExpand : BaseMeshEffect
{
	private static readonly String[] OUTLINE_SHADERS; // 0x0
	private Int32 m_outlineWidth; // 0x20
	private Material m_currMat; // 0x28
	private String m_currShader; // 0x30
	private static List`1 m_VetexList; // 0x8

	private Boolean hasSetMaterial { get; }

	// RVA: 0x21ee2dc VA: 0x75948062dc
	protected override Void Awake() { }
	// RVA: 0x21ee584 VA: 0x7594806584
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x21ee2f4 VA: 0x75948062f4
	private Void _ModifyShaderChannels() { }
	// RVA: 0x21ee588 VA: 0x7594806588
	private Boolean get_hasSetMaterial() { }
	// RVA: 0x21ee45c VA: 0x759480645c
	private Void _Refresh() { }
	// RVA: 0x21ee634 VA: 0x7594806634
	private Void _SaveCurrMatInfo() { }
	// RVA: 0x21ee6a8 VA: 0x75948066a8
	public override Void ModifyMesh(VertexHelper vh) { }
	// RVA: 0x21ee768 VA: 0x7594806768
	private Void _ProcessVertices() { }
	// RVA: 0x21ef280 VA: 0x7594807280
	private static UIVertex _SetNewPosAndUV(UIVertex pVertex, Int32 pOutLineWidth, Vector2 pPosCenter, Vector2 pTriangleX, Vector2 pTriangleY, Vector2 pUVX, Vector2 pUVY, Vector4 pUVOrigin) { }
	// RVA: 0x21ef120 VA: 0x7594807120
	private static Single _Min(Single pA, Single pB, Single pC) { }
	// RVA: 0x21ef134 VA: 0x7594807134
	private static Single _Max(Single pA, Single pB, Single pC) { }
	// RVA: 0x21ef148 VA: 0x7594807148
	private static Vector2 _Min(Vector2 pA, Vector2 pB, Vector2 pC) { }
	// RVA: 0x21ef1e4 VA: 0x75948071e4
	private static Vector2 _Max(Vector2 pA, Vector2 pB, Vector2 pC) { }
	// RVA: 0x21ef4ec VA: 0x75948074ec
	public Void .ctor() { }
	// RVA: 0x21ef4f4 VA: 0x75948074f4
	private static Void .cctor() { }
}
```