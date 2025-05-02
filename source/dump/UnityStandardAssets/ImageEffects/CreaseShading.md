# CreaseShading

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single intensity`

- `Int32 softness`

- `Single spread`

- `Shader blurShader`

- `Material blurMaterial`

- `Shader depthFetchShader`

- `Material depthFetchMaterial`

- `Shader creaseApplyShader`

- `Material creaseApplyMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class CreaseShading : PostEffectsBase
{
	public Single intensity; // 0x28
	public Int32 softness; // 0x2c
	public Single spread; // 0x30
	public Shader blurShader; // 0x38
	private Material blurMaterial; // 0x40
	public Shader depthFetchShader; // 0x48
	private Material depthFetchMaterial; // 0x50
	public Shader creaseApplyShader; // 0x58
	private Material creaseApplyMaterial; // 0x60


	// RVA: 0x64789bc VA: 0x7598a909bc
	public override Boolean CheckResources() { }
	// RVA: 0x6478a80 VA: 0x7598a90a80
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6478df8 VA: 0x7598a90df8
	public Void .ctor() { }
}
```