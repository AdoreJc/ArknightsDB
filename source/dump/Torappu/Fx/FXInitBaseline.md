# FXInitBaseline

**Namespace:** `Torappu.Fx`


## Fields

- `Transform _host`

- `MaterialPropertyBlock m_propertyBlock`

- `Renderer m_renderer`


## Properties

- `MaterialPropertyBlock PropertyBlock`


## Methods

- `MaterialPropertyBlock get_PropertyBlock()`

- `Void Awake()`

- `Void OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FXInitBaseline : MonoBehaviour
{
	public Transform _host; // 0x18
	private MaterialPropertyBlock m_propertyBlock; // 0x20
	private Renderer m_renderer; // 0x28

	private MaterialPropertyBlock PropertyBlock { get; }

	// RVA: 0x3efcf94 VA: 0x7596514f94
	private MaterialPropertyBlock get_PropertyBlock() { }
	// RVA: 0x3efd00c VA: 0x759651500c
	private Void Awake() { }
	// RVA: 0x3efd064 VA: 0x7596515064
	private Void OnEnable() { }
	// RVA: 0x3efd144 VA: 0x7596515144
	public Void .ctor() { }
}
```