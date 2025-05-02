# Blur

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Int32 iterations`

- `Single blurSpread`

- `Shader blurShader`


## Properties

- `Material material`


## Methods

- `Material get_material()`

- `Void OnDisable()`

- `Void Start()`

- `Void FourTapCone(RenderTexture, RenderTexture, Int32)`

- `Void DownSample4x(RenderTexture, RenderTexture)`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class Blur : MonoBehaviour
{
	public Int32 iterations; // 0x18
	public Single blurSpread; // 0x1c
	public Shader blurShader; // 0x20
	private static Material m_Material; // 0x0

	protected Material material { get; }

	// RVA: 0x6472d94 VA: 0x7598a8ad94
	protected Material get_material() { }
	// RVA: 0x6472e9c VA: 0x7598a8ae9c
	protected Void OnDisable() { }
	// RVA: 0x6472f48 VA: 0x7598a8af48
	protected Void Start() { }
	// RVA: 0x6472ff8 VA: 0x7598a8aff8
	public Void FourTapCone(RenderTexture source, RenderTexture dest, Int32 iteration) { }
	// RVA: 0x6473108 VA: 0x7598a8b108
	private Void DownSample4x(RenderTexture source, RenderTexture dest) { }
	// RVA: 0x6473204 VA: 0x7598a8b204
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6473360 VA: 0x7598a8b360
	public Void .ctor() { }
}
```