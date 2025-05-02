# CooperateMoveCameraAVGCommand

**Namespace:** `Torappu.Battle.Cooperate`


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
// Namespace : Torappu.Battle.Cooperate
public class CooperateMoveCameraAVGCommand : ICommandExecutor, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_command; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x10
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String command { get; }

	// RVA: 0x1c642f8 VA: 0x759427c2f8
	public String get_command() { }
	// RVA: 0x1c64374 VA: 0x759427c374
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x1c646d0 VA: 0x759427c6d0
	public Void RaiseSignal(Command command) { }
	// RVA: 0x1c64748 VA: 0x759427c748
	public Void ForceEnd() { }
	// RVA: 0x1c647ac VA: 0x759427c7ac
	public Void .ctor() { }
}
```