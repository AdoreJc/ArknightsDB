# FileStreamAsyncResult

**Namespace:** `System.IO`


## Fields

- `Object state`

- `Boolean completed`

- `ManualResetEvent wh`

- `AsyncCallback cb`

- `Boolean completedSynch`

- `Int32 Count`

- `Int32 OriginalCount`

- `Int32 BytesRead`

- `AsyncCallback realcb`


## Properties

- `Object AsyncState`

- `Boolean CompletedSynchronously`

- `WaitHandle AsyncWaitHandle`

- `Boolean IsCompleted`


## Methods

- `Object get_AsyncState()`

- `Boolean get_CompletedSynchronously()`

- `WaitHandle get_AsyncWaitHandle()`

- `Boolean get_IsCompleted()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
internal class FileStreamAsyncResult : IAsyncResult
{
	private Object state; // 0x10
	private Boolean completed; // 0x18
	private ManualResetEvent wh; // 0x20
	private AsyncCallback cb; // 0x28
	private Boolean completedSynch; // 0x30
	public Int32 Count; // 0x34
	public Int32 OriginalCount; // 0x38
	public Int32 BytesRead; // 0x3c
	private AsyncCallback realcb; // 0x40

	public Object AsyncState { get; }
	public Boolean CompletedSynchronously { get; }
	public WaitHandle AsyncWaitHandle { get; }
	public Boolean IsCompleted { get; }

	// RVA: 0x6037dec VA: 0x759864fdec
	public Void .ctor(AsyncCallback cb, Object state) { }
	// RVA: 0x6038fa8 VA: 0x7598650fa8
	private static Void CBWrapper(IAsyncResult ares) { }
	// RVA: 0x603903c VA: 0x759865103c
	public Object get_AsyncState() { }
	// RVA: 0x6039044 VA: 0x7598651044
	public Boolean get_CompletedSynchronously() { }
	// RVA: 0x603904c VA: 0x759865104c
	public WaitHandle get_AsyncWaitHandle() { }
	// RVA: 0x6039054 VA: 0x7598651054
	public Boolean get_IsCompleted() { }
}
```