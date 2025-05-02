# ContrastStretch

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single adaptationSpeed`

- `Single limitMinimum`

- `Single limitMaximum`

- `Int32 curAdaptIndex`

- `Shader shaderLum`

- `Material m_materialLum`

- `Shader shaderReduce`

- `Material m_materialReduce`

- `Shader shaderAdapt`

- `Material m_materialAdapt`

- `Shader shaderApply`

- `Material m_materialApply`


## Properties

- `Material materialLum`

- `Material materialReduce`

- `Material materialAdapt`

- `Material materialApply`


## Methods

- `Material get_materialLum()`

- `Material get_materialReduce()`

- `Material get_materialAdapt()`

- `Material get_materialApply()`

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void CalculateAdaptation(Texture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ContrastStretch : MonoBehaviour
{
	public Single adaptationSpeed; // 0x18
	public Single limitMinimum; // 0x1c
	public Single limitMaximum; // 0x20
	private RenderTexture[] adaptRenderTex; // 0x28
	private Int32 curAdaptIndex; // 0x30
	public Shader shaderLum; // 0x38
	private Material m_materialLum; // 0x40
	public Shader shaderReduce; // 0x48
	private Material m_materialReduce; // 0x50
	public Shader shaderAdapt; // 0x58
	private Material m_materialAdapt; // 0x60
	public Shader shaderApply; // 0x68
	private Material m_materialApply; // 0x70

	protected Material materialLum { get; }
	protected Material materialReduce { get; }
	protected Material materialAdapt { get; }
	protected Material materialApply { get; }

	// RVA: 0x6477e4c VA: 0x7598a8fe4c
	protected Material get_materialLum() { }
	// RVA: 0x6477f20 VA: 0x7598a8ff20
	protected Material get_materialReduce() { }
	// RVA: 0x6477ff4 VA: 0x7598a8fff4
	protected Material get_materialAdapt() { }
	// RVA: 0x64780c8 VA: 0x7598a900c8
	protected Material get_materialApply() { }
	// RVA: 0x647819c VA: 0x7598a9019c
	private Void Start() { }
	// RVA: 0x6478220 VA: 0x7598a90220
	private Void OnEnable() { }
	// RVA: 0x647836c VA: 0x7598a9036c
	private Void OnDisable() { }
	// RVA: 0x6478548 VA: 0x7598a90548
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6478788 VA: 0x7598a90788
	private Void CalculateAdaptation(Texture curTexture) { }
	// RVA: 0x6478940 VA: 0x7598a90940
	public Void .ctor() { }
}
```