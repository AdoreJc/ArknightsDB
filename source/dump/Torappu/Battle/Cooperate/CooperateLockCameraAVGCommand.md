# CooperateLockCameraAVGCommand

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
public class CooperateLockCameraAVGCommand : ICommandExecutor, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_command; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x10
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String command { get; }

	// RVA: 0x1c6481c VA: 0x759427c81c
	public String get_command() { }
	// RVA: 0x1c64898 VA: 0x759427c898
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x1c649f4 VA: 0x759427c9f4
	public Void RaiseSignal(Command command) { }
	// RVA: 0x1c64a6c VA: 0x759427ca6c
	public Void ForceEnd() { }
	// RVA: 0x1c64ad0 VA: 0x759427cad0
	public Void .ctor() { }
}
```