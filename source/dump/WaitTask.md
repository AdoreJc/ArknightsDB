# WaitTask

**Namespace:** ` `


## Fields

- `Boolean m_keepWaiting`

- `Int32 timeoutFrameCnt`

- `Boolean <isDisposed>k__BackingField`


## Properties

- `Boolean isDisposed`

- `Boolean keepWaiting`


## Methods

- `Boolean get_isDisposed()`

- `Void set_isDisposed(Boolean)`

- `Boolean get_keepWaiting()`

- `Void Dispose()`

- `Void StopWait()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class WaitTask
{
	private Boolean m_keepWaiting; // 0x0
	public Int32 timeoutFrameCnt; // 0x0
	public Func`2 condition; // 0x0
	private Boolean <isDisposed>k__BackingField; // 0x0

	public Boolean isDisposed { get; set; }
	public Boolean keepWaiting { get; }

	// RVA: 0x VA: 0x0
	public Boolean get_isDisposed() { }
	// RVA: 0x VA: 0x0
	private Void set_isDisposed(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Boolean get_keepWaiting() { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Void StopWait() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```