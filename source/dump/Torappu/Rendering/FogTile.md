# FogTile

**Namespace:** `Torappu.Rendering`


## Fields

- `MaterialPropertyBlock m_materialPB`

- `Renderer m_renderer`

- `Int32 m_propID`

- `Color m_targetColor`

- `Color m_color`

- `Tween m_colorTween`


## Methods

- `Void Awake()`

- `Void GetComponentIfNot()`

- `Void _FinishTweenIfNot()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class FogTile : HighlightTileBase`1
{
	private MaterialPropertyBlock m_materialPB; // 0x20
	private Renderer m_renderer; // 0x28
	private Int32 m_propID; // 0x30
	private Color m_targetColor; // 0x34
	private Color m_color; // 0x44
	private Tween m_colorTween; // 0x58


	// RVA: 0x3f064f0 VA: 0x759651e4f0
	public override Void SwitchHighlightLevel(Int32 level) { }
	// RVA: 0x3f06884 VA: 0x759651e884
	private Void Awake() { }
	// RVA: 0x3f06778 VA: 0x759651e778
	private Void GetComponentIfNot() { }
	// RVA: 0x3f06738 VA: 0x759651e738
	private Void _FinishTweenIfNot() { }
	// RVA: 0x3f06888 VA: 0x759651e888
	private Void OnDestroy() { }
	// RVA: 0x3f0688c VA: 0x759651e88c
	public Void .ctor() { }
}
```