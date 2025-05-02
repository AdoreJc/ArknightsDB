# PostEffectsBase

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Boolean supportHDRTextures`

- `Boolean supportDX11`

- `Boolean isSupported`


## Methods

- `Material CheckShaderAndCreateMaterial(Shader, Material)`

- `Material CreateMaterial(Shader, Material)`

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void RemoveCreatedMaterials()`

- `Boolean CheckSupport()`

- `Void Start()`

- `Boolean CheckSupport(Boolean)`

- `Boolean CheckSupport(Boolean, Boolean)`

- `Boolean Dx11Support()`

- `Void ReportAutoDisable()`

- `Boolean CheckShader(Shader)`

- `Void NotSupported()`

- `Void DrawBorder(RenderTexture, Material)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class PostEffectsBase : MonoBehaviour
{
	protected Boolean supportHDRTextures; // 0x18
	protected Boolean supportDX11; // 0x19
	protected Boolean isSupported; // 0x1a
	private List`1 createdMaterials; // 0x20


	// RVA: 0x6560dc8 VA: 0x7598b78dc8
	protected Material CheckShaderAndCreateMaterial(Shader s, Material m2Create) { }
	// RVA: 0x6565cf8 VA: 0x7598b7dcf8
	protected Material CreateMaterial(Shader s, Material m2Create) { }
	// RVA: 0x6565f30 VA: 0x7598b7df30
	private Void OnEnable() { }
	// RVA: 0x6565f3c VA: 0x7598b7df3c
	private Void OnDestroy() { }
	// RVA: 0x6565f40 VA: 0x7598b7df40
	private Void RemoveCreatedMaterials() { }
	// RVA: 0x6566020 VA: 0x7598b7e020
	protected Boolean CheckSupport() { }
	// RVA: 0x6566028 VA: 0x7598b7e028
	public virtual Boolean CheckResources() { }
	// RVA: 0x65660e8 VA: 0x7598b7e0e8
	protected Void Start() { }
	// RVA: 0x656134c VA: 0x7598b7934c
	protected Boolean CheckSupport(Boolean needDepth) { }
	// RVA: 0x65660f4 VA: 0x7598b7e0f4
	protected Boolean CheckSupport(Boolean needDepth, Boolean needHdr) { }
	// RVA: 0x656614c VA: 0x7598b7e14c
	public Boolean Dx11Support() { }
	// RVA: 0x6561444 VA: 0x7598b79444
	protected Void ReportAutoDisable() { }
	// RVA: 0x6566154 VA: 0x7598b7e154
	private Boolean CheckShader(Shader s) { }
	// RVA: 0x6565cd8 VA: 0x7598b7dcd8
	protected Void NotSupported() { }
	// RVA: 0x65663d8 VA: 0x7598b7e3d8
	protected Void DrawBorder(RenderTexture dest, Material material) { }
	// RVA: 0x65632f4 VA: 0x7598b7b2f4
	public Void .ctor() { }
}
```