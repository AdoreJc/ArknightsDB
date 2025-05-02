# ColorCorrectionLookup

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Shader shader`

- `Material material`

- `Texture3D converted3DLut`

- `String basedOnTempTex`


## Methods

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void SetIdentityLut()`

- `Boolean ValidDimensions(Texture2D)`

- `Void Convert(Texture2D, String)`

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ColorCorrectionLookup : PostEffectsBase
{
	public Shader shader; // 0x28
	private Material material; // 0x30
	public Texture3D converted3DLut; // 0x38
	public String basedOnTempTex; // 0x40


	// RVA: 0x6476f7c VA: 0x7598a8ef7c
	public override Boolean CheckResources() { }
	// RVA: 0x6476fec VA: 0x7598a8efec
	private Void OnDisable() { }
	// RVA: 0x6477088 VA: 0x7598a8f088
	private Void OnDestroy() { }
	// RVA: 0x6477118 VA: 0x7598a8f118
	public Void SetIdentityLut() { }
	// RVA: 0x6477314 VA: 0x7598a8f314
	public Boolean ValidDimensions(Texture2D tex2d) { }
	// RVA: 0x6477414 VA: 0x7598a8f414
	public Void Convert(Texture2D temp2DTex, String path) { }
	// RVA: 0x647775c VA: 0x7598a8f75c
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6477950 VA: 0x7598a8f950
	public Void .ctor() { }
}
```