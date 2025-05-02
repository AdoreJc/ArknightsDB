# BlurOptimized

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Int32 downsample`

- `Single blurSize`

- `Int32 blurIterations`

- `BlurType blurType`

- `Shader blurShader`

- `Material blurMaterial`


## Methods

- `Void OnDisable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class BlurOptimized : PostEffectsBase
{
	public Int32 downsample; // 0x28
	public Single blurSize; // 0x2c
	public Int32 blurIterations; // 0x30
	public BlurType blurType; // 0x34
	public Shader blurShader; // 0x38
	private Material blurMaterial; // 0x40


	// RVA: 0x6473378 VA: 0x7598a8b378
	public override Boolean CheckResources() { }
	// RVA: 0x64733ec VA: 0x7598a8b3ec
	public Void OnDisable() { }
	// RVA: 0x6473478 VA: 0x7598a8b478
	public Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x64737a0 VA: 0x7598a8b7a0
	public Void .ctor() { }
}
```