# LookupFilter3D

**Namespace:** `Colorful`


## Fields

- `Texture2D LookupTexture`

- `Single Amount`

- `Boolean ForceCompatibility`

- `Texture3D m_Lut3D`

- `String m_BaseTextureName`

- `Boolean m_Use2DLut`

- `Shader Shader2D`

- `Shader Shader3D`

- `Material m_Material2D`

- `Material m_Material3D`


## Properties

- `Shader Shader2DSafe`

- `Shader Shader3DSafe`

- `Material Material`


## Methods

- `Shader get_Shader2DSafe()`

- `Shader get_Shader3DSafe()`

- `Material get_Material()`

- `Void SetIdentityLut()`

- `Boolean ValidDimensions(Texture2D)`

- `Void ConvertBaseTexture()`

- `Void Apply(Texture, RenderTexture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class LookupFilter3D : MonoBehaviour
{
	public Texture2D LookupTexture; // 0x18
	public Single Amount; // 0x20
	public Boolean ForceCompatibility; // 0x24
	protected Texture3D m_Lut3D; // 0x28
	protected String m_BaseTextureName; // 0x30
	protected Boolean m_Use2DLut; // 0x38
	public Shader Shader2D; // 0x40
	public Shader Shader3D; // 0x48
	protected Material m_Material2D; // 0x50
	protected Material m_Material3D; // 0x58

	public Shader Shader2DSafe { get; }
	public Shader Shader3DSafe { get; }
	public Material Material { get; }

	// RVA: 0x34edc84 VA: 0x7595b05c84
	public Shader get_Shader2DSafe() { }
	// RVA: 0x34edd20 VA: 0x7595b05d20
	public Shader get_Shader3DSafe() { }
	// RVA: 0x34ed2cc VA: 0x7595b052cc
	public Material get_Material() { }
	// RVA: 0x34eddbc VA: 0x7595b05dbc
	protected virtual Void Start() { }
	// RVA: 0x34edf4c VA: 0x7595b05f4c
	protected virtual Void OnDisable() { }
	// RVA: 0x34ee080 VA: 0x7595b06080
	protected virtual Void Reset() { }
	// RVA: 0x34ed888 VA: 0x7595b05888
	protected Void SetIdentityLut() { }
	// RVA: 0x34ee0cc VA: 0x7595b060cc
	public Boolean ValidDimensions(Texture2D tex2D) { }
	// RVA: 0x34ed5b4 VA: 0x7595b055b4
	protected Void ConvertBaseTexture() { }
	// RVA: 0x34ee1d0 VA: 0x7595b061d0
	public Void Apply(Texture source, RenderTexture destination) { }
	// RVA: 0x34ee304 VA: 0x7595b06304
	protected virtual Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ee3f8 VA: 0x7595b063f8
	protected virtual Void RenderLut2D(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34ee5ac VA: 0x7595b065ac
	protected virtual Void RenderLut3D(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34edab8 VA: 0x7595b05ab8
	public Void .ctor() { }
}
```