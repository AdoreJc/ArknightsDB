# RuntimeInitializeOnLoadMethodAttribute

**Namespace:** `UnityEngine`


## Fields

- `RuntimeInitializeLoadType m_LoadType`


## Properties

- `RuntimeInitializeLoadType loadType`


## Methods

- `Void set_loadType(RuntimeInitializeLoadType)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class RuntimeInitializeOnLoadMethodAttribute : PreserveAttribute
{
	private RuntimeInitializeLoadType m_LoadType; // 0x10

	private RuntimeInitializeLoadType loadType { set; }

	// RVA: 0x6886510 VA: 0x7598e9e510
	public Void .ctor() { }
	// RVA: 0x688653c VA: 0x7598e9e53c
	public Void .ctor(RuntimeInitializeLoadType loadType) { }
	// RVA: 0x6886534 VA: 0x7598e9e534
	private Void set_loadType(RuntimeInitializeLoadType value) { }
}
```