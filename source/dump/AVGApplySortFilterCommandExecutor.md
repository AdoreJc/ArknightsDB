# AVGApplySortFilterCommandExecutor

**Namespace:** ` `


## Fields

- `CharSelectStateBean m_stateBean`


## Properties

- `String command`


## Methods

- `String get_command()`

- `Void Execute(Command, Action`1)`

- `Void RaiseSignal(Command)`

- `Void ForceEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AVGApplySortFilterCommandExecutor : ICommandExecutor, IHotfixable
{
	private CharSelectStateBean m_stateBean; // 0x10
	private static DelegateBridge __Hotfix0_get_command; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x18
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x20

	public String command { get; }

	// RVA: 0x2ceddb0 VA: 0x7595305db0
	public String get_command() { }
	// RVA: 0x2cede2c VA: 0x7595305e2c
	public Void .ctor(CharSelectStateBean stateBean) { }
	// RVA: 0x2cedec0 VA: 0x7595305ec0
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x2cee22c VA: 0x759530622c
	public Void RaiseSignal(Command command) { }
	// RVA: 0x2cee2a4 VA: 0x75953062a4
	public Void ForceEnd() { }
}
```