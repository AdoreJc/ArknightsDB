# DelayHandler

**Namespace:** ` `


## Fields

- `Boolean m_isDelayProcessing`


## Methods

- `Boolean SetDelay(Action, Single)`

- `Boolean IsRunning()`

- `Void InterruptDelay()`

- `Void _InvokeNextAction(Action, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DelayHandler : IHotfixable
{
	private Boolean m_isDelayProcessing; // 0x10
	private static DelegateBridge __Hotfix0_SetDelay; // 0x0
	private static DelegateBridge __Hotfix0_IsRunning; // 0x8
	private static DelegateBridge __Hotfix0_InterruptDelay; // 0x10
	private static DelegateBridge __Hotfix0__InvokeNextAction; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30ccc9c VA: 0x75956e4c9c
	public Boolean SetDelay(Action nextAction, Single delay) { }
	// RVA: 0x30cce64 VA: 0x75956e4e64
	public Boolean IsRunning() { }
	// RVA: 0x30cf8b8 VA: 0x75956e78b8
	public Void InterruptDelay() { }
	// RVA: 0x30cf920 VA: 0x75956e7920
	private Void _InvokeNextAction(Action nextAction, Boolean interrupted) { }
	// RVA: 0x30cf12c VA: 0x75956e712c
	public Void .ctor() { }
}
```