# Bloom

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `TweakMode tweakMode`

- `BloomScreenBlendMode screenBlendMode`

- `HDRBloomMode hdr`

- `Boolean doHdr`

- `Single sepBlurSpread`

- `BloomQuality quality`

- `Single bloomIntensity`

- `Single bloomThreshold`

- `Color bloomThresholdColor`

- `Int32 bloomBlurIterations`

- `Int32 hollywoodFlareBlurIterations`

- `Single flareRotation`

- `LensFlareStyle lensflareMode`

- `Single hollyStretchWidth`

- `Single lensflareIntensity`

- `Single lensflareThreshold`

- `Single lensFlareSaturation`

- `Color flareColorA`

- `Color flareColorB`

- `Color flareColorC`

- `Color flareColorD`

- `Texture2D lensFlareVignetteMask`

- `Shader lensFlareShader`

- `Material lensFlareMaterial`

- `Shader screenBlendShader`

- `Material screenBlend`

- `Shader blurAndFlaresShader`

- `Material blurAndFlaresMaterial`

- `Shader brightPassFilterShader`

- `Material brightPassFilterMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void AddTo(Single, RenderTexture, RenderTexture)`

- `Void BlendFlares(RenderTexture, RenderTexture)`

- `Void BrightFilter(Single, RenderTexture, RenderTexture)`

- `Void BrightFilter(Color, RenderTexture, RenderTexture)`

- `Void Vignette(Single, RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class Bloom : PostEffectsBase
{
	public TweakMode tweakMode; // 0x28
	public BloomScreenBlendMode screenBlendMode; // 0x2c
	public HDRBloomMode hdr; // 0x30
	private Boolean doHdr; // 0x34
	public Single sepBlurSpread; // 0x38
	public BloomQuality quality; // 0x3c
	public Single bloomIntensity; // 0x40
	public Single bloomThreshold; // 0x44
	public Color bloomThresholdColor; // 0x48
	public Int32 bloomBlurIterations; // 0x58
	public Int32 hollywoodFlareBlurIterations; // 0x5c
	public Single flareRotation; // 0x60
	public LensFlareStyle lensflareMode; // 0x64
	public Single hollyStretchWidth; // 0x68
	public Single lensflareIntensity; // 0x6c
	public Single lensflareThreshold; // 0x70
	public Single lensFlareSaturation; // 0x74
	public Color flareColorA; // 0x78
	public Color flareColorB; // 0x88
	public Color flareColorC; // 0x98
	public Color flareColorD; // 0xa8
	public Texture2D lensFlareVignetteMask; // 0xb8
	public Shader lensFlareShader; // 0xc0
	private Material lensFlareMaterial; // 0xc8
	public Shader screenBlendShader; // 0xd0
	private Material screenBlend; // 0xd8
	public Shader blurAndFlaresShader; // 0xe0
	private Material blurAndFlaresMaterial; // 0xe8
	public Shader brightPassFilterShader; // 0xf0
	private Material brightPassFilterMaterial; // 0xf8


	// RVA: 0x6470514 VA: 0x7598a88514
	public override Boolean CheckResources() { }
	// RVA: 0x6470600 VA: 0x7598a88600
	public Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6471770 VA: 0x7598a89770
	private Void AddTo(Single intensity_, RenderTexture from, RenderTexture to) { }
	// RVA: 0x64715d8 VA: 0x7598a895d8
	private Void BlendFlares(RenderTexture from, RenderTexture to) { }
	// RVA: 0x647132c VA: 0x7598a8932c
	private Void BrightFilter(Single thresh, RenderTexture from, RenderTexture to) { }
	// RVA: 0x6471258 VA: 0x7598a89258
	private Void BrightFilter(Color threshColor, RenderTexture from, RenderTexture to) { }
	// RVA: 0x64713ec VA: 0x7598a893ec
	private Void Vignette(Single amount, RenderTexture from, RenderTexture to) { }
	// RVA: 0x6471834 VA: 0x7598a89834
	public Void .ctor() { }
}
```