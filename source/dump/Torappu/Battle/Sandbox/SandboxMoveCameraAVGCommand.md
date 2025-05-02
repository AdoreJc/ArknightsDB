# SandboxMoveCameraAVGCommand

**Namespace:** `Torappu.Battle.Sandbox`


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
// Namespace : Torappu.Battle.Sandbox
public class SandboxMoveCameraAVGCommand : ICommandExecutor, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_command; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x10
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String command { get; }

	// RVA: 0x1de2254 VA: 0x75943fa254
	public String get_command() { }
	// RVA: 0x1de22d0 VA: 0x75943fa2d0
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x1de2554 VA: 0x75943fa554
	public Void RaiseSignal(Command command) { }
	// RVA: 0x1de25cc VA: 0x75943fa5cc
	public Void ForceEnd() { }
	// RVA: 0x1de2630 VA: 0x75943fa630
	public Void .ctor() { }
}
```