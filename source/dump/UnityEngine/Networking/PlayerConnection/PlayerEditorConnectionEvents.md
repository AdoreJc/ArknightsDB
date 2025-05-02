# PlayerEditorConnectionEvents

**Namespace:** `UnityEngine.Networking.PlayerConnection`


## Fields

- `ConnectionChangeEvent connectionEvent`

- `ConnectionChangeEvent disconnectionEvent`


## Methods

- `Void InvokeMessageIdSubscribers(Guid, Byte[], Int32)`

- `Void UnregisterManagedCallback(Guid, UnityAction`1)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Networking.PlayerConnection
internal class PlayerEditorConnectionEvents
{
	public List`1 messageTypeSubscribers; // 0x10
	public ConnectionChangeEvent connectionEvent; // 0x18
	public ConnectionChangeEvent disconnectionEvent; // 0x20


	// RVA: 0x689bcb4 VA: 0x7598eb3cb4
	public Void InvokeMessageIdSubscribers(Guid messageId, Byte[] data, Int32 playerId) { }
	// RVA: 0x689ae28 VA: 0x7598eb2e28
	public UnityEvent`1 AddAndCreate(Guid messageId) { }
	// RVA: 0x689b1dc VA: 0x7598eb31dc
	public Void UnregisterManagedCallback(Guid messageId, UnityAction`1 callback) { }
	// RVA: 0x689c390 VA: 0x7598eb4390
	public Void .ctor() { }
}
```