# DepthOfField

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Boolean visualizeFocus`

- `Single focalLength`

- `Single focalSize`

- `Single aperture`

- `Transform focalTransform`

- `Single maxBlurSize`

- `Boolean highResolution`

- `BlurType blurType`

- `BlurSampleCount blurSampleCount`

- `Boolean nearBlur`

- `Single foregroundOverlap`

- `Shader dofHdrShader`

- `Material dofHdrMaterial`

- `Shader dx11BokehShader`

- `Material dx11bokehMaterial`

- `Single dx11BokehThreshold`

- `Single dx11SpawnHeuristic`

- `Texture2D dx11BokehTexture`

- `Single dx11BokehScale`

- `Single dx11BokehIntensity`

- `Single focalDistance01`

- `ComputeBuffer cbDrawArgs`

- `ComputeBuffer cbPoints`

- `Single internalBlurWidth`

- `Camera cachedCamera`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void ReleaseComputeResources()`

- `Void CreateComputeResources()`

- `Single FocalDistance01(Single)`

- `Void WriteCoc(RenderTexture, Boolean)`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class DepthOfField : PostEffectsBase
{
	public Boolean visualizeFocus; // 0x28
	public Single focalLength; // 0x2c
	public Single focalSize; // 0x30
	public Single aperture; // 0x34
	public Transform focalTransform; // 0x38
	public Single maxBlurSize; // 0x40
	public Boolean highResolution; // 0x44
	public BlurType blurType; // 0x48
	public BlurSampleCount blurSampleCount; // 0x4c
	public Boolean nearBlur; // 0x50
	public Single foregroundOverlap; // 0x54
	public Shader dofHdrShader; // 0x58
	private Material dofHdrMaterial; // 0x60
	public Shader dx11BokehShader; // 0x68
	private Material dx11bokehMaterial; // 0x70
	public Single dx11BokehThreshold; // 0x78
	public Single dx11SpawnHeuristic; // 0x7c
	public Texture2D dx11BokehTexture; // 0x80
	public Single dx11BokehScale; // 0x88
	public Single dx11BokehIntensity; // 0x8c
	private Single focalDistance01; // 0x90
	private ComputeBuffer cbDrawArgs; // 0x98
	private ComputeBuffer cbPoints; // 0xa0
	private Single internalBlurWidth; // 0xa8
	private Camera cachedCamera; // 0xb0


	// RVA: 0x6478e14 VA: 0x7598a90e14
	public override Boolean CheckResources() { }
	// RVA: 0x6479014 VA: 0x7598a91014
	private Void OnEnable() { }
	// RVA: 0x6479094 VA: 0x7598a91094
	private Void OnDisable() { }
	// RVA: 0x647918c VA: 0x7598a9118c
	private Void ReleaseComputeResources() { }
	// RVA: 0x6478ecc VA: 0x7598a90ecc
	private Void CreateComputeResources() { }
	// RVA: 0x64791e4 VA: 0x7598a911e4
	private Single FocalDistance01(Single worldDist) { }
	// RVA: 0x64792d0 VA: 0x7598a912d0
	private Void WriteCoc(RenderTexture fromTo, Boolean fgDilate) { }
	// RVA: 0x64795a0 VA: 0x7598a915a0
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x647a8a0 VA: 0x7598a928a0
	public Void .ctor() { }
}
```