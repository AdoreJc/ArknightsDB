# SDKPromiseWrapper

**Namespace:** `U8.SDK`


## Fields

- `ISDKPromise m_promise`


## Methods

- `T EnsurePromise()`

- `Void Fulfill(Object)`

- `Void Reject(Object)`

- `Void _Clear()`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKPromiseWrapper
{
	private ISDKPromise m_promise; // 0x10


	// RVA: 0x VA: 0x0
	public T EnsurePromise() { }
	// RVA: 0x67ddfd0 VA: 0x7598df5fd0
	public Void Fulfill(Object param) { }
	// RVA: 0x67de09c VA: 0x7598df609c
	public Void Reject(Object reason) { }
	// RVA: 0x67e559c VA: 0x7598dfd59c
	private Void _Clear() { }
	// RVA: 0x67e0df0 VA: 0x7598df8df0
	public Void .ctor() { }
}
```