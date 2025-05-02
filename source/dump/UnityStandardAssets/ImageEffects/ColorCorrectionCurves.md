# ColorCorrectionCurves

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `AnimationCurve redChannel`

- `AnimationCurve greenChannel`

- `AnimationCurve blueChannel`

- `Boolean useDepthCorrection`

- `AnimationCurve zCurve`

- `AnimationCurve depthRedChannel`

- `AnimationCurve depthGreenChannel`

- `AnimationCurve depthBlueChannel`

- `Material ccMaterial`

- `Material ccDepthMaterial`

- `Material selectiveCcMaterial`

- `Texture2D rgbChannelTex`

- `Texture2D rgbDepthChannelTex`

- `Texture2D zCurveTex`

- `Single saturation`

- `Boolean selectiveCc`

- `Color selectiveFromColor`

- `Color selectiveToColor`

- `ColorCorrectionMode mode`

- `Boolean updateTextures`

- `Shader colorCorrectionCurvesShader`

- `Shader simpleColorCorrectionCurvesShader`

- `Shader colorCorrectionSelectiveShader`

- `Boolean updateTexturesOnStartup`


## Methods

- `Void Start()`

- `Void Awake()`

- `Void UpdateParameters()`

- `Void UpdateTextures()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ColorCorrectionCurves : PostEffectsBase
{
	public AnimationCurve redChannel; // 0x28
	public AnimationCurve greenChannel; // 0x30
	public AnimationCurve blueChannel; // 0x38
	public Boolean useDepthCorrection; // 0x40
	public AnimationCurve zCurve; // 0x48
	public AnimationCurve depthRedChannel; // 0x50
	public AnimationCurve depthGreenChannel; // 0x58
	public AnimationCurve depthBlueChannel; // 0x60
	private Material ccMaterial; // 0x68
	private Material ccDepthMaterial; // 0x70
	private Material selectiveCcMaterial; // 0x78
	private Texture2D rgbChannelTex; // 0x80
	private Texture2D rgbDepthChannelTex; // 0x88
	private Texture2D zCurveTex; // 0x90
	public Single saturation; // 0x98
	public Boolean selectiveCc; // 0x9c
	public Color selectiveFromColor; // 0xa0
	public Color selectiveToColor; // 0xb0
	public ColorCorrectionMode mode; // 0xc0
	public Boolean updateTextures; // 0xc4
	public Shader colorCorrectionCurvesShader; // 0xc8
	public Shader simpleColorCorrectionCurvesShader; // 0xd0
	public Shader colorCorrectionSelectiveShader; // 0xd8
	private Boolean updateTexturesOnStartup; // 0xe0


	// RVA: 0x6476004 VA: 0x7598a8e004
	private Void Start() { }
	// RVA: 0x6476024 VA: 0x7598a8e024
	private Void Awake() { }
	// RVA: 0x6476028 VA: 0x7598a8e028
	public override Boolean CheckResources() { }
	// RVA: 0x64762ec VA: 0x7598a8e2ec
	public Void UpdateParameters() { }
	// RVA: 0x64765e0 VA: 0x7598a8e5e0
	private Void UpdateTextures() { }
	// RVA: 0x64765e4 VA: 0x7598a8e5e4
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x64768f0 VA: 0x7598a8e8f0
	public Void .ctor() { }
}
```