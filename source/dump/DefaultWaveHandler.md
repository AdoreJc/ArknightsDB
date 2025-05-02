# DefaultWaveHandler

**Namespace:** ` `


## Fields

- `Scheduler m_scheduler`


## Properties

- `Scheduler scheduler`


## Methods

- `Scheduler get_scheduler()`

- `Void OnActionExecuted(ActionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DefaultWaveHandler : IHotfixable
{
	private Scheduler m_scheduler; // 0x10
	private static DelegateBridge __Hotfix0_get_scheduler; // 0x0
	private static DelegateBridge __Hotfix0_get_actionExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnActionExecuted; // 0x10
	private static DelegateBridge __Hotfix0_get_actionQueue; // 0x18
	private static DelegateBridge __Hotfix0_get_skipCurWave; // 0x20
	private static DelegateBridge __Hotfix0_WaitForPredelay; // 0x28
	private static DelegateBridge __Hotfix0_WaitForPostDelay; // 0x30
	private static DelegateBridge __Hotfix0_ExecuteActionQueue; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected Scheduler scheduler { get; }
	protected Func`3[] actionExecutors { get; }
	protected List`1 actionQueue { get; }
	public virtual Boolean skipCurWave { get; }

	// RVA: 0x40d929c VA: 0x75966f129c
	protected Scheduler get_scheduler() { }
	// RVA: 0x40d934c VA: 0x75966f134c
	protected Func`3[] get_actionExecutors() { }
	// RVA: 0x40d93c4 VA: 0x75966f13c4
	public Void OnActionExecuted(ActionData data) { }
	// RVA: 0x40d9450 VA: 0x75966f1450
	protected List`1 get_actionQueue() { }
	// RVA: 0x40d94c8 VA: 0x75966f14c8
	public virtual Boolean get_skipCurWave() { }
	// RVA: 0x40d952c VA: 0x75966f152c
	public virtual IEnumerator WaitForPredelay(WaveData wave) { }
	// RVA: 0x40d9614 VA: 0x75966f1614
	public virtual IEnumerator WaitForPostDelay(WaveData wave) { }
	// RVA: 0x40d96fc VA: 0x75966f16fc
	public virtual IEnumerator ExecuteActionQueue() { }
	// RVA: 0x40d97d0 VA: 0x75966f17d0
	public Void .ctor() { }
}
```