# ScreenSpaceAmbientObscurance

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single intensity`

- `Single radius`

- `Int32 blurIterations`

- `Single blurFilterDistance`

- `Int32 downsample`

- `Texture2D rand`

- `Shader aoShader`

- `Material aoMaterial`


## Methods

- `Void OnDisable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
internal class ScreenSpaceAmbientObscurance : PostEffectsBase
{
	public Single intensity; // 0x28
	public Single radius; // 0x2c
	public Int32 blurIterations; // 0x30
	public Single blurFilterDistance; // 0x34
	public Int32 downsample; // 0x38
	public Texture2D rand; // 0x40
	public Shader aoShader; // 0x48
	private Material aoMaterial; // 0x50


	// RVA: 0x6567548 VA: 0x7598b7f548
	public override Boolean CheckResources() { }
	// RVA: 0x65675b0 VA: 0x7598b7f5b0
	private Void OnDisable() { }
	// RVA: 0x6567640 VA: 0x7598b7f640
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6567df4 VA: 0x7598b7fdf4
	public Void .ctor() { }
}
```