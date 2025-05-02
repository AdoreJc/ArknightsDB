# ConnectionGroup

**Namespace:** ` `


## Properties

- `ServicePointScheduler Scheduler`


## Methods

- `ServicePointScheduler get_Scheduler()`

- `Boolean IsEmpty()`

- `Void RemoveConnection(WebConnection)`

- `Void Cleanup()`

- `Void EnqueueOperation(WebOperation)`

- `WebOperation GetNextOperation()`

- `WebConnection FindIdleConnection(WebOperation)`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class ConnectionGroup
{
	private readonly ServicePointScheduler <Scheduler>k__BackingField; // 0x10
	private readonly String <Name>k__BackingField; // 0x18
	private static Int32 nextId; // 0x0
	public readonly Int32 ID; // 0x20
	private LinkedList`1 connections; // 0x28
	private LinkedList`1 queue; // 0x30

	public ServicePointScheduler Scheduler { get; }

	// RVA: 0x63337e0 VA: 0x759894b7e0
	public ServicePointScheduler get_Scheduler() { }
	// RVA: 0x6331f28 VA: 0x7598949f28
	public Void .ctor(ServicePointScheduler scheduler, String name) { }
	// RVA: 0x6332634 VA: 0x759894a634
	public Boolean IsEmpty() { }
	// RVA: 0x6332d70 VA: 0x759894ad70
	public Void RemoveConnection(WebConnection connection) { }
	// RVA: 0x6332ec4 VA: 0x759894aec4
	public Void Cleanup() { }
	// RVA: 0x6333634 VA: 0x759894b634
	public Void EnqueueOperation(WebOperation operation) { }
	// RVA: 0x6333198 VA: 0x759894b198
	public WebOperation GetNextOperation() { }
	// RVA: 0x6333800 VA: 0x759894b800
	public WebConnection FindIdleConnection(WebOperation operation) { }
	// RVA: 0x6332fb4 VA: 0x759894afb4
	public ValueTuple`2 CreateOrReuseConnection(WebOperation operation, Boolean force) { }
}
```