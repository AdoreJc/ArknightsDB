# NoiseAndScratches

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Boolean monochrome`

- `Boolean rgbFallback`

- `Single grainIntensityMin`

- `Single grainIntensityMax`

- `Single grainSize`

- `Single scratchIntensityMin`

- `Single scratchIntensityMax`

- `Single scratchFPS`

- `Single scratchJitter`

- `Texture grainTexture`

- `Texture scratchTexture`

- `Shader shaderRGB`

- `Shader shaderYUV`

- `Material m_MaterialRGB`

- `Material m_MaterialYUV`

- `Single scratchTimeLeft`

- `Single scratchX`

- `Single scratchY`


## Properties

- `Material material`


## Methods

- `Void Start()`

- `Material get_material()`

- `Void OnDisable()`

- `Void SanitizeParameters()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class NoiseAndScratches : MonoBehaviour
{
	public Boolean monochrome; // 0x18
	private Boolean rgbFallback; // 0x19
	public Single grainIntensityMin; // 0x1c
	public Single grainIntensityMax; // 0x20
	public Single grainSize; // 0x24
	public Single scratchIntensityMin; // 0x28
	public Single scratchIntensityMax; // 0x2c
	public Single scratchFPS; // 0x30
	public Single scratchJitter; // 0x34
	public Texture grainTexture; // 0x38
	public Texture scratchTexture; // 0x40
	public Shader shaderRGB; // 0x48
	public Shader shaderYUV; // 0x50
	private Material m_MaterialRGB; // 0x58
	private Material m_MaterialYUV; // 0x60
	private Single scratchTimeLeft; // 0x68
	private Single scratchX; // 0x6c
	private Single scratchY; // 0x70

	protected Material material { get; }

	// RVA: 0x6565574 VA: 0x7598b7d574
	protected Void Start() { }
	// RVA: 0x65656a0 VA: 0x7598b7d6a0
	protected Material get_material() { }
	// RVA: 0x6565808 VA: 0x7598b7d808
	protected Void OnDisable() { }
	// RVA: 0x65658d8 VA: 0x7598b7d8d8
	private Void SanitizeParameters() { }
	// RVA: 0x656597c VA: 0x7598b7d97c
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6565ca4 VA: 0x7598b7dca4
	public Void .ctor() { }
}
```