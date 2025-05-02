# Tonemapping

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `TonemapperType type`

- `AdaptiveTexSize adaptiveTextureSize`

- `AnimationCurve remapCurve`

- `Texture2D curveTex`

- `Single exposureAdjustment`

- `Single middleGrey`

- `Single white`

- `Single adaptionSpeed`

- `Shader tonemapper`

- `Boolean validRenderTextureFormat`

- `Material tonemapMaterial`

- `RenderTexture rt`

- `RenderTextureFormat rtFormat`


## Methods

- `Single UpdateCurve()`

- `Void OnDisable()`

- `Boolean CreateInternalRenderTexture()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class Tonemapping : PostEffectsBase
{
	public TonemapperType type; // 0x28
	public AdaptiveTexSize adaptiveTextureSize; // 0x2c
	public AnimationCurve remapCurve; // 0x30
	private Texture2D curveTex; // 0x38
	public Single exposureAdjustment; // 0x40
	public Single middleGrey; // 0x44
	public Single white; // 0x48
	public Single adaptionSpeed; // 0x4c
	public Shader tonemapper; // 0x50
	public Boolean validRenderTextureFormat; // 0x58
	private Material tonemapMaterial; // 0x60
	private RenderTexture rt; // 0x68
	private RenderTextureFormat rtFormat; // 0x70


	// RVA: 0x6569280 VA: 0x7598b81280
	public override Boolean CheckResources() { }
	// RVA: 0x65693e4 VA: 0x7598b813e4
	public Single UpdateCurve() { }
	// RVA: 0x6569664 VA: 0x7598b81664
	private Void OnDisable() { }
	// RVA: 0x65697bc VA: 0x7598b817bc
	private Boolean CreateInternalRenderTexture() { }
	// RVA: 0x65698bc VA: 0x7598b818bc
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x656a05c VA: 0x7598b8205c
	public Void .ctor() { }
}
```