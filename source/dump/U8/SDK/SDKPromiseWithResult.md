# SDKPromiseWithResult

**Namespace:** `U8.SDK`


## Fields

- `Param <result>k__BackingField`

- `Object <rejectInfo>k__BackingField`


## Properties

- `Param result`

- `Object rejectInfo`


## Methods

- `Param get_result()`

- `Void set_result(Param)`

- `Object get_rejectInfo()`

- `Void set_rejectInfo(Object)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class SDKPromiseWithResult`1 : SDKPromise`1
{
	private Param <result>k__BackingField; // 0x0
	private Object <rejectInfo>k__BackingField; // 0x0

	public Param result { get; set; }
	public Object rejectInfo { get; set; }

	// RVA: 0x VA: 0x0
	public Param get_result() { }
	// RVA: 0x VA: 0x0
	private Void set_result(Param value) { }
	// RVA: 0x VA: 0x0
	public Object get_rejectInfo() { }
	// RVA: 0x VA: 0x0
	private Void set_rejectInfo(Object value) { }
	// RVA: 0x VA: 0x0
	public override Void Fulfill(Object param) { }
	// RVA: 0x VA: 0x0
	public override Void Reject(Object reason) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```