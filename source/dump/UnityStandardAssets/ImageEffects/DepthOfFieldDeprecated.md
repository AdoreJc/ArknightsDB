# DepthOfFieldDeprecated

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Dof34QualitySetting quality`

- `DofResolution resolution`

- `Boolean simpleTweakMode`

- `Single focalPoint`

- `Single smoothness`

- `Single focalZDistance`

- `Single focalZStartCurve`

- `Single focalZEndCurve`

- `Single focalStartCurve`

- `Single focalEndCurve`

- `Single focalDistance01`

- `Transform objectFocus`

- `Single focalSize`

- `DofBlurriness bluriness`

- `Single maxBlurSpread`

- `Single foregroundBlurExtrude`

- `Shader dofBlurShader`

- `Material dofBlurMaterial`

- `Shader dofShader`

- `Material dofMaterial`

- `Boolean visualize`

- `BokehDestination bokehDestination`

- `Single widthOverHeight`

- `Single oneOverBaseSize`

- `Boolean bokeh`

- `Boolean bokehSupport`

- `Shader bokehShader`

- `Texture2D bokehTexture`

- `Single bokehScale`

- `Single bokehIntensity`

- `Single bokehThresholdContrast`

- `Single bokehThresholdLuminance`

- `Int32 bokehDownsample`

- `Material bokehMaterial`

- `Camera _camera`

- `RenderTexture foregroundTexture`

- `RenderTexture mediumRezWorkTexture`

- `RenderTexture finalDefocus`

- `RenderTexture lowRezWorkTexture`

- `RenderTexture bokehSource`

- `RenderTexture bokehSource2`


## Methods

- `Void CreateMaterials()`

- `Void OnDisable()`

- `Void OnEnable()`

- `Single FocalDistance01(Single)`

- `Int32 GetDividerBasedOnQuality()`

- `Int32 GetLowResolutionDividerBasedOnQuality(Int32)`

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void Blur(RenderTexture, RenderTexture, DofBlurriness, Int32, Single)`

- `Void BlurFg(RenderTexture, RenderTexture, DofBlurriness, Int32, Single)`

- `Void BlurHex(RenderTexture, RenderTexture, Int32, Single, RenderTexture)`

- `Void Downsample(RenderTexture, RenderTexture)`

- `Void AddBokeh(RenderTexture, RenderTexture, RenderTexture)`

- `Void ReleaseTextures()`

- `Void AllocateTextures(Boolean, RenderTexture, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class DepthOfFieldDeprecated : PostEffectsBase
{
	private static Int32 SMOOTH_DOWNSAMPLE_PASS; // 0x0
	private static Single BOKEH_EXTRA_BLUR; // 0x4
	public Dof34QualitySetting quality; // 0x28
	public DofResolution resolution; // 0x2c
	public Boolean simpleTweakMode; // 0x30
	public Single focalPoint; // 0x34
	public Single smoothness; // 0x38
	public Single focalZDistance; // 0x3c
	public Single focalZStartCurve; // 0x40
	public Single focalZEndCurve; // 0x44
	private Single focalStartCurve; // 0x48
	private Single focalEndCurve; // 0x4c
	private Single focalDistance01; // 0x50
	public Transform objectFocus; // 0x58
	public Single focalSize; // 0x60
	public DofBlurriness bluriness; // 0x64
	public Single maxBlurSpread; // 0x68
	public Single foregroundBlurExtrude; // 0x6c
	public Shader dofBlurShader; // 0x70
	private Material dofBlurMaterial; // 0x78
	public Shader dofShader; // 0x80
	private Material dofMaterial; // 0x88
	public Boolean visualize; // 0x90
	public BokehDestination bokehDestination; // 0x94
	private Single widthOverHeight; // 0x98
	private Single oneOverBaseSize; // 0x9c
	public Boolean bokeh; // 0xa0
	public Boolean bokehSupport; // 0xa1
	public Shader bokehShader; // 0xa8
	public Texture2D bokehTexture; // 0xb0
	public Single bokehScale; // 0xb8
	public Single bokehIntensity; // 0xbc
	public Single bokehThresholdContrast; // 0xc0
	public Single bokehThresholdLuminance; // 0xc4
	public Int32 bokehDownsample; // 0xc8
	private Material bokehMaterial; // 0xd0
	private Camera _camera; // 0xd8
	private RenderTexture foregroundTexture; // 0xe0
	private RenderTexture mediumRezWorkTexture; // 0xe8
	private RenderTexture finalDefocus; // 0xf0
	private RenderTexture lowRezWorkTexture; // 0xf8
	private RenderTexture bokehSource; // 0x100
	private RenderTexture bokehSource2; // 0x108


	// RVA: 0x6560cc8 VA: 0x7598b78cc8
	private Void CreateMaterials() { }
	// RVA: 0x6561224 VA: 0x7598b79224
	public override Boolean CheckResources() { }
	// RVA: 0x65614fc VA: 0x7598b794fc
	private Void OnDisable() { }
	// RVA: 0x6561664 VA: 0x7598b79664
	private Void OnEnable() { }
	// RVA: 0x65616e4 VA: 0x7598b796e4
	private Single FocalDistance01(Single worldDist) { }
	// RVA: 0x65617d0 VA: 0x7598b797d0
	private Int32 GetDividerBasedOnQuality() { }
	// RVA: 0x65617f4 VA: 0x7598b797f4
	private Int32 GetLowResolutionDividerBasedOnQuality(Int32 baseDivider) { }
	// RVA: 0x6561818 VA: 0x7598b79818
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6562584 VA: 0x7598b7a584
	private Void Blur(RenderTexture from, RenderTexture to, DofBlurriness iterations, Int32 blurPass, Single spread) { }
	// RVA: 0x6562b34 VA: 0x7598b7ab34
	private Void BlurFg(RenderTexture from, RenderTexture to, DofBlurriness iterations, Int32 blurPass, Single spread) { }
	// RVA: 0x6562ea8 VA: 0x7598b7aea8
	private Void BlurHex(RenderTexture from, RenderTexture to, Int32 blurPass, Single spread, RenderTexture tmp) { }
	// RVA: 0x656245c VA: 0x7598b7a45c
	private Void Downsample(RenderTexture from, RenderTexture to) { }
	// RVA: 0x6562764 VA: 0x7598b7a764
	private Void AddBokeh(RenderTexture bokehInfo, RenderTexture tempTex, RenderTexture finalTarget) { }
	// RVA: 0x6562d40 VA: 0x7598b7ad40
	private Void ReleaseTextures() { }
	// RVA: 0x65620ac VA: 0x7598b7a0ac
	private Void AllocateTextures(Boolean blurForeground, RenderTexture source, Int32 divider, Int32 lowTexDivider) { }
	// RVA: 0x6563280 VA: 0x7598b7b280
	public Void .ctor() { }
	// RVA: 0x6563388 VA: 0x7598b7b388
	private static Void .cctor() { }
}
```