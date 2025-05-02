# StandardTaskContinuation

**Namespace:** `System.Threading.Tasks`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
internal class StandardTaskContinuation : TaskContinuation
{
	internal readonly Task m_task; // 0x10
	internal readonly TaskContinuationOptions m_options; // 0x18
	private readonly TaskScheduler m_taskScheduler; // 0x20


	// RVA: 0x6131fb0 VA: 0x7598749fb0
	internal Void .ctor(Task task, TaskContinuationOptions options, TaskScheduler scheduler) { }
	// RVA: 0x6134258 VA: 0x759874c258
	internal override Void Run(Task completedTask, Boolean bCanInlineContinuationTask) { }
}
```