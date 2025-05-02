# AsyncResult

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Object async_state`

- `WaitHandle handle`

- `Object async_delegate`

- `IntPtr data`

- `Object object_data`

- `Boolean sync_completed`

- `Boolean completed`

- `Boolean endinvoke_called`

- `Object async_callback`

- `ExecutionContext current`

- `ExecutionContext original`

- `Int64 add_time`

- `MonoMethodMessage call_message`

- `IMessageCtrl message_ctrl`

- `IMessage reply_message`

- `WaitCallback orig_cb`


## Properties

- `Boolean EndInvokeCalled`

- `IMessageSink NextSink`


## Methods

- `Boolean get_EndInvokeCalled()`

- `Void set_EndInvokeCalled(Boolean)`

- `IMessageSink get_NextSink()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class AsyncResult : IAsyncResult, IMessageSink, IThreadPoolWorkItem
{
	private Object async_state; // 0x10
	private WaitHandle handle; // 0x18
	private Object async_delegate; // 0x20
	private IntPtr data; // 0x28
	private Object object_data; // 0x30
	private Boolean sync_completed; // 0x38
	private Boolean completed; // 0x39
	private Boolean endinvoke_called; // 0x3a
	private Object async_callback; // 0x40
	private ExecutionContext current; // 0x48
	private ExecutionContext original; // 0x50
	private Int64 add_time; // 0x58
	private MonoMethodMessage call_message; // 0x60
	private IMessageCtrl message_ctrl; // 0x68
	private IMessage reply_message; // 0x70
	private WaitCallback orig_cb; // 0x78

	public virtual Object AsyncState { get; }
	public virtual WaitHandle AsyncWaitHandle { get; }
	public virtual Boolean CompletedSynchronously { get; }
	public virtual Boolean IsCompleted { get; }
	public Boolean EndInvokeCalled { get; set; }
	public virtual Object AsyncDelegate { get; }
	public IMessageSink NextSink { get; }
	internal MonoMethodMessage CallMessage { get; set; }

	// RVA: 0x5fa0828 VA: 0x75985b8828
	internal Void .ctor() { }
	// RVA: 0x5fa0830 VA: 0x75985b8830
	public virtual Object get_AsyncState() { }
	// RVA: 0x5fa0838 VA: 0x75985b8838
	public virtual WaitHandle get_AsyncWaitHandle() { }
	// RVA: 0x5fa0968 VA: 0x75985b8968
	public virtual Boolean get_CompletedSynchronously() { }
	// RVA: 0x5fa0970 VA: 0x75985b8970
	public virtual Boolean get_IsCompleted() { }
	// RVA: 0x5fa0978 VA: 0x75985b8978
	public Boolean get_EndInvokeCalled() { }
	// RVA: 0x5fa0980 VA: 0x75985b8980
	public Void set_EndInvokeCalled(Boolean value) { }
	// RVA: 0x5fa098c VA: 0x75985b898c
	public virtual Object get_AsyncDelegate() { }
	// RVA: 0x5fa0994 VA: 0x75985b8994
	public IMessageSink get_NextSink() { }
	// RVA: 0x5fa099c VA: 0x75985b899c
	public virtual IMessageCtrl AsyncProcessMessage(IMessage msg, IMessageSink replySink) { }
	// RVA: 0x5fa09dc VA: 0x75985b89dc
	public virtual IMessage GetReplyMessage() { }
	// RVA: 0x5fa09e4 VA: 0x75985b89e4
	public virtual Void SetMessageCtrl(IMessageCtrl mc) { }
	// RVA: 0x5fa09ec VA: 0x75985b89ec
	internal Void SetCompletedSynchronously(Boolean completed) { }
	// RVA: 0x5f8f978 VA: 0x75985a7978
	internal IMessage EndInvoke() { }
	// RVA: 0x5fa09f8 VA: 0x75985b89f8
	public virtual IMessage SyncProcessMessage(IMessage msg) { }
	// RVA: 0x5fa0b94 VA: 0x75985b8b94
	internal MonoMethodMessage get_CallMessage() { }
	// RVA: 0x5fa0b9c VA: 0x75985b8b9c
	internal Void set_CallMessage(MonoMethodMessage value) { }
	// RVA: 0x5fa0ba4 VA: 0x75985b8ba4
	private Void System.Threading.IThreadPoolWorkItem.ExecuteWorkItem() { }
	// RVA: 0x5fa0bac VA: 0x75985b8bac
	private Void System.Threading.IThreadPoolWorkItem.MarkAborted(ThreadAbortException tae) { }
	// RVA: 0x5fa0ba8 VA: 0x75985b8ba8
	internal Object Invoke() { }
}
```