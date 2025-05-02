# UniWebViewEventProcessor

**Namespace:** ` `


## Fields

- `Object _queueLock`


## Methods

- `Void QueueEvent(Action)`

- `Void Update()`

- `Void MoveQueuedEventsToExecuting()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class UniWebViewEventProcessor : MonoBehaviour
{
	private Object _queueLock; // 0x18
	private List`1 _queuedEvents; // 0x20
	private List`1 _executingEvents; // 0x28
	private static UniWebViewEventProcessor _instance; // 0x0

	public static UniWebViewEventProcessor instance { get; }

	// RVA: 0x64672d8 VA: 0x7598a7f2d8
	public static UniWebViewEventProcessor get_instance() { }
	// RVA: 0x6467520 VA: 0x7598a7f520
	public Void QueueEvent(Action action) { }
	// RVA: 0x6467674 VA: 0x7598a7f674
	private Void Update() { }
	// RVA: 0x6467740 VA: 0x7598a7f740
	private Void MoveQueuedEventsToExecuting() { }
	// RVA: 0x646791c VA: 0x7598a7f91c
	public Void .ctor() { }
}
```