# RequestTask

**Namespace:** ` `


## Fields

- `IRequestSendHandler m_initRequestHandler`

- `IRequestSendHandler m_queryRequestHandler`

- `IRequestSendHandler m_cancelRequestHandler`

- `IRequestWaitStrategy m_waitStrategy`

- `Boolean m_hasCancelOp`

- `Boolean m_isFinish`

- `Coroutine taskCoroutine`


## Properties

- `IRequestSendHandler initRequestHandler`

- `IRequestSendHandler queryRequestHandler`

- `IRequestSendHandler cancelRequestHandler`


## Methods

- `IRequestSendHandler get_initRequestHandler()`

- `IRequestSendHandler get_queryRequestHandler()`

- `IRequestSendHandler get_cancelRequestHandler()`

- `Void TriggerTick(Single)`

- `Boolean IsWaitEnough(Single)`

- `Boolean IsFinish()`

- `Void MarkFinish()`

- `Boolean IsCancel()`

- `Void MarkCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RequestTask : IHotfixable
{
	private IRequestSendHandler m_initRequestHandler; // 0x10
	private IRequestSendHandler m_queryRequestHandler; // 0x18
	private IRequestSendHandler m_cancelRequestHandler; // 0x20
	private IRequestWaitStrategy m_waitStrategy; // 0x28
	private Boolean m_hasCancelOp; // 0x30
	private Boolean m_isFinish; // 0x31
	private Action`1 m_onTick; // 0x38
	public Coroutine taskCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_get_initRequestHandler; // 0x0
	private static DelegateBridge __Hotfix0_get_queryRequestHandler; // 0x8
	private static DelegateBridge __Hotfix0_get_cancelRequestHandler; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_Create; // 0x20
	private static DelegateBridge __Hotfix0_TriggerTick; // 0x28
	private static DelegateBridge __Hotfix0_IsWaitEnough; // 0x30
	private static DelegateBridge __Hotfix0_IsFinish; // 0x38
	private static DelegateBridge __Hotfix0_MarkFinish; // 0x40
	private static DelegateBridge __Hotfix0_IsCancel; // 0x48
	private static DelegateBridge __Hotfix0_MarkCancel; // 0x50

	public IRequestSendHandler initRequestHandler { get; }
	public IRequestSendHandler queryRequestHandler { get; }
	public IRequestSendHandler cancelRequestHandler { get; }

	// RVA: 0x22262b8 VA: 0x759483e2b8
	public IRequestSendHandler get_initRequestHandler() { }
	// RVA: 0x2226320 VA: 0x759483e320
	public IRequestSendHandler get_queryRequestHandler() { }
	// RVA: 0x2226388 VA: 0x759483e388
	public IRequestSendHandler get_cancelRequestHandler() { }
	// RVA: 0x22263f0 VA: 0x759483e3f0
	private Void .ctor() { }
	// RVA: 0x2225dc4 VA: 0x759483ddc4
	public static RequestTask Create(SenderContext context) { }
	// RVA: 0x2226460 VA: 0x759483e460
	public Void TriggerTick(Single totalSec) { }
	// RVA: 0x2226500 VA: 0x759483e500
	public Boolean IsWaitEnough(Single waitSecFromPrev) { }
	// RVA: 0x2226098 VA: 0x759483e098
	public Boolean IsFinish() { }
	// RVA: 0x2226600 VA: 0x759483e600
	public Void MarkFinish() { }
	// RVA: 0x222666c VA: 0x759483e66c
	public Boolean IsCancel() { }
	// RVA: 0x2225d48 VA: 0x759483dd48
	public Void MarkCancel() { }
}
```