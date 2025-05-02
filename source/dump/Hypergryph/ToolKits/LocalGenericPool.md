# LocalGenericPool

**Namespace:** `Hypergryph.ToolKits`


## Methods

- `T Get()`

- `Void Release(T)`

- `Void _OnRelease(Object)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.ToolKits
public class LocalGenericPool`1
{
	private const Int32 DEFAULT_LOCAL_POOL_SIZE; // 0x0
	private readonly ObjectPool m_pool; // 0x0
	private readonly Action`1 m_actionOnRelease; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(Action`1 actionOnRelease, Int32 poolSize) { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x VA: 0x0
	public Void Release(T item) { }
	// RVA: 0x VA: 0x0
	private Void _OnRelease(Object obj) { }
}
```