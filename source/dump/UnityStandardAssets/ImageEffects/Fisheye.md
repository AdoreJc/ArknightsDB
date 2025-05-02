# Fisheye

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single strengthX`

- `Single strengthY`

- `Shader fishEyeShader`

- `Material fisheyeMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class Fisheye : PostEffectsBase
{
	public Single strengthX; // 0x28
	public Single strengthY; // 0x2c
	public Shader fishEyeShader; // 0x30
	private Material fisheyeMaterial; // 0x38


	// RVA: 0x6563720 VA: 0x7598b7b720
	public override Boolean CheckResources() { }
	// RVA: 0x6563788 VA: 0x7598b7b788
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x65638bc VA: 0x7598b7b8bc
	public Void .ctor() { }
}
```