# Image

**Namespace:** `UnityEngine.UIElements`


## Fields

- `ScaleMode m_ScaleMode`

- `Texture m_Image`

- `Sprite m_Sprite`

- `VectorImage m_VectorImage`

- `Rect m_UV`

- `Color m_TintColor`

- `Boolean m_ImageIsInline`

- `Boolean m_ScaleModeIsInline`

- `Boolean m_TintColorIsInline`


## Properties

- `Texture image`

- `Sprite sprite`

- `VectorImage vectorImage`

- `Rect sourceRect`

- `Rect uv`

- `ScaleMode scaleMode`

- `Color tintColor`


## Methods

- `Texture get_image()`

- `Sprite get_sprite()`

- `VectorImage get_vectorImage()`

- `Rect get_sourceRect()`

- `Rect get_uv()`

- `ScaleMode get_scaleMode()`

- `Color get_tintColor()`

- `Vector2 GetTextureDisplaySize(Texture)`

- `Vector2 GetTextureDisplaySize(Sprite)`

- `Void OnGenerateVisualContent(MeshGenerationContext)`

- `Void OnCustomStyleResolved(CustomStyleResolvedEvent)`

- `Void SetScaleMode(ScaleMode)`

- `Rect GetSourceRect()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Image : VisualElement
{
	private ScaleMode m_ScaleMode; // 0x3b0
	private Texture m_Image; // 0x3b8
	private Sprite m_Sprite; // 0x3c0
	private VectorImage m_VectorImage; // 0x3c8
	private Rect m_UV; // 0x3d0
	private Color m_TintColor; // 0x3e0
	private Boolean m_ImageIsInline; // 0x3f0
	private Boolean m_ScaleModeIsInline; // 0x3f1
	private Boolean m_TintColorIsInline; // 0x3f2
	public static readonly String ussClassName; // 0x0
	private static CustomStyleProperty`1 s_ImageProperty; // 0x8
	private static CustomStyleProperty`1 s_SpriteProperty; // 0x10
	private static CustomStyleProperty`1 s_VectorImageProperty; // 0x18
	private static CustomStyleProperty`1 s_ScaleModeProperty; // 0x20
	private static CustomStyleProperty`1 s_TintColorProperty; // 0x28

	public Texture image { get; }
	public Sprite sprite { get; }
	public VectorImage vectorImage { get; }
	public Rect sourceRect { get; }
	public Rect uv { get; }
	public ScaleMode scaleMode { get; }
	public Color tintColor { get; }

	// RVA: 0x69b054c VA: 0x7598fc854c
	public Texture get_image() { }
	// RVA: 0x69b0554 VA: 0x7598fc8554
	public Sprite get_sprite() { }
	// RVA: 0x69b055c VA: 0x7598fc855c
	public VectorImage get_vectorImage() { }
	// RVA: 0x69b0564 VA: 0x7598fc8564
	public Rect get_sourceRect() { }
	// RVA: 0x69b07ac VA: 0x7598fc87ac
	public Rect get_uv() { }
	// RVA: 0x69b07c0 VA: 0x7598fc87c0
	public ScaleMode get_scaleMode() { }
	// RVA: 0x69b07c8 VA: 0x7598fc87c8
	public Color get_tintColor() { }
	// RVA: 0x69b07dc VA: 0x7598fc87dc
	public Void .ctor() { }
	// RVA: 0x69b09d4 VA: 0x7598fc89d4
	private Vector2 GetTextureDisplaySize(Texture texture) { }
	// RVA: 0x69b0ab0 VA: 0x7598fc8ab0
	private Vector2 GetTextureDisplaySize(Sprite sprite) { }
	// RVA: 0x69b0bb8 VA: 0x7598fc8bb8
	protected internal override Vector2 DoMeasure(Single desiredWidth, MeasureMode widthMode, Single desiredHeight, MeasureMode heightMode) { }
	// RVA: 0x69b0dfc VA: 0x7598fc8dfc
	private Void OnGenerateVisualContent(MeshGenerationContext mgc) { }
	// RVA: 0x69b12e8 VA: 0x7598fc92e8
	private Void OnCustomStyleResolved(CustomStyleResolvedEvent e) { }
	// RVA: 0x69b173c VA: 0x7598fc973c
	private Void SetScaleMode(ScaleMode mode) { }
	// RVA: 0x69b0568 VA: 0x7598fc8568
	private Rect GetSourceRect() { }
	// RVA: 0x69b1760 VA: 0x7598fc9760
	private static Void .cctor() { }
}
```