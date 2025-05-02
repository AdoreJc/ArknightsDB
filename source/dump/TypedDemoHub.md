# TypedDemoHub

**Namespace:** ` `


## Fields

- `String typedEchoResult`

- `String typedEchoClientResult`


## Methods

- `Void Echo(Hub, MethodCallMessage)`

- `Void Echo(String)`

- `Void OnEcho_Done(Hub, ClientMessage, ResultMessage)`

- `Void Draw()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
internal class TypedDemoHub : Hub
{
	private String typedEchoResult; // 0x48
	private String typedEchoClientResult; // 0x50


	// RVA: 0x644e3d4 VA: 0x7598a663d4
	public Void .ctor() { }
	// RVA: 0x6451410 VA: 0x7598a69410
	private Void Echo(Hub hub, MethodCallMessage methodCall) { }
	// RVA: 0x644f9f0 VA: 0x7598a679f0
	public Void Echo(String msg) { }
	// RVA: 0x6451494 VA: 0x7598a69494
	private Void OnEcho_Done(Hub hub, ClientMessage originalMessage, ResultMessage result) { }
	// RVA: 0x6451214 VA: 0x7598a69214
	public Void Draw() { }
}
```