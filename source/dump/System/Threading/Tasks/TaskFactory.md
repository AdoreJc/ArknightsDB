# TaskFactory

**Namespace:** `System.Threading.Tasks`


## Methods

- `Task StartNew(Action, CancellationToken, TaskCreationOptions, TaskScheduler)`

- `Task StartNew(Action`1, Object, CancellationToken, TaskCreationOptions, TaskScheduler)`

- `Task FromAsync(Func`4, Action`1, TArg1, Object)`

- `Task FromAsync(Func`4, Action`1, TArg1, Object, TaskCreationOptions)`

- `Task FromAsync(Func`5, Action`1, TArg1, TArg2, Object)`

- `Task FromAsync(Func`5, Action`1, TArg1, TArg2, Object, TaskCreationOptions)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public class TaskFactory
{
	private readonly CancellationToken m_defaultCancellationToken; // 0x10
	private readonly TaskScheduler m_defaultScheduler; // 0x18
	private readonly TaskCreationOptions m_defaultCreationOptions; // 0x20
	private readonly TaskContinuationOptions m_defaultContinuationOptions; // 0x24


	// RVA: 0x6133bdc VA: 0x759874bbdc
	public Void .ctor() { }
	// RVA: 0x6135f0c VA: 0x759874df0c
	public Void .ctor(CancellationToken cancellationToken, TaskCreationOptions creationOptions, TaskContinuationOptions continuationOptions, TaskScheduler scheduler) { }
	// RVA: 0x6136080 VA: 0x759874e080
	internal static Void CheckCreationOptions(TaskCreationOptions creationOptions) { }
	// RVA: 0x61360e0 VA: 0x759874e0e0
	public Task StartNew(Action action, CancellationToken cancellationToken, TaskCreationOptions creationOptions, TaskScheduler scheduler) { }
	// RVA: 0x613616c VA: 0x759874e16c
	public Task StartNew(Action`1 action, Object state, CancellationToken cancellationToken, TaskCreationOptions creationOptions, TaskScheduler scheduler) { }
	// RVA: 0x VA: 0x0
	public Task`1 StartNew(Func`1 function, CancellationToken cancellationToken, TaskCreationOptions creationOptions, TaskScheduler scheduler) { }
	// RVA: 0x VA: 0x0
	public Task`1 StartNew(Func`2 function, Object state, CancellationToken cancellationToken, TaskCreationOptions creationOptions, TaskScheduler scheduler) { }
	// RVA: 0x VA: 0x0
	public Task FromAsync(Func`4 beginMethod, Action`1 endMethod, TArg1 arg1, Object state) { }
	// RVA: 0x VA: 0x0
	public Task FromAsync(Func`4 beginMethod, Action`1 endMethod, TArg1 arg1, Object state, TaskCreationOptions creationOptions) { }
	// RVA: 0x VA: 0x0
	public Task FromAsync(Func`5 beginMethod, Action`1 endMethod, TArg1 arg1, TArg2 arg2, Object state) { }
	// RVA: 0x VA: 0x0
	public Task FromAsync(Func`5 beginMethod, Action`1 endMethod, TArg1 arg1, TArg2 arg2, Object state, TaskCreationOptions creationOptions) { }
	// RVA: 0x61361fc VA: 0x759874e1fc
	internal static Void CheckFromAsyncOptions(TaskCreationOptions creationOptions, Boolean hasBeginMethod) { }
	// RVA: 0x6132f28 VA: 0x759874af28
	internal static Task`1 CommonCWAnyLogic(IList`1 tasks) { }
	// RVA: 0x6135f78 VA: 0x759874df78
	internal static Void CheckMultiTaskContinuationOptions(TaskContinuationOptions continuationOptions) { }
}
```