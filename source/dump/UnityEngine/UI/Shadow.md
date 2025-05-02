# Shadow

**Namespace:** `UnityEngine.UI`


## Fields

- `Color m_EffectColor`

- `Vector2 m_EffectDistance`

- `Boolean m_UseGraphicAlpha`


## Properties

- `Color effectColor`

- `Vector2 effectDistance`

- `Boolean useGraphicAlpha`


## Methods

- `Color get_effectColor()`

- `Void set_effectColor(Color)`

- `Vector2 get_effectDistance()`

- `Void set_effectDistance(Vector2)`

- `Boolean get_useGraphicAlpha()`

- `Void set_useGraphicAlpha(Boolean)`

- `Void ApplyShadowZeroAlloc(List`1, Color32, Int32, Int32, Single, Single)`

- `Void ApplyShadow(List`1, Color32, Int32, Int32, Single, Single)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Shadow : BaseMeshEffect
{
	private Color m_EffectColor; // 0x20
	private Vector2 m_EffectDistance; // 0x30
	private Boolean m_UseGraphicAlpha; // 0x38
	private const Single kMaxEffectDistance; // 0x0

	public Color effectColor { get; set; }
	public Vector2 effectDistance { get; set; }
	public Boolean useGraphicAlpha { get; set; }

	// RVA: 0x6a71678 VA: 0x7599089678
	protected Void .ctor() { }
	// RVA: 0x6a716a0 VA: 0x75990896a0
	public Color get_effectColor() { }
	// RVA: 0x6a716ac VA: 0x75990896ac
	public Void set_effectColor(Color value) { }
	// RVA: 0x6a71780 VA: 0x7599089780
	public Vector2 get_effectDistance() { }
	// RVA: 0x6a71788 VA: 0x7599089788
	public Void set_effectDistance(Vector2 value) { }
	// RVA: 0x6a7188c VA: 0x759908988c
	public Boolean get_useGraphicAlpha() { }
	// RVA: 0x6a71894 VA: 0x7599089894
	public Void set_useGraphicAlpha(Boolean value) { }
	// RVA: 0x6a7194c VA: 0x759908994c
	protected Void ApplyShadowZeroAlloc(List`1 verts, Color32 color, Int32 start, Int32 end, Single x, Single y) { }
	// RVA: 0x6a71c58 VA: 0x7599089c58
	protected Void ApplyShadow(List`1 verts, Color32 color, Int32 start, Int32 end, Single x, Single y) { }
	// RVA: 0x6a71c60 VA: 0x7599089c60
	public override Void ModifyMesh(VertexHelper vh) { }
}
```