# ComicBook

**Namespace:** `Colorful`


## Fields

- `Single StripAngle`

- `Single StripDensity`

- `Single StripThickness`

- `Vector2 StripLimits`

- `Color StripInnerColor`

- `Color StripOuterColor`

- `Color FillColor`

- `Color BackgroundColor`

- `Boolean EdgeDetection`

- `Single EdgeThreshold`

- `Color EdgeColor`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ComicBook : BaseEffect
{
	public Single StripAngle; // 0x28
	public Single StripDensity; // 0x2c
	public Single StripThickness; // 0x30
	public Vector2 StripLimits; // 0x34
	public Color StripInnerColor; // 0x3c
	public Color StripOuterColor; // 0x4c
	public Color FillColor; // 0x5c
	public Color BackgroundColor; // 0x6c
	public Boolean EdgeDetection; // 0x7c
	public Single EdgeThreshold; // 0x80
	public Color EdgeColor; // 0x84
	public Single Amount; // 0x94


	// RVA: 0x34e8e38 VA: 0x7595b00e38
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e90e0 VA: 0x7595b010e0
	protected override String GetShaderName() { }
	// RVA: 0x34e9120 VA: 0x7595b01120
	public Void .ctor() { }
}
```