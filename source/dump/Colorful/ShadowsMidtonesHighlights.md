# ShadowsMidtonesHighlights

**Namespace:** `Colorful`


## Fields

- `ColorMode Mode`

- `Color Shadows`

- `Color Midtones`

- `Color Highlights`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class ShadowsMidtonesHighlights : BaseEffect
{
	public ColorMode Mode; // 0x28
	public Color Shadows; // 0x2c
	public Color Midtones; // 0x3c
	public Color Highlights; // 0x4c
	public Single Amount; // 0x5c


	// RVA: 0x34f04d8 VA: 0x7595b084d8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f076c VA: 0x7595b0876c
	protected override String GetShaderName() { }
	// RVA: 0x34f07ac VA: 0x7595b087ac
	public Void .ctor() { }
}
```