# EventCallbackRegistry

**Namespace:** `UnityEngine.UIElements`


## Fields

- `EventCallbackList m_Callbacks`

- `EventCallbackList m_TemporaryCallbacks`

- `Int32 m_IsInvoking`


## Methods

- `EventCallbackList GetCallbackListForWriting()`

- `EventCallbackList GetCallbackListForReading()`

- `Boolean UnregisterCallback(Int64, Delegate, TrickleDown)`

- `Void RegisterCallback(EventCallback`1, TrickleDown, InvokePolicy)`

- `Boolean UnregisterCallback(EventCallback`1, TrickleDown)`

- `Void InvokeCallbacks(EventBase, PropagationPhase)`

- `Boolean HasTrickleDownHandlers()`

- `Boolean HasBubbleHandlers()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class EventCallbackRegistry
{
	private static readonly EventCallbackListPool s_ListPool; // 0x0
	private EventCallbackList m_Callbacks; // 0x10
	private EventCallbackList m_TemporaryCallbacks; // 0x18
	private Int32 m_IsInvoking; // 0x20


	// RVA: 0x69e1944 VA: 0x7598ff9944
	private static EventCallbackList GetCallbackList(EventCallbackList initializer) { }
	// RVA: 0x69e19ac VA: 0x7598ff99ac
	private static Void ReleaseCallbackList(EventCallbackList toRelease) { }
	// RVA: 0x69e1a14 VA: 0x7598ff9a14
	public Void .ctor() { }
	// RVA: 0x69e1a30 VA: 0x7598ff9a30
	private EventCallbackList GetCallbackListForWriting() { }
	// RVA: 0x69e1b04 VA: 0x7598ff9b04
	private EventCallbackList GetCallbackListForReading() { }
	// RVA: 0x69e1b20 VA: 0x7598ff9b20
	private Boolean UnregisterCallback(Int64 eventTypeId, Delegate callback, TrickleDown useTrickleDown) { }
	// RVA: 0x VA: 0x0
	public Void RegisterCallback(EventCallback`1 callback, TrickleDown useTrickleDown, InvokePolicy invokePolicy) { }
	// RVA: 0x VA: 0x0
	public Boolean UnregisterCallback(EventCallback`1 callback, TrickleDown useTrickleDown) { }
	// RVA: 0x69e1b74 VA: 0x7598ff9b74
	public Void InvokeCallbacks(EventBase evt, PropagationPhase propagationPhase) { }
	// RVA: 0x69e1d34 VA: 0x7598ff9d34
	public Boolean HasTrickleDownHandlers() { }
	// RVA: 0x69e1d54 VA: 0x7598ff9d54
	public Boolean HasBubbleHandlers() { }
	// RVA: 0x69e1d74 VA: 0x7598ff9d74
	private static Void .cctor() { }
}
```