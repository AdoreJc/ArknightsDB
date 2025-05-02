# EmptyRequestHandler

**Namespace:** ` `


## Properties

- `JsonSerializerSettings serializeSettings`


## Methods

- `JsonSerializerSettings get_serializeSettings()`

- `Void BeforeRequest(Request)`

- `Void MarkRequestFinish(Request)`

- `String SerializeRequest(Request)`

- `CustomYieldInstruction DeserializeResposne(String)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class EmptyRequestHandler : IRequestHandler
{

	public JsonSerializerSettings serializeSettings { get; }

	// RVA: 0x67b1e70 VA: 0x7598dc9e70
	public JsonSerializerSettings get_serializeSettings() { }
	// RVA: 0x67b1f08 VA: 0x7598dc9f08
	public Void BeforeRequest(Request request) { }
	// RVA: 0x67b1f2c VA: 0x7598dc9f2c
	public Void MarkRequestFinish(Request request) { }
	// RVA: 0x67b1f50 VA: 0x7598dc9f50
	public String SerializeRequest(Request request) { }
	// RVA: 0x VA: 0x0
	public CustomYieldInstruction DeserializeResposne(String responseText) { }
	// RVA: 0x VA: 0x0
	public RespMsgBundle`1 HandleResponse(CustomYieldInstruction deserializeTask) { }
	// RVA: 0x67b1e94 VA: 0x7598dc9e94
	private static Exception _NotImplemented() { }
	// RVA: 0x67b1e68 VA: 0x7598dc9e68
	public Void .ctor() { }
}
```