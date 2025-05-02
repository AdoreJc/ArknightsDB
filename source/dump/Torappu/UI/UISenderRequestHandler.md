# UISenderRequestHandler

**Namespace:** `Torappu.UI`


## Fields

- `CreateRequestAction m_onCreateRequest`


## Methods

- `RequestResult SendRequest()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISenderRequestHandler`1 : IRequestSendHandler, IHotfixable
{
	private CreateRequestAction m_onCreateRequest; // 0x0
	private Func`2 m_onResponse; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CreateSendHandler; // 0x0
	private static DelegateBridge __Hotfix0_SendRequest; // 0x0


	// RVA: 0x VA: 0x0
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public static UISenderRequestHandler`1 CreateSendHandler(HandlerParam handlerParam) { }
	// RVA: 0x VA: 0x0
	public RequestResult SendRequest() { }
}
```