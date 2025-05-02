# GameObjectPoolComponent

**Namespace:** `Torappu.ObjectPool`


## Fields

- `ObjectConfig _config`

- `GameObjectPool m_pool`


## Properties

- `GameObjectPool pool`


## Methods

- `GameObjectPool get_pool()`

- `GameObjectPool _ConstructPool(ObjectConfig)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.ObjectPool
public class GameObjectPoolComponent : MonoBehaviour
{
	private ObjectConfig _config; // 0x18
	private GameObjectPool m_pool; // 0x48

	public GameObjectPool pool { get; }

	// RVA: 0x35685dc VA: 0x7595b805dc
	public GameObjectPool get_pool() { }
	// RVA: 0x35685e4 VA: 0x7595b805e4
	private GameObjectPool _ConstructPool(ObjectConfig config) { }
	// RVA: 0x356883c VA: 0x7595b8083c
	private Void Start() { }
	// RVA: 0x356887c VA: 0x7595b8087c
	public Void .ctor() { }
}
```