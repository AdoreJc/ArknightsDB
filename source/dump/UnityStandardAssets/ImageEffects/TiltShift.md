# TiltShift

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `TiltShiftMode mode`

- `TiltShiftQuality quality`

- `Single blurArea`

- `Single maxBlurSize`

- `Int32 downsample`

- `Shader tiltShiftShader`

- `Material tiltShiftMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
internal class TiltShift : PostEffectsBase
{
	public TiltShiftMode mode; // 0x28
	public TiltShiftQuality quality; // 0x2c
	public Single blurArea; // 0x30
	public Single maxBlurSize; // 0x34
	public Int32 downsample; // 0x38
	public Shader tiltShiftShader; // 0x40
	private Material tiltShiftMaterial; // 0x48


	// RVA: 0x6568f70 VA: 0x7598b80f70
	public override Boolean CheckResources() { }
	// RVA: 0x6568fd8 VA: 0x7598b80fd8
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6569268 VA: 0x7598b81268
	public Void .ctor() { }
}
```