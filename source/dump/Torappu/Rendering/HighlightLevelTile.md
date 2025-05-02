# HighlightLevelTile

**Namespace:** `Torappu.Rendering`


## Fields

- `MeshRenderer m_renderer`

- `MaterialPropertyBlock m_materialPB`

- `Tween m_colorTween`

- `Color m_color`

- `Single m_strength`


## Methods

- `Void Awake()`

- `Void OnDestroy()`

- `Void FinishTweenIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class HighlightLevelTile : HighlightTileBase`1
{
	private static readonly String PROP_STRENGTH; // 0x0
	private static readonly String TINT_COLOR; // 0x8
	private MeshRenderer m_renderer; // 0x20
	private MaterialPropertyBlock m_materialPB; // 0x28
	private Tween m_colorTween; // 0x30
	private Color m_color; // 0x38
	private Single m_strength; // 0x48


	// RVA: 0x3f06ff0 VA: 0x759651eff0
	public Void Awake() { }
	// RVA: 0x3f0715c VA: 0x759651f15c
	public override Void SwitchHighlightLevel(Int32 level) { }
	// RVA: 0x3f073c4 VA: 0x759651f3c4
	public override Void LitOn() { }
	// RVA: 0x3f07428 VA: 0x759651f428
	public override Void LitOff() { }
	// RVA: 0x3f0743c VA: 0x759651f43c
	private Void OnDestroy() { }
	// RVA: 0x3f07384 VA: 0x759651f384
	private Void FinishTweenIfNot() { }
	// RVA: 0x3f07440 VA: 0x759651f440
	public Void .ctor() { }
	// RVA: 0x3f07488 VA: 0x759651f488
	private static Void .cctor() { }
}
```