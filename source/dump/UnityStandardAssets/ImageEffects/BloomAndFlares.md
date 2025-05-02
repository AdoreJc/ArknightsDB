# BloomAndFlares

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `TweakMode34 tweakMode`

- `BloomScreenBlendMode screenBlendMode`

- `HDRBloomMode hdr`

- `Boolean doHdr`

- `Single sepBlurSpread`

- `Single useSrcAlphaAsMask`

- `Single bloomIntensity`

- `Single bloomThreshold`

- `Int32 bloomBlurIterations`

- `Boolean lensflares`

- `Int32 hollywoodFlareBlurIterations`

- `LensflareStyle34 lensflareMode`

- `Single hollyStretchWidth`

- `Single lensflareIntensity`

- `Single lensflareThreshold`

- `Color flareColorA`

- `Color flareColorB`

- `Color flareColorC`

- `Color flareColorD`

- `Texture2D lensFlareVignetteMask`

- `Shader lensFlareShader`

- `Material lensFlareMaterial`

- `Shader vignetteShader`

- `Material vignetteMaterial`

- `Shader separableBlurShader`

- `Material separableBlurMaterial`

- `Shader addBrightStuffOneOneShader`

- `Material addBrightStuffBlendOneOneMaterial`

- `Shader screenBlendShader`

- `Material screenBlend`

- `Shader hollywoodFlaresShader`

- `Material hollywoodFlaresMaterial`

- `Shader brightPassFilterShader`

- `Material brightPassFilterMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void AddTo(Single, RenderTexture, RenderTexture)`

- `Void BlendFlares(RenderTexture, RenderTexture)`

- `Void BrightFilter(Single, Single, RenderTexture, RenderTexture)`

- `Void Vignette(Single, RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class BloomAndFlares : PostEffectsBase
{
	public TweakMode34 tweakMode; // 0x28
	public BloomScreenBlendMode screenBlendMode; // 0x2c
	public HDRBloomMode hdr; // 0x30
	private Boolean doHdr; // 0x34
	public Single sepBlurSpread; // 0x38
	public Single useSrcAlphaAsMask; // 0x3c
	public Single bloomIntensity; // 0x40
	public Single bloomThreshold; // 0x44
	public Int32 bloomBlurIterations; // 0x48
	public Boolean lensflares; // 0x4c
	public Int32 hollywoodFlareBlurIterations; // 0x50
	public LensflareStyle34 lensflareMode; // 0x54
	public Single hollyStretchWidth; // 0x58
	public Single lensflareIntensity; // 0x5c
	public Single lensflareThreshold; // 0x60
	public Color flareColorA; // 0x64
	public Color flareColorB; // 0x74
	public Color flareColorC; // 0x84
	public Color flareColorD; // 0x94
	public Texture2D lensFlareVignetteMask; // 0xa8
	public Shader lensFlareShader; // 0xb0
	private Material lensFlareMaterial; // 0xb8
	public Shader vignetteShader; // 0xc0
	private Material vignetteMaterial; // 0xc8
	public Shader separableBlurShader; // 0xd0
	private Material separableBlurMaterial; // 0xd8
	public Shader addBrightStuffOneOneShader; // 0xe0
	private Material addBrightStuffBlendOneOneMaterial; // 0xe8
	public Shader screenBlendShader; // 0xf0
	private Material screenBlend; // 0xf8
	public Shader hollywoodFlaresShader; // 0x100
	private Material hollywoodFlaresMaterial; // 0x108
	public Shader brightPassFilterShader; // 0x110
	private Material brightPassFilterMaterial; // 0x118


	// RVA: 0x64718c0 VA: 0x7598a898c0
	public override Boolean CheckResources() { }
	// RVA: 0x6471a1c VA: 0x7598a89a1c
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x64727dc VA: 0x7598a8a7dc
	private Void AddTo(Single intensity_, RenderTexture from, RenderTexture to) { }
	// RVA: 0x6472654 VA: 0x7598a8a654
	private Void BlendFlares(RenderTexture from, RenderTexture to) { }
	// RVA: 0x64723fc VA: 0x7598a8a3fc
	private Void BrightFilter(Single thresh, Single useAlphaAsMask, RenderTexture from, RenderTexture to) { }
	// RVA: 0x6472504 VA: 0x7598a8a504
	private Void Vignette(Single amount, RenderTexture from, RenderTexture to) { }
	// RVA: 0x647288c VA: 0x7598a8a88c
	public Void .ctor() { }
}
```