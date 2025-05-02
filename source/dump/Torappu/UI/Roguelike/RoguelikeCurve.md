# RoguelikeCurve

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _startNode`

- `RectTransform _endNode`

- `Vector2 _startPosOffset`

- `Vector2 _endPosOffset`

- `Int32 _segment`

- `Single _width`

- `Single _degreeX`

- `Single _degreeY`

- `Single _startRoundCorner`

- `Single _endRoundCorner`

- `Boolean _useClipColor`

- `Single _clipRatio`

- `Color _clipColor`

- `Single _reflectOffsetY`

- `Single _reflectWidthRatio`

- `Color _reflectColor`

- `Vector3 m_startPos`

- `Vector3 m_endPos`


## Properties

- `RectTransform startNode`

- `RectTransform endNode`

- `Boolean useClipColor`

- `Color clipColor`

- `Color reflectColor`


## Methods

- `RectTransform get_startNode()`

- `Void set_startNode(RectTransform)`

- `RectTransform get_endNode()`

- `Void set_endNode(RectTransform)`

- `Boolean get_useClipColor()`

- `Void set_useClipColor(Boolean)`

- `Color get_clipColor()`

- `Void set_clipColor(Color)`

- `Color get_reflectColor()`

- `Void set_reflectColor(Color)`

- `Void _GenerateCurve()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCurve : MaskableGraphic, IHotfixable
{
	private RectTransform _startNode; // 0xe0
	private RectTransform _endNode; // 0xe8
	private Vector2 _startPosOffset; // 0xf0
	private Vector2 _endPosOffset; // 0xf8
	private Int32 _segment; // 0x100
	private Single _width; // 0x104
	private Single _degreeX; // 0x108
	private Single _degreeY; // 0x10c
	private Single _startRoundCorner; // 0x110
	private Single _endRoundCorner; // 0x114
	private Boolean _useClipColor; // 0x118
	private Single _clipRatio; // 0x11c
	private Color _clipColor; // 0x120
	private Single _reflectOffsetY; // 0x130
	private Single _reflectWidthRatio; // 0x134
	private Color _reflectColor; // 0x138
	private List`1 m_vertices; // 0x148
	private List`1 m_tris; // 0x150
	private Vector3 m_startPos; // 0x158
	private Vector3 m_endPos; // 0x164
	private static DelegateBridge __Hotfix0_get_startNode; // 0x0
	private static DelegateBridge __Hotfix0_set_startNode; // 0x8
	private static DelegateBridge __Hotfix0_get_endNode; // 0x10
	private static DelegateBridge __Hotfix0_set_endNode; // 0x18
	private static DelegateBridge __Hotfix0_get_useClipColor; // 0x20
	private static DelegateBridge __Hotfix0_set_useClipColor; // 0x28
	private static DelegateBridge __Hotfix0_get_clipColor; // 0x30
	private static DelegateBridge __Hotfix0_set_clipColor; // 0x38
	private static DelegateBridge __Hotfix0_get_reflectColor; // 0x40
	private static DelegateBridge __Hotfix0_set_reflectColor; // 0x48
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x50
	private static DelegateBridge __Hotfix0__GenerateCurve; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public RectTransform startNode { get; set; }
	public RectTransform endNode { get; set; }
	public Boolean useClipColor { get; set; }
	public Color clipColor { get; set; }
	public Color reflectColor { get; set; }

	// RVA: 0x2a1b410 VA: 0x7595033410
	public RectTransform get_startNode() { }
	// RVA: 0x2a1b478 VA: 0x7595033478
	public Void set_startNode(RectTransform value) { }
	// RVA: 0x2a1b510 VA: 0x7595033510
	public RectTransform get_endNode() { }
	// RVA: 0x2a1b578 VA: 0x7595033578
	public Void set_endNode(RectTransform value) { }
	// RVA: 0x2a1b610 VA: 0x7595033610
	public Boolean get_useClipColor() { }
	// RVA: 0x2a1b678 VA: 0x7595033678
	public Void set_useClipColor(Boolean value) { }
	// RVA: 0x2a1b6f8 VA: 0x75950336f8
	public Color get_clipColor() { }
	// RVA: 0x2a1b768 VA: 0x7595033768
	public Void set_clipColor(Color value) { }
	// RVA: 0x2a1b814 VA: 0x7595033814
	public Color get_reflectColor() { }
	// RVA: 0x2a1b884 VA: 0x7595033884
	public Void set_reflectColor(Color value) { }
	// RVA: 0x2a1b930 VA: 0x7595033930
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2a1e564 VA: 0x7595036564
	private Void _GenerateCurve() { }
	// RVA: 0x2a1ed08 VA: 0x7595036d08
	public Void Update() { }
	// RVA: 0x2a1ed6c VA: 0x7595036d6c
	public Void .ctor() { }
	// RVA: 0x2a1eec0 VA: 0x7595036ec0
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```