# TaskCompletionSource

**Namespace:** `System.Threading.Tasks`


## Methods

- `Void SpinUntilCompleted()`

- `Boolean TrySetException(Exception)`

- `Boolean TrySetResult(TResult)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public class TaskCompletionSource`1
{
	private readonly Task`1 _task; // 0x0

	public Task`1 Task { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(TaskCreationOptions creationOptions) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Object state) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Object state, TaskCreationOptions creationOptions) { }
	// RVA: 0x VA: 0x0
	public Task`1 get_Task() { }
	// RVA: 0x VA: 0x0
	private Void SpinUntilCompleted() { }
	// RVA: 0x VA: 0x0
	public Boolean TrySetException(Exception exception) { }
	// RVA: 0x VA: 0x0
	public Boolean TrySetResult(TResult result) { }
}
```