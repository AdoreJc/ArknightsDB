# LoopRequestSender

**Namespace:** `Torappu.UI`


## Fields

- `SenderContext m_context`

- `ICoroutineHost m_coroutineHost`

- `RequestTask m_activeTask`


## Methods

- `Void StartRequest()`

- `IEnumerator _StartNewTaskSafely(RequestTask, RequestTask)`

- `Void TryRequestCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LoopRequestSender : IHotfixable
{
	private const Single TICK_INTERVAL; // 0x0
	private SenderContext m_context; // 0x10
	private ICoroutineHost m_coroutineHost; // 0x18
	private RequestTask m_activeTask; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_StartRequest; // 0x8
	private static DelegateBridge __Hotfix0__StartNewTaskSafely; // 0x10
	private static DelegateBridge __Hotfix0_TryRequestCancel; // 0x18
	private static DelegateBridge __Hotfix0__LoopSendRequest; // 0x20
	private static DelegateBridge __Hotfix0__CancelIfNeed; // 0x28


	// RVA: 0x2225b10 VA: 0x759483db10
	public Void .ctor(SenderContext context) { }
	// RVA: 0x2225bb0 VA: 0x759483dbb0
	public Void StartRequest() { }
	// RVA: 0x2225f0c VA: 0x759483df0c
	private IEnumerator _StartNewTaskSafely(RequestTask prevTask, RequestTask newTask) { }
	// RVA: 0x222600c VA: 0x759483e00c
	public Void TryRequestCancel() { }
	// RVA: 0x2226100 VA: 0x759483e100
	private static IEnumerator _LoopSendRequest(RequestTask currTask) { }
	// RVA: 0x22261d4 VA: 0x759483e1d4
	private static IEnumerator _CancelIfNeed(RequestTask currTask) { }
}
```