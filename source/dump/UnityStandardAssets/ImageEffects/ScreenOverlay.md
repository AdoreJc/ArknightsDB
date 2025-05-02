# ScreenOverlay

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `OverlayBlendMode blendMode`

- `Single intensity`

- `Texture2D texture`

- `Shader overlayShader`

- `Material overlayMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ScreenOverlay : PostEffectsBase
{
	public OverlayBlendMode blendMode; // 0x28
	public Single intensity; // 0x2c
	public Texture2D texture; // 0x30
	public Shader overlayShader; // 0x38
	private Material overlayMaterial; // 0x40


	// RVA: 0x6567380 VA: 0x7598b7f380
	public override Boolean CheckResources() { }
	// RVA: 0x65673e8 VA: 0x7598b7f3e8
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6567538 VA: 0x7598b7f538
	public Void .ctor() { }
}
```