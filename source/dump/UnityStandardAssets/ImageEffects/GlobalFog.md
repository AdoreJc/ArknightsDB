# GlobalFog

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Boolean distanceFog`

- `Boolean excludeFarPixels`

- `Boolean useRadialDistance`

- `Boolean heightFog`

- `Single height`

- `Single heightDensity`

- `Single startDistance`

- `Shader fogShader`

- `Material fogMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
internal class GlobalFog : PostEffectsBase
{
	public Boolean distanceFog; // 0x28
	public Boolean excludeFarPixels; // 0x29
	public Boolean useRadialDistance; // 0x2a
	public Boolean heightFog; // 0x2b
	public Single height; // 0x2c
	public Single heightDensity; // 0x30
	public Single startDistance; // 0x34
	public Shader fogShader; // 0x38
	private Material fogMaterial; // 0x40


	// RVA: 0x65638d0 VA: 0x7598b7b8d0
	public override Boolean CheckResources() { }
	// RVA: 0x6563938 VA: 0x7598b7b938
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6563ec8 VA: 0x7598b7bec8
	public Void .ctor() { }
}
```