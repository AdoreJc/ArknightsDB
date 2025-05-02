# MonoBehaviourWrapped

**Namespace:** `BitBenderGames`


## Fields

- `Transform cachedTransform`

- `GameObject cachedGO`


## Properties

- `Transform Transform`

- `GameObject GameObject`


## Methods

- `Transform get_Transform()`

- `GameObject get_GameObject()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class MonoBehaviourWrapped : MonoBehaviour
{
	protected Transform cachedTransform; // 0x18
	protected GameObject cachedGO; // 0x20

	public Transform Transform { get; }
	public GameObject GameObject { get; }

	// RVA: 0x2c20d88 VA: 0x7595238d88
	public Transform get_Transform() { }
	// RVA: 0x2c2abf0 VA: 0x7595242bf0
	public GameObject get_GameObject() { }
	// RVA: 0x2c2a428 VA: 0x7595242428
	public Void .ctor() { }
}
```