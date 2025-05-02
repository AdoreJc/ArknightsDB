# ScreenSpaceAmbientOcclusion

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single m_Radius`

- `SSAOSamples m_SampleCount`

- `Single m_OcclusionIntensity`

- `Int32 m_Blur`

- `Int32 m_Downsampling`

- `Single m_OcclusionAttenuation`

- `Single m_MinZ`

- `Shader m_SSAOShader`

- `Material m_SSAOMaterial`

- `Texture2D m_RandomTexture`

- `Boolean m_Supported`


## Methods

- `Void OnDisable()`

- `Void Start()`

- `Void OnEnable()`

- `Void CreateMaterials()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ScreenSpaceAmbientOcclusion : MonoBehaviour
{
	public Single m_Radius; // 0x18
	public SSAOSamples m_SampleCount; // 0x1c
	public Single m_OcclusionIntensity; // 0x20
	public Int32 m_Blur; // 0x24
	public Int32 m_Downsampling; // 0x28
	public Single m_OcclusionAttenuation; // 0x2c
	public Single m_MinZ; // 0x30
	public Shader m_SSAOShader; // 0x38
	private Material m_SSAOMaterial; // 0x40
	public Texture2D m_RandomTexture; // 0x48
	private Boolean m_Supported; // 0x50


	// RVA: 0x6567e10 VA: 0x7598b7fe10
	private static Material CreateMaterial(Shader shader) { }
	// RVA: 0x6567ebc VA: 0x7598b7febc
	private static Void DestroyMaterial(Material mat) { }
	// RVA: 0x6567f40 VA: 0x7598b7ff40
	private Void OnDisable() { }
	// RVA: 0x6567f48 VA: 0x7598b7ff48
	private Void Start() { }
	// RVA: 0x65680e8 VA: 0x7598b800e8
	private Void OnEnable() { }
	// RVA: 0x6568010 VA: 0x7598b80010
	private Void CreateMaterials() { }
	// RVA: 0x6568154 VA: 0x7598b80154
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6568728 VA: 0x7598b80728
	public Void .ctor() { }
}
```