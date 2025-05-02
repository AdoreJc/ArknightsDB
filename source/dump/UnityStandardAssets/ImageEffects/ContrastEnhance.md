# ContrastEnhance

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single intensity`

- `Single threshold`

- `Material separableBlurMaterial`

- `Material contrastCompositeMaterial`

- `Single blurSpread`

- `Shader separableBlurShader`

- `Shader contrastCompositeShader`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ContrastEnhance : PostEffectsBase
{
	public Single intensity; // 0x28
	public Single threshold; // 0x2c
	private Material separableBlurMaterial; // 0x30
	private Material contrastCompositeMaterial; // 0x38
	public Single blurSpread; // 0x40
	public Shader separableBlurShader; // 0x48
	public Shader contrastCompositeShader; // 0x50


	// RVA: 0x6477a6c VA: 0x7598a8fa6c
	public override Boolean CheckResources() { }
	// RVA: 0x6477b08 VA: 0x7598a8fb08
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6477e34 VA: 0x7598a8fe34
	public Void .ctor() { }
}
```