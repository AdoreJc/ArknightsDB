# BaseEffect

**Namespace:** `Colorful`


## Fields

- `Shader Shader`

- `Material m_Material`


## Properties

- `Shader ShaderSafe`

- `Material Material`


## Methods

- `Shader get_ShaderSafe()`

- `Material get_Material()`

- `Void Apply(Texture, RenderTexture)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class BaseEffect : MonoBehaviour
{
	public Shader Shader; // 0x18
	protected Material m_Material; // 0x20

	public Shader ShaderSafe { get; }
	public Material Material { get; }

	// RVA: 0x34e7368 VA: 0x7595aff368
	public Shader get_ShaderSafe() { }
	// RVA: 0x34e7408 VA: 0x7595aff408
	public Material get_Material() { }
	// RVA: 0x34e74e8 VA: 0x7595aff4e8
	protected virtual Void Start() { }
	// RVA: 0x34e7600 VA: 0x7595aff600
	protected virtual Void OnDisable() { }
	// RVA: 0x34e7690 VA: 0x7595aff690
	public Void Apply(Texture source, RenderTexture destination) { }
	// RVA: 0x34e77c4 VA: 0x7595aff7c4
	protected virtual Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e77c8 VA: 0x7595aff7c8
	protected virtual String GetShaderName() { }
	// RVA: 0x34e7808 VA: 0x7595aff808
	public Void .ctor() { }
}
```