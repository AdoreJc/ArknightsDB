# BloomOptimized

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single threshold`

- `Single intensity`

- `Single blurSize`

- `Resolution resolution`

- `Int32 blurIterations`

- `BlurType blurType`

- `Shader fastBloomShader`

- `Material fastBloomMaterial`


## Methods

- `Void OnDisable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class BloomOptimized : PostEffectsBase
{
	public Single threshold; // 0x28
	public Single intensity; // 0x2c
	public Single blurSize; // 0x30
	private Resolution resolution; // 0x34
	public Int32 blurIterations; // 0x38
	public BlurType blurType; // 0x3c
	public Shader fastBloomShader; // 0x40
	private Material fastBloomMaterial; // 0x48


	// RVA: 0x6472900 VA: 0x7598a8a900
	public override Boolean CheckResources() { }
	// RVA: 0x6472974 VA: 0x7598a8a974
	private Void OnDisable() { }
	// RVA: 0x6472a00 VA: 0x7598a8aa00
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6472d70 VA: 0x7598a8ad70
	public Void .ctor() { }
}
```