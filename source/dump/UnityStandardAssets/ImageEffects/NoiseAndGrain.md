# NoiseAndGrain

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single intensityMultiplier`

- `Single generalIntensity`

- `Single blackIntensity`

- `Single whiteIntensity`

- `Single midGrey`

- `Boolean dx11Grain`

- `Single softness`

- `Boolean monochrome`

- `Vector3 intensities`

- `Vector3 tiling`

- `Single monochromeTiling`

- `FilterMode filterMode`

- `Texture2D noiseTexture`

- `Shader noiseShader`

- `Material noiseMaterial`

- `Shader dx11NoiseShader`

- `Material dx11NoiseMaterial`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class NoiseAndGrain : PostEffectsBase
{
	public Single intensityMultiplier; // 0x28
	public Single generalIntensity; // 0x2c
	public Single blackIntensity; // 0x30
	public Single whiteIntensity; // 0x34
	public Single midGrey; // 0x38
	public Boolean dx11Grain; // 0x3c
	public Single softness; // 0x40
	public Boolean monochrome; // 0x44
	public Vector3 intensities; // 0x48
	public Vector3 tiling; // 0x54
	public Single monochromeTiling; // 0x60
	public FilterMode filterMode; // 0x64
	public Texture2D noiseTexture; // 0x68
	public Shader noiseShader; // 0x70
	private Material noiseMaterial; // 0x78
	public Shader dx11NoiseShader; // 0x80
	private Material dx11NoiseMaterial; // 0x88
	private static Single TILE_AMOUNT; // 0x0


	// RVA: 0x6564910 VA: 0x7598b7c910
	public override Boolean CheckResources() { }
	// RVA: 0x65649ac VA: 0x7598b7c9ac
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x65651ac VA: 0x7598b7d1ac
	private static Void DrawNoiseQuadGrid(RenderTexture source, RenderTexture dest, Material fxMaterial, Texture2D noise, Int32 passNr) { }
	// RVA: 0x65654ec VA: 0x7598b7d4ec
	public Void .ctor() { }
	// RVA: 0x6565528 VA: 0x7598b7d528
	private static Void .cctor() { }
}
```