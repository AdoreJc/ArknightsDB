# SunShafts

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `SunShaftsResolution resolution`

- `ShaftsScreenBlendMode screenBlendMode`

- `Transform sunTransform`

- `Int32 radialBlurIterations`

- `Color sunColor`

- `Color sunThreshold`

- `Single sunShaftBlurRadius`

- `Single sunShaftIntensity`

- `Single maxRadius`

- `Boolean useDepthTexture`

- `Shader sunShaftsShader`

- `Material sunShaftsMaterial`

- `Shader simpleClearShader`

- `Material simpleClearMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class SunShafts : PostEffectsBase
{
	public SunShaftsResolution resolution; // 0x28
	public ShaftsScreenBlendMode screenBlendMode; // 0x2c
	public Transform sunTransform; // 0x30
	public Int32 radialBlurIterations; // 0x38
	public Color sunColor; // 0x3c
	public Color sunThreshold; // 0x4c
	public Single sunShaftBlurRadius; // 0x5c
	public Single sunShaftIntensity; // 0x60
	public Single maxRadius; // 0x64
	public Boolean useDepthTexture; // 0x68
	public Shader sunShaftsShader; // 0x70
	private Material sunShaftsMaterial; // 0x78
	public Shader simpleClearShader; // 0x80
	private Material simpleClearMaterial; // 0x88


	// RVA: 0x65687e4 VA: 0x7598b807e4
	public override Boolean CheckResources() { }
	// RVA: 0x6568870 VA: 0x7598b80870
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6568f2c VA: 0x7598b80f2c
	public Void .ctor() { }
}
```