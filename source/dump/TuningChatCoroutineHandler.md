# TuningChatCoroutineHandler

**Namespace:** ` `


## Fields

- `TuningChatController m_closure`

- `Coroutine m_activeCoroutine`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TuningChatCoroutineHandler : CoroutineHandler
{
	private TuningChatController m_closure; // 0x10
	private Coroutine m_activeCoroutine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_HandleOnEnable; // 0x8
	private static DelegateBridge __Hotfix0_HandleStartCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HandleStopCoroutine; // 0x18


	// RVA: 0x2317e30 VA: 0x759492fe30
	public Void .ctor(TuningChatController closure) { }
	// RVA: 0x2317ec4 VA: 0x759492fec4
	public override Boolean HandleOnEnable() { }
	// RVA: 0x2317f2c VA: 0x759492ff2c
	public override Coroutine HandleStartCoroutine(IEnumerator routine) { }
	// RVA: 0x2317ff0 VA: 0x759492fff0
	public override Void HandleStopCoroutine() { }
}
```