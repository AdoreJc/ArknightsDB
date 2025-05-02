# SDKExtraInfoBridge

**Namespace:** `Torappu.SDK`


## Fields

- `Boolean m_isInited`


## Methods

- `Boolean _InitIfNot()`

- `Void Dispose()`

- `Void _GT3MessageEvent(GT3Message)`

- `Void _CloudAuthMessageEvent(CloudAuthMessage)`

- `Void _UnbindGrantMsgEvent(UnbindGrantMessage)`

- `Void CallGT3Message(String, Action`1)`

- `Void CallCloudAuthMessage(String, Action`1)`

- `Void BindMsgObserver(Object, Action`1)`

- `Boolean UnbindMsgObserver(Object)`

- `Void _TriggerMsgEvents(InfoType)`

- `Void _DoActionWithCallback(Action, Action`1, Boolean)`

- `Void _BindCallback(Action`1)`

- `Boolean _CheckIfInvoking()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKExtraInfoBridge : Singleton`1, IDisposable
{
	private Dictionary`2 m_callbackMap; // 0x10
	private Dictionary`2 m_observerMap; // 0x18
	private Boolean m_isInited; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10
	private static DelegateBridge __Hotfix0__GT3MessageEvent; // 0x18
	private static DelegateBridge __Hotfix0__CloudAuthMessageEvent; // 0x20
	private static DelegateBridge __Hotfix0__UnbindGrantMsgEvent; // 0x28
	private static DelegateBridge __Hotfix0_CallGT3Message; // 0x30
	private static DelegateBridge __Hotfix0_CallCloudAuthMessage; // 0x38
	private static DelegateBridge __Hotfix0_BindMsgObserver; // 0x40
	private static DelegateBridge __Hotfix0_UnbindMsgObserver; // 0x48
	private static DelegateBridge __Hotfix0__TriggerMsgEvents; // 0x50
	private static DelegateBridge __Hotfix0__DoActionWithCallback; // 0x58
	private static DelegateBridge __Hotfix0__BindCallback; // 0x60
	private static DelegateBridge __Hotfix0__CheckIfInvoking; // 0x68


	// RVA: 0x3577cf4 VA: 0x7595b8fcf4
	private Void .ctor() { }
	// RVA: 0x3577e28 VA: 0x7595b8fe28
	private Boolean _InitIfNot() { }
	// RVA: 0x3578680 VA: 0x7595b90680
	public Void Dispose() { }
	// RVA: 0x3578864 VA: 0x7595b90864
	private Void _GT3MessageEvent(GT3Message msg) { }
	// RVA: 0x3578908 VA: 0x7595b90908
	private Void _CloudAuthMessageEvent(CloudAuthMessage msg) { }
	// RVA: 0x35789cc VA: 0x7595b909cc
	private Void _UnbindGrantMsgEvent(UnbindGrantMessage msg) { }
	// RVA: 0x3578a70 VA: 0x7595b90a70
	public Void CallGT3Message(String captchaData, Action`1 callback) { }
	// RVA: 0x3578ba8 VA: 0x7595b90ba8
	public Void CallCloudAuthMessage(String token, Action`1 callback) { }
	// RVA: 0x VA: 0x0
	public Void BindMsgObserver(Object binder, Action`1 callback) { }
	// RVA: 0x VA: 0x0
	public Boolean UnbindMsgObserver(Object binder) { }
	// RVA: 0x VA: 0x0
	private Void _TriggerMsgEvents(InfoType result) { }
	// RVA: 0x VA: 0x0
	private Void _DoActionWithCallback(Action invoke, Action`1 callback, Boolean useBlocker) { }
	// RVA: 0x VA: 0x0
	private Void _BindCallback(Action`1 callback) { }
	// RVA: 0x VA: 0x0
	private Boolean _CheckIfInvoking() { }
}
```