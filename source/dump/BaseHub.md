# BaseHub

**Namespace:** ` `


## Fields

- `String Title`

- `GUIMessageList messages`


## Methods

- `Void Joined(Hub, MethodCallMessage)`

- `Void Rejoined(Hub, MethodCallMessage)`

- `Void Left(Hub, MethodCallMessage)`

- `Void Invoked(Hub, MethodCallMessage)`

- `Void InvokedFromClient()`

- `Void OnInvoked(Hub, ClientMessage, ResultMessage)`

- `Void OnInvokeFailed(Hub, ClientMessage, FailureMessage)`

- `Void Draw()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
internal class BaseHub : Hub
{
	private String Title; // 0x48
	private GUIMessageList messages; // 0x50


	// RVA: 0x644a8f8 VA: 0x7598a628f8
	public Void .ctor(String name, String title) { }
	// RVA: 0x644b5a0 VA: 0x7598a635a0
	private Void Joined(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644b878 VA: 0x7598a63878
	private Void Rejoined(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644b904 VA: 0x7598a63904
	private Void Left(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644b990 VA: 0x7598a63990
	private Void Invoked(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644ace8 VA: 0x7598a62ce8
	public Void InvokedFromClient() { }
	// RVA: 0x644ba1c VA: 0x7598a63a1c
	private Void OnInvoked(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x644baa8 VA: 0x7598a63aa8
	private Void OnInvokeFailed(Hub hub, ClientMessage originalMessage, FailureMessage result) { }
	// RVA: 0x644b480 VA: 0x7598a63480
	public Void Draw() { }
}
```