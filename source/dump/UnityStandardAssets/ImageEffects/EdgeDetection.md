# EdgeDetection

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `EdgeDetectMode mode`

- `Single sensitivityDepth`

- `Single sensitivityNormals`

- `Single lumThreshold`

- `Single edgeExp`

- `Single sampleDist`

- `Single edgesOnly`

- `Color edgesOnlyBgColor`

- `Shader edgeDetectShader`

- `Material edgeDetectMaterial`

- `EdgeDetectMode oldMode`


## Methods

- `Void Start()`

- `Void SetCameraFlag()`

- `Void OnEnable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class EdgeDetection : PostEffectsBase
{
	public EdgeDetectMode mode; // 0x28
	public Single sensitivityDepth; // 0x2c
	public Single sensitivityNormals; // 0x30
	public Single lumThreshold; // 0x34
	public Single edgeExp; // 0x38
	public Single sampleDist; // 0x3c
	public Single edgesOnly; // 0x40
	public Color edgesOnlyBgColor; // 0x44
	public Shader edgeDetectShader; // 0x58
	private Material edgeDetectMaterial; // 0x60
	private EdgeDetectMode oldMode; // 0x68


	// RVA: 0x65633d8 VA: 0x7598b7b3d8
	public override Boolean CheckResources() { }
	// RVA: 0x6563510 VA: 0x7598b7b510
	private Void Start() { }
	// RVA: 0x6563460 VA: 0x7598b7b460
	private Void SetCameraFlag() { }
	// RVA: 0x656351c VA: 0x7598b7b51c
	private Void OnEnable() { }
	// RVA: 0x6563520 VA: 0x7598b7b520
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x65636f4 VA: 0x7598b7b6f4
	public Void .ctor() { }
}
```