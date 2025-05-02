# Antialiasing

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `AAMode mode`

- `Boolean showGeneratedNormals`

- `Single offsetScale`

- `Single blurRadius`

- `Single edgeThresholdMin`

- `Single edgeThreshold`

- `Single edgeSharpness`

- `Boolean dlaaSharp`

- `Shader ssaaShader`

- `Material ssaa`

- `Shader dlaaShader`

- `Material dlaa`

- `Shader nfaaShader`

- `Material nfaa`

- `Shader shaderFXAAPreset2`

- `Material materialFXAAPreset2`

- `Shader shaderFXAAPreset3`

- `Material materialFXAAPreset3`

- `Shader shaderFXAAII`

- `Material materialFXAAII`

- `Shader shaderFXAAIII`

- `Material materialFXAAIII`


## Methods

- `Material CurrentAAMaterial()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class Antialiasing : PostEffectsBase
{
	public AAMode mode; // 0x28
	public Boolean showGeneratedNormals; // 0x2c
	public Single offsetScale; // 0x30
	public Single blurRadius; // 0x34
	public Single edgeThresholdMin; // 0x38
	public Single edgeThreshold; // 0x3c
	public Single edgeSharpness; // 0x40
	public Boolean dlaaSharp; // 0x44
	public Shader ssaaShader; // 0x48
	private Material ssaa; // 0x50
	public Shader dlaaShader; // 0x58
	private Material dlaa; // 0x60
	public Shader nfaaShader; // 0x68
	private Material nfaa; // 0x70
	public Shader shaderFXAAPreset2; // 0x78
	private Material materialFXAAPreset2; // 0x80
	public Shader shaderFXAAPreset3; // 0x88
	private Material materialFXAAPreset3; // 0x90
	public Shader shaderFXAAII; // 0x98
	private Material materialFXAAII; // 0xa0
	public Shader shaderFXAAIII; // 0xa8
	private Material materialFXAAIII; // 0xb0


	// RVA: 0x646fe54 VA: 0x7598a87e54
	public Material CurrentAAMaterial() { }
	// RVA: 0x646febc VA: 0x7598a87ebc
	public override Boolean CheckResources() { }
	// RVA: 0x647002c VA: 0x7598a8802c
	public Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x64704f0 VA: 0x7598a884f0
	public Void .ctor() { }
}
```