# InvokableCallList

**Namespace:** `UnityEngine.Events`


## Fields

- `Boolean m_NeedsUpdate`


## Methods

- `Void AddPersistentInvokableCall(BaseInvokableCall)`

- `Void AddListener(BaseInvokableCall)`

- `Void RemoveListener(Object, MethodInfo)`

- `Void Clear()`

- `Void ClearPersistent()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Events
internal class InvokableCallList
{
	private readonly List`1 m_PersistentCalls; // 0x10
	private readonly List`1 m_RuntimeCalls; // 0x18
	private List`1 m_ExecutingCalls; // 0x20
	private Boolean m_NeedsUpdate; // 0x28


	// RVA: 0x6897b28 VA: 0x7598eafb28
	public Void AddPersistentInvokableCall(BaseInvokableCall call) { }
	// RVA: 0x6897be0 VA: 0x7598eafbe0
	public Void AddListener(BaseInvokableCall call) { }
	// RVA: 0x6897c98 VA: 0x7598eafc98
	public Void RemoveListener(Object targetObj, MethodInfo method) { }
	// RVA: 0x6897f1c VA: 0x7598eaff1c
	public Void Clear() { }
	// RVA: 0x6897fe0 VA: 0x7598eaffe0
	public Void ClearPersistent() { }
	// RVA: 0x68980a4 VA: 0x7598eb00a4
	public List`1 PrepareInvoke() { }
	// RVA: 0x6898158 VA: 0x7598eb0158
	public Void .ctor() { }
}
```