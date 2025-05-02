# VignetteAndChromaticAberration

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `AberrationMode mode`

- `Single intensity`

- `Single chromaticAberration`

- `Single axialAberration`

- `Single blur`

- `Single blurSpread`

- `Single luminanceDependency`

- `Single blurDistance`

- `Shader vignetteShader`

- `Shader separableBlurShader`

- `Shader chromAberrationShader`

- `Material m_VignetteMaterial`

- `Material m_SeparableBlurMaterial`

- `Material m_ChromAberrationMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class VignetteAndChromaticAberration : PostEffectsBase
{
	public AberrationMode mode; // 0x28
	public Single intensity; // 0x2c
	public Single chromaticAberration; // 0x30
	public Single axialAberration; // 0x34
	public Single blur; // 0x38
	public Single blurSpread; // 0x3c
	public Single luminanceDependency; // 0x40
	public Single blurDistance; // 0x44
	public Shader vignetteShader; // 0x48
	public Shader separableBlurShader; // 0x50
	public Shader chromAberrationShader; // 0x58
	private Material m_VignetteMaterial; // 0x60
	private Material m_SeparableBlurMaterial; // 0x68
	private Material m_ChromAberrationMaterial; // 0x70


	// RVA: 0x656a854 VA: 0x7598b82854
	public override Boolean CheckResources() { }
	// RVA: 0x656a904 VA: 0x7598b82904
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x656ae58 VA: 0x7598b82e58
	public Void .ctor() { }
}
```