# ImageEffectBase

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Shader shader`

- `Material m_Material`


## Properties

- `Material material`


## Methods

- `Material get_material()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class ImageEffectBase : MonoBehaviour
{
	public Shader shader; // 0x18
	private Material m_Material; // 0x20

	protected Material material { get; }

	// RVA: 0x65640b0 VA: 0x7598b7c0b0
	protected virtual Void Start() { }
	// RVA: 0x6563fcc VA: 0x7598b7bfcc
	protected Material get_material() { }
	// RVA: 0x6564150 VA: 0x7598b7c150
	protected virtual Void OnDisable() { }
	// RVA: 0x65640a8 VA: 0x7598b7c0a8
	public Void .ctor() { }
}
```