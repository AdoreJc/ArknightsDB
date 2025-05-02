# ResourceRequest

**Namespace:** `UnityEngine`


## Properties

- `Object asset`


## Methods

- `Object get_asset()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class ResourceRequest : AsyncOperation
{
	internal String m_Path; // 0x20
	internal Type m_Type; // 0x28

	public Object asset { get; }

	// RVA: 0x6881540 VA: 0x7598e99540
	protected virtual Object GetResult() { }
	// RVA: 0x68815c4 VA: 0x7598e995c4
	public Object get_asset() { }
	// RVA: 0x68815d0 VA: 0x7598e995d0
	public Void .ctor() { }
}
```