# AVGResetToActEntryCommandExecutor

**Namespace:** ` `


## Fields

- `TemplateActivityController m_actController`


## Properties

- `String command`


## Methods

- `String get_command()`

- `Void Execute(Command, Action`1)`

- `Void ForceEnd()`

- `Void RaiseSignal(Command)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AVGResetToActEntryCommandExecutor : ICommandExecutor, IHotfixable
{
	private const String RESET_TO_ENTRY_COMMAND; // 0x0
	private TemplateActivityController m_actController; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_command; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x18
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x20

	public String command { get; }

	// RVA: 0x309fd80 VA: 0x75956b7d80
	public Void .ctor(TemplateActivityController templateActivityController) { }
	// RVA: 0x30a1690 VA: 0x75956b9690
	public String get_command() { }
	// RVA: 0x30a170c VA: 0x75956b970c
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x30a17c0 VA: 0x75956b97c0
	public Void ForceEnd() { }
	// RVA: 0x30a1824 VA: 0x75956b9824
	public Void RaiseSignal(Command command) { }
}
```