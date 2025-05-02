# Process

**Namespace:** `System.Diagnostics`


## Fields

- `Boolean haveProcessId`

- `Int32 processId`

- `Boolean haveProcessHandle`

- `SafeProcessHandle m_processHandle`

- `Boolean isRemoteMachine`

- `String machineName`

- `Int32 m_processAccess`

- `ProcessThreadCollection threads`

- `ProcessModuleCollection modules`

- `Boolean haveWorkingSetLimits`

- `Boolean havePriorityClass`

- `Boolean watchForExit`

- `Boolean watchingForExit`

- `EventHandler onExited`

- `Boolean exited`

- `Int32 exitCode`

- `Boolean signaled`

- `Boolean haveExitTime`

- `Boolean raisedOnExited`

- `RegisteredWaitHandle registeredWaitHandle`

- `WaitHandle waitHandle`

- `ISynchronizeInvoke synchronizingObject`

- `StreamReader standardOutput`

- `StreamWriter standardInput`

- `StreamReader standardError`

- `Boolean disposed`

- `StreamReadMode outputStreamReadMode`

- `StreamReadMode errorStreamReadMode`

- `StreamReadMode inputStreamReadMode`

- `String process_name`


## Properties

- `Boolean Associated`

- `Boolean HasExited`

- `Int32 Id`

- `ISynchronizeInvoke SynchronizingObject`

- `String ProcessName`


## Methods

- `Boolean get_Associated()`

- `Boolean get_HasExited()`

- `Int32 get_Id()`

- `ISynchronizeInvoke get_SynchronizingObject()`

- `Void ReleaseProcessHandle(SafeProcessHandle)`

- `Void Close()`

- `Void EnsureState(State)`

- `Void OnExited()`

- `SafeProcessHandle GetProcessHandle(Int32, Boolean)`

- `SafeProcessHandle GetProcessHandle(Int32)`

- `Void Refresh()`

- `Void StopWatchingForExit()`

- `String get_ProcessName()`

- `Void RaiseOnExited()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public class Process : Component
{
	private Boolean haveProcessId; // 0x28
	private Int32 processId; // 0x2c
	private Boolean haveProcessHandle; // 0x30
	private SafeProcessHandle m_processHandle; // 0x38
	private Boolean isRemoteMachine; // 0x40
	private String machineName; // 0x48
	private Int32 m_processAccess; // 0x50
	private ProcessThreadCollection threads; // 0x58
	private ProcessModuleCollection modules; // 0x60
	private Boolean haveWorkingSetLimits; // 0x68
	private Boolean havePriorityClass; // 0x69
	private Boolean watchForExit; // 0x6a
	private Boolean watchingForExit; // 0x6b
	private EventHandler onExited; // 0x70
	private Boolean exited; // 0x78
	private Int32 exitCode; // 0x7c
	private Boolean signaled; // 0x80
	private Boolean haveExitTime; // 0x81
	private Boolean raisedOnExited; // 0x82
	private RegisteredWaitHandle registeredWaitHandle; // 0x88
	private WaitHandle waitHandle; // 0x90
	private ISynchronizeInvoke synchronizingObject; // 0x98
	private StreamReader standardOutput; // 0xa0
	private StreamWriter standardInput; // 0xa8
	private StreamReader standardError; // 0xb0
	private Boolean disposed; // 0xb8
	private StreamReadMode outputStreamReadMode; // 0xbc
	private StreamReadMode errorStreamReadMode; // 0xc0
	private StreamReadMode inputStreamReadMode; // 0xc4
	internal AsyncStreamReader output; // 0xc8
	internal AsyncStreamReader error; // 0xd0
	private String process_name; // 0xd8

	private Boolean Associated { get; }
	public Boolean HasExited { get; }
	public Int32 Id { get; }
	public ISynchronizeInvoke SynchronizingObject { get; }
	public String ProcessName { get; }

	// RVA: 0x6398894 VA: 0x75989b0894
	private Void .ctor(String machineName, Boolean isRemoteMachine, Int32 processId, ProcessInfo processInfo) { }
	// RVA: 0x639893c VA: 0x75989b093c
	private Boolean get_Associated() { }
	// RVA: 0x639895c VA: 0x75989b095c
	public Boolean get_HasExited() { }
	// RVA: 0x6396948 VA: 0x75989ae948
	public Int32 get_Id() { }
	// RVA: 0x6399408 VA: 0x75989b1408
	public ISynchronizeInvoke get_SynchronizingObject() { }
	// RVA: 0x63995bc VA: 0x75989b15bc
	private Void ReleaseProcessHandle(SafeProcessHandle handle) { }
	// RVA: 0x63995e4 VA: 0x75989b15e4
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6399634 VA: 0x75989b1634
	public Void Close() { }
	// RVA: 0x6398cc8 VA: 0x75989b0cc8
	private Void EnsureState(State state) { }
	// RVA: 0x63968c0 VA: 0x75989ae8c0
	public static Process GetCurrentProcess() { }
	// RVA: 0x6399974 VA: 0x75989b1974
	protected Void OnExited() { }
	// RVA: 0x6398e00 VA: 0x75989b0e00
	private SafeProcessHandle GetProcessHandle(Int32 access, Boolean throwIfExited) { }
	// RVA: 0x6399bcc VA: 0x75989b1bcc
	private SafeProcessHandle GetProcessHandle(Int32 access) { }
	// RVA: 0x639993c VA: 0x75989b193c
	public Void Refresh() { }
	// RVA: 0x6399808 VA: 0x75989b1808
	private Void StopWatchingForExit() { }
	// RVA: 0x6399bd4 VA: 0x75989b1bd4
	public override String ToString() { }
	// RVA: 0x6399d40 VA: 0x75989b1d40
	private static String ProcessName_icall(IntPtr handle) { }
	// RVA: 0x6399d44 VA: 0x75989b1d44
	private static String ProcessName_internal(SafeProcessHandle handle) { }
	// RVA: 0x6396964 VA: 0x75989ae964
	public String get_ProcessName() { }
	// RVA: 0x6399328 VA: 0x75989b1328
	private Void RaiseOnExited() { }
}
```