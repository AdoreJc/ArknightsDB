# CommandExecutorWrapper

**Namespace:** `Torappu.AVG`


## Fields

- `CommandExecuteDelegate m_executor`

- `RaiseSignalDelegate m_signalReceiver`

- `Action m_forceEnd`

- `Command m_cachedCmd`

- `String <command>k__BackingField`


## Properties

- `String command`


## Methods

- `String get_command()`

- `Void set_command(String)`

- `Void Execute(Command, Action`1)`

- `Void RaiseSignal(Command)`

- `Void ForceEnd()`

- `Void _OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class CommandExecutorWrapper : ICommandExecutor, IHotfixable
{
	private CommandExecuteDelegate m_executor; // 0x10
	private RaiseSignalDelegate m_signalReceiver; // 0x18
	private Action m_forceEnd; // 0x20
	private Action`1 m_finishCb; // 0x28
	private Command m_cachedCmd; // 0x30
	private String <command>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_command; // 0x0
	private static DelegateBridge __Hotfix0_set_command; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge __Hotfix0_RaiseSignal; // 0x20
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x28
	private static DelegateBridge __Hotfix0__OnFinish; // 0x30

	public String command { get; set; }

	// RVA: 0x3e5dbdc VA: 0x7596475bdc
	public String get_command() { }
	// RVA: 0x3e5dc44 VA: 0x7596475c44
	private Void set_command(String value) { }
	// RVA: 0x3e5dcc8 VA: 0x7596475cc8
	public Void .ctor(String command, CommandExecuteDelegate executor, Action forceEnd, RaiseSignalDelegate signalReceiver) { }
	// RVA: 0x3e5ddac VA: 0x7596475dac
	public Void Execute(Command command, Action`1 finishCb) { }
	// RVA: 0x3e5deb8 VA: 0x7596475eb8
	public Void RaiseSignal(Command command) { }
	// RVA: 0x3e5df58 VA: 0x7596475f58
	public Void ForceEnd() { }
	// RVA: 0x3e5dfd8 VA: 0x7596475fd8
	private Void _OnFinish() { }
}
```