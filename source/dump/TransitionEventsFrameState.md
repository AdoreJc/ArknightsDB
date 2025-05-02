# TransitionEventsFrameState

**Namespace:** ` `


## Fields

- `IPanel panel`

- `Int32 m_ChangesCount`


## Methods

- `Void RegisterChange()`

- `Void UnregisterChange()`

- `Boolean StateChanged()`

- `Void Clear()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class TransitionEventsFrameState
{
	private static readonly ObjectPool`1 k_EventQueuePool; // 0x0
	public readonly Dictionary`2 elementPropertyStateDelta; // 0x0
	public readonly Dictionary`2 elementPropertyQueuedEvents; // 0x0
	public IPanel panel; // 0x0
	private Int32 m_ChangesCount; // 0x0


	// RVA: 0x VA: 0x0
	public static Queue`1 GetPooledQueue() { }
	// RVA: 0x VA: 0x0
	public Void RegisterChange() { }
	// RVA: 0x VA: 0x0
	public Void UnregisterChange() { }
	// RVA: 0x VA: 0x0
	public Boolean StateChanged() { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```