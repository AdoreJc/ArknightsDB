# UnzipTaskThread

**Namespace:** ` `


## Fields

- `Thread m_workThread`

- `Boolean m_isDisposed`

- `UnzipThreadContext m_context`

- `Options m_options`

- `Int32 m_totalTaskCnt`

- `Int64 m_totalSize`

- `Int32 m_completeTaskCnt`

- `Int64 m_completeSize`

- `Int64 m_curFileSize`

- `ErrorInfo m_lastError`

- `Boolean m_isError`


## Properties

- `Int32 pendingTaskCount`

- `Boolean isError`

- `ErrorInfo lastError`

- `Boolean isCompleted`

- `Boolean isWorking`

- `Single progress`


## Methods

- `Void AddTask(Task)`

- `Int32 get_pendingTaskCount()`

- `Boolean get_isError()`

- `ErrorInfo get_lastError()`

- `Boolean get_isCompleted()`

- `Boolean get_isWorking()`

- `Single get_progress()`

- `Void Dispose()`

- `Void Run()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnzipTaskThread : IDisposable
{
	private ThreadSafeQueue`1 m_pendingTasks; // 0x10
	private Thread m_workThread; // 0x18
	private Boolean m_isDisposed; // 0x20
	private UnzipThreadContext m_context; // 0x28
	private Options m_options; // 0x30
	private Int32 m_totalTaskCnt; // 0x34
	private Int64 m_totalSize; // 0x38
	private Int32 m_completeTaskCnt; // 0x40
	private Int64 m_completeSize; // 0x48
	private Int64 m_curFileSize; // 0x50
	private ErrorInfo m_lastError; // 0x58
	private Boolean m_isError; // 0x78

	public Int32 pendingTaskCount { get; }
	public Boolean isError { get; }
	public ErrorInfo lastError { get; }
	public Boolean isCompleted { get; }
	public Boolean isWorking { get; }
	public Single progress { get; }

	// RVA: 0x373b02c VA: 0x7595d5302c
	public Void .ctor(Options options) { }
	// RVA: 0x373b198 VA: 0x7595d53198
	public Void AddTask(Task task) { }
	// RVA: 0x373b35c VA: 0x7595d5335c
	public Int32 get_pendingTaskCount() { }
	// RVA: 0x373acb0 VA: 0x7595d52cb0
	public Boolean get_isError() { }
	// RVA: 0x373acc8 VA: 0x7595d52cc8
	public ErrorInfo get_lastError() { }
	// RVA: 0x373b3ac VA: 0x7595d533ac
	public Boolean get_isCompleted() { }
	// RVA: 0x373aa08 VA: 0x7595d52a08
	public Boolean get_isWorking() { }
	// RVA: 0x373a890 VA: 0x7595d52890
	public Single get_progress() { }
	// RVA: 0x373b470 VA: 0x7595d53470
	public Void Dispose() { }
	// RVA: 0x373b59c VA: 0x7595d5359c
	protected Void Run() { }
}
```