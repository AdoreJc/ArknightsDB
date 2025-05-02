# SemaphoreSlim

**Namespace:** `System.Threading`


## Fields

- `Int32 m_currentCount`

- `Int32 m_waitCount`

- `Object m_lockObj`

- `ManualResetEvent m_waitHandle`

- `TaskNode m_asyncHead`

- `TaskNode m_asyncTail`


## Methods

- `Void Wait()`

- `Boolean Wait(Int32, CancellationToken)`

- `Boolean WaitUntilCountOrTimeout(Int32, UInt32, CancellationToken)`

- `Task WaitAsync()`

- `TaskNode CreateAndAddAsyncWaiter()`

- `Boolean RemoveAsyncWaiter(TaskNode)`

- `Int32 Release()`

- `Int32 Release(Int32)`

- `Void Dispose()`

- `Void CheckDispose()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class SemaphoreSlim : IDisposable
{
	private Int32 m_currentCount; // 0x10
	private readonly Int32 m_maxCount; // 0x14
	private Int32 m_waitCount; // 0x18
	private Object m_lockObj; // 0x20
	private ManualResetEvent m_waitHandle; // 0x28
	private TaskNode m_asyncHead; // 0x30
	private TaskNode m_asyncTail; // 0x38
	private static readonly Task`1 s_trueTask; // 0x0
	private static readonly Task`1 s_falseTask; // 0x8
	private const Int32 NO_MAXIMUM; // 0x0
	private static Action`1 s_cancellationTokenCanceledEventHandler; // 0x10


	// RVA: 0x611cb4c VA: 0x7598734b4c
	public Void .ctor(Int32 initialCount, Int32 maxCount) { }
	// RVA: 0x611ccf4 VA: 0x7598734cf4
	public Void Wait() { }
	// RVA: 0x611cd00 VA: 0x7598734d00
	public Boolean Wait(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x611d5e0 VA: 0x75987355e0
	private Boolean WaitUntilCountOrTimeout(Int32 millisecondsTimeout, UInt32 startTime, CancellationToken cancellationToken) { }
	// RVA: 0x611d70c VA: 0x759873570c
	public Task WaitAsync() { }
	// RVA: 0x611d2c0 VA: 0x75987352c0
	public Task`1 WaitAsync(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x611d718 VA: 0x7598735718
	private TaskNode CreateAndAddAsyncWaiter() { }
	// RVA: 0x611d97c VA: 0x759873597c
	private Boolean RemoveAsyncWaiter(TaskNode task) { }
	// RVA: 0x611d7c8 VA: 0x75987357c8
	private Task`1 WaitUntilCountOrTimeoutAsync(TaskNode asyncWaiter, Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x611da64 VA: 0x7598735a64
	public Int32 Release() { }
	// RVA: 0x611da6c VA: 0x7598735a6c
	public Int32 Release(Int32 releaseCount) { }
	// RVA: 0x611dda8 VA: 0x7598735da8
	private static Void QueueWaiterTask(TaskNode waiterTask) { }
	// RVA: 0x611ddb4 VA: 0x7598735db4
	public Void Dispose() { }
	// RVA: 0x611de20 VA: 0x7598735e20
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x611debc VA: 0x7598735ebc
	private static Void CancellationTokenCanceledEventHandler(Object obj) { }
	// RVA: 0x611d23c VA: 0x759873523c
	private Void CheckDispose() { }
	// RVA: 0x611ccec VA: 0x7598734cec
	private static String GetResourceString(String str) { }
	// RVA: 0x611dfd0 VA: 0x7598735fd0
	private static Void .cctor() { }
}
```