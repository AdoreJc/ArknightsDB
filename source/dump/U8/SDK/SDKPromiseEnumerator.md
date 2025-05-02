# SDKPromiseEnumerator

**Namespace:** `U8.SDK`


## Fields

- `State m_state`

- `T <result>k__BackingField`

- `Object <reject>k__BackingField`


## Properties

- `Boolean isFulfilled`

- `T result`

- `Object reject`


## Methods

- `Boolean get_isFulfilled()`

- `T get_result()`

- `Void set_result(T)`

- `Object get_reject()`

- `Void set_reject(Object)`

- `IEnumerator Yield()`

- `Void _OnFulfilled(T)`

- `Void _OnRejected(Object)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKPromiseEnumerator`1
{
	private State m_state; // 0x0
	private T <result>k__BackingField; // 0x0
	private Object <reject>k__BackingField; // 0x0

	public Boolean isFulfilled { get; }
	public T result { get; set; }
	public Object reject { get; set; }

	// RVA: 0x VA: 0x0
	public Boolean get_isFulfilled() { }
	// RVA: 0x VA: 0x0
	public T get_result() { }
	// RVA: 0x VA: 0x0
	private Void set_result(T value) { }
	// RVA: 0x VA: 0x0
	public Object get_reject() { }
	// RVA: 0x VA: 0x0
	private Void set_reject(Object value) { }
	// RVA: 0x VA: 0x0
	public IEnumerator Yield() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(SDKPromise`1 promise) { }
	// RVA: 0x VA: 0x0
	private Void _OnFulfilled(T result) { }
	// RVA: 0x VA: 0x0
	private Void _OnRejected(Object rejectInfo) { }
}
```