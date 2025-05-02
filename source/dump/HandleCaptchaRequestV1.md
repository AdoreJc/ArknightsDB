# HandleCaptchaRequestV1

**Namespace:** ` `


## Fields

- `MessageRequest m_requestParam`

- `Action onFail`

- `Action onMessageFail`


## Methods

- `Void Request(MessageRequest)`

- `Void _CallRequest(MessageRequest)`

- `Void _HandleMessage(LoginProceedInfo)`

- `Void _OnGT3Message(GT3Message)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HandleCaptchaRequestV1`2 : IHotfixable
{
	private MessageRequest m_requestParam; // 0x0
	public Func`2 requestFuc; // 0x0
	public Action`1 onSuc; // 0x0
	public Action onFail; // 0x0
	public Action onMessageFail; // 0x0
	private static DelegateBridge __Hotfix0_Request; // 0x0
	private static DelegateBridge __Hotfix0__CallRequest; // 0x0
	private static DelegateBridge __Hotfix0__HandleMessage; // 0x0
	private static DelegateBridge __Hotfix0__OnGT3Message; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x VA: 0x0
	public Void Request(MessageRequest param) { }
	// RVA: 0x VA: 0x0
	private Void _CallRequest(MessageRequest param) { }
	// RVA: 0x VA: 0x0
	private Void _HandleMessage(LoginProceedInfo info) { }
	// RVA: 0x VA: 0x0
	private Void _OnGT3Message(GT3Message msg) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```