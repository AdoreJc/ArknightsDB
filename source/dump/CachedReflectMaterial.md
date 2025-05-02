# CachedReflectMaterial

**Namespace:** ` `


## Methods

- `Void Clear()`

- `Void Register(Material)`

- `Void UnRegister(Material)`

- `Material GetReflMat(Material)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CachedReflectMaterial
{
	private List`1 m_cachedMaterial; // 0x10
	private Dictionary`2 m_cachedReflectMaterialCount; // 0x18
	private Dictionary`2 m_cacheMatDic; // 0x20


	// RVA: 0x35c043c VA: 0x7595bd843c
	public Void Clear() { }
	// RVA: 0x35bd478 VA: 0x7595bd5478
	public Void Register(Material mat) { }
	// RVA: 0x35bda20 VA: 0x7595bd5a20
	public Void UnRegister(Material mat) { }
	// RVA: 0x35be5a4 VA: 0x7595bd65a4
	public Material GetReflMat(Material mat) { }
	// RVA: 0x35c073c VA: 0x7595bd873c
	public Void .ctor() { }
}
```