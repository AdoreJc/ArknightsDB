# AwaitTaskContinuation

**Namespace:** `System.Threading.Tasks`


## Methods

- `Task CreateTask(Action`1, Object, TaskScheduler)`

- `Void RunCallback(ContextCallback, Object, ref)`

- `Void MarkAborted(ThreadAbortException)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
internal class AwaitTaskContinuation : TaskContinuation, IThreadPoolWorkItem
{
	private readonly ExecutionContext m_capturedContext; // 0x10
	protected readonly Action m_action; // 0x18
	private static ContextCallback s_invokeActionCallback; // 0x0

	internal static Boolean IsValidLocationForInlining { get; }

	// RVA: 0x61343f8 VA: 0x759874c3f8
	internal Void .ctor(Action action, Boolean flowExecutionContext) { }
	// RVA: 0x6134ebc VA: 0x759874cebc
	protected Task CreateTask(Action`1 action, Object state, TaskScheduler scheduler) { }
	// RVA: 0x6134d90 VA: 0x759874cd90
	internal override Void Run(Task ignored, Boolean canInlineContinuationTask) { }
	// RVA: 0x613510c VA: 0x759874d10c
	internal static Boolean get_IsValidLocationForInlining() { }
	// RVA: 0x6135240 VA: 0x759874d240
	private Void System.Threading.IThreadPoolWorkItem.ExecuteWorkItem() { }
	// RVA: 0x6135378 VA: 0x759874d378
	private static Void InvokeAction(Object state) { }
	// RVA: 0x61353e4 VA: 0x759874d3e4
	protected static ContextCallback GetInvokeActionCallback() { }
	// RVA: 0x61346a0 VA: 0x759874c6a0
	protected Void RunCallback(ContextCallback callback, Object state, ref Task currentTask) { }
	// RVA: 0x6131660 VA: 0x7598749660
	internal static Void RunOrScheduleAction(Action action, Boolean allowInlining, ref Task currentTask) { }
	// RVA: 0x6130590 VA: 0x7598748590
	internal static Void UnsafeScheduleAction(Action action) { }
	// RVA: 0x61350b4 VA: 0x759874d0b4
	protected static Void ThrowAsyncIfNecessary(Exception exc) { }
	// RVA: 0x613549c VA: 0x759874d49c
	public Void MarkAborted(ThreadAbortException e) { }
}
```