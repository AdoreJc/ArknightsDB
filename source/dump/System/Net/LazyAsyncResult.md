# LazyAsyncResult

**Namespace:** `System.Net`


## Fields

- `Object m_AsyncObject`

- `Object m_AsyncState`

- `AsyncCallback m_AsyncCallback`

- `Object m_Result`

- `Int32 m_IntCompleted`

- `Boolean m_EndCalled`

- `Boolean m_UserEvent`

- `Object m_Event`


## Properties

- `Object AsyncState`

- `AsyncCallback AsyncCallback`

- `WaitHandle AsyncWaitHandle`

- `Boolean CompletedSynchronously`

- `Boolean IsCompleted`


## Methods

- `Object get_AsyncState()`

- `AsyncCallback get_AsyncCallback()`

- `WaitHandle get_AsyncWaitHandle()`

- `Boolean LazilyCreateEvent(out)`

- `Boolean get_CompletedSynchronously()`

- `Boolean get_IsCompleted()`

- `Void ProtectedInvokeCallback(Object, IntPtr)`

- `Void WorkerThreadComplete(Object)`

- `Object WaitForCompletion(Boolean)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class LazyAsyncResult : IAsyncResult
{
	private static ThreadContext t_ThreadContext; // 0xffffffffffffffff
	private Object m_AsyncObject; // 0x10
	private Object m_AsyncState; // 0x18
	private AsyncCallback m_AsyncCallback; // 0x20
	private Object m_Result; // 0x28
	private Int32 m_IntCompleted; // 0x30
	private Boolean m_EndCalled; // 0x34
	private Boolean m_UserEvent; // 0x35
	private Object m_Event; // 0x38

	private static ThreadContext CurrentThreadContext { get; }
	internal Object AsyncObject { get; }
	public Object AsyncState { get; }
	protected AsyncCallback AsyncCallback { get; }
	public WaitHandle AsyncWaitHandle { get; }
	public Boolean CompletedSynchronously { get; }
	public Boolean IsCompleted { get; }
	internal Boolean InternalPeekCompleted { get; }
	internal Boolean EndCalled { get; set; }

	// RVA: 0x6432a50 VA: 0x7598a4aa50
	private static ThreadContext get_CurrentThreadContext() { }
	// RVA: 0x6432af4 VA: 0x7598a4aaf4
	internal Void .ctor(Object myObject, Object myState, AsyncCallback myCallBack) { }
	// RVA: 0x6432bb0 VA: 0x7598a4abb0
	internal Object get_AsyncObject() { }
	// RVA: 0x6432bb8 VA: 0x7598a4abb8
	public Object get_AsyncState() { }
	// RVA: 0x6432bc0 VA: 0x7598a4abc0
	protected AsyncCallback get_AsyncCallback() { }
	// RVA: 0x6432bc8 VA: 0x7598a4abc8
	public WaitHandle get_AsyncWaitHandle() { }
	// RVA: 0x6432c6c VA: 0x7598a4ac6c
	private Boolean LazilyCreateEvent(out ManualResetEvent waitHandle) { }
	// RVA: 0x6432e5c VA: 0x7598a4ae5c
	public Boolean get_CompletedSynchronously() { }
	// RVA: 0x6432e8c VA: 0x7598a4ae8c
	public Boolean get_IsCompleted() { }
	// RVA: 0x6432e4c VA: 0x7598a4ae4c
	internal Boolean get_InternalPeekCompleted() { }
	// RVA: 0x6432ebc VA: 0x7598a4aebc
	internal Boolean get_EndCalled() { }
	// RVA: 0x6432ec4 VA: 0x7598a4aec4
	internal Void set_EndCalled(Boolean value) { }
	// RVA: 0x6432ed0 VA: 0x7598a4aed0
	protected Void ProtectedInvokeCallback(Object result, IntPtr userToken) { }
	// RVA: 0x64330c4 VA: 0x7598a4b0c4
	internal Void InvokeCallback(Object result) { }
	// RVA: 0x6433124 VA: 0x7598a4b124
	internal Void InvokeCallback() { }
	// RVA: 0x6433178 VA: 0x7598a4b178
	protected virtual Void Complete(IntPtr userToken) { }
	// RVA: 0x6433310 VA: 0x7598a4b310
	private Void WorkerThreadComplete(Object state) { }
	// RVA: 0x64333bc VA: 0x7598a4b3bc
	protected virtual Void Cleanup() { }
	// RVA: 0x64333c0 VA: 0x7598a4b3c0
	internal Object InternalWaitForCompletion() { }
	// RVA: 0x64333c8 VA: 0x7598a4b3c8
	private Object WaitForCompletion(Boolean snap) { }
}
```