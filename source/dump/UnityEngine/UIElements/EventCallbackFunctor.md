# EventCallbackFunctor

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class EventCallbackFunctor`1 : EventCallbackFunctorBase
{
	private readonly EventCallback`1 m_Callback; // 0x0
	private readonly Int64 m_EventTypeId; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(EventCallback`1 callback, CallbackPhase phase, InvokePolicy invokePolicy) { }
	// RVA: 0x VA: 0x0
	public override Void Invoke(EventBase evt, PropagationPhase propagationPhase) { }
	// RVA: 0x VA: 0x0
	public override Boolean IsEquivalentTo(Int64 eventTypeId, Delegate callback, CallbackPhase phase) { }
}
```