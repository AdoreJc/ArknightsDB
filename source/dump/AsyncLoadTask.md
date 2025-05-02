# AsyncLoadTask

**Namespace:** ` `


## Fields

- `Boolean m_keepWorking`

- `Boolean m_isValid`


## Properties

- `Boolean isWorking`


## Methods

- `Void set_worker(WaitForAsyncTask`1)`

- `Void StartWork(IList`1)`

- `Boolean TryGetNextResult(out, out)`

- `Void Dispose()`

- `Void Abort()`

- `IEnumerator KeepWorking()`

- `Boolean get_isWorking()`

- `Boolean HasResultToGet()`

- `Int32 _AsyncWork()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AsyncLoadTask : IDisposable
{
	private ThreadSafeQueue`1 m_pendingTasks; // 0x10
	private ThreadSafeQueue`1 m_finishedTasks; // 0x18
	private Boolean m_keepWorking; // 0x20
	private Boolean m_isValid; // 0x21
	private WaitForAsyncTask`1 <worker>k__BackingField; // 0x28

	public WaitForAsyncTask`1 worker { get; set; }
	public Boolean isWorking { get; }

	// RVA: 0x371ccf8 VA: 0x7595d34cf8
	public WaitForAsyncTask`1 get_worker() { }
	// RVA: 0x371cd00 VA: 0x7595d34d00
	private Void set_worker(WaitForAsyncTask`1 value) { }
	// RVA: 0x371cd08 VA: 0x7595d34d08
	public Void StartWork(IList`1 tasks) { }
	// RVA: 0x371cf28 VA: 0x7595d34f28
	public Boolean TryGetNextResult(out AsyncLoadResult data, out IAsyncLoadRequest handler) { }
	// RVA: 0x371c890 VA: 0x7595d34890
	public Void Dispose() { }
	// RVA: 0x371d03c VA: 0x7595d3503c
	public Void Abort() { }
	// RVA: 0x371d054 VA: 0x7595d35054
	public IEnumerator KeepWorking() { }
	// RVA: 0x371d0f0 VA: 0x7595d350f0
	public Boolean get_isWorking() { }
	// RVA: 0x371d134 VA: 0x7595d35134
	public Boolean HasResultToGet() { }
	// RVA: 0x371d190 VA: 0x7595d35190
	private Int32 _AsyncWork() { }
	// RVA: 0x371d430 VA: 0x7595d35430
	public Void .ctor() { }
}
```