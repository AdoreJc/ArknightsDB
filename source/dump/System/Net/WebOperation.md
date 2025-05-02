# WebOperation

**Namespace:** `System.Net`


## Fields

- `WebConnection <Connection>k__BackingField`

- `ServicePoint <ServicePoint>k__BackingField`

- `CancellationTokenSource cts`

- `WebRequestStream writeStream`

- `WebResponseStream responseStream`

- `ExceptionDispatchInfo disposedInfo`

- `ExceptionDispatchInfo closedInfo`

- `WebOperation priorityRequest`

- `Int32 requestSent`

- `Int32 finished`


## Properties

- `HttpWebRequest Request`

- `WebConnection Connection`

- `ServicePoint ServicePoint`

- `BufferOffsetSize WriteBuffer`

- `Boolean IsNtlmChallenge`

- `Boolean Aborted`

- `Boolean Closed`

- `WebRequestStream WriteStream`


## Methods

- `HttpWebRequest get_Request()`

- `WebConnection get_Connection()`

- `Void set_Connection(WebConnection)`

- `ServicePoint get_ServicePoint()`

- `Void set_ServicePoint(ServicePoint)`

- `BufferOffsetSize get_WriteBuffer()`

- `Boolean get_IsNtlmChallenge()`

- `Boolean get_Aborted()`

- `Boolean get_Closed()`

- `Void Abort()`

- `Void Close()`

- `Void SetCanceled()`

- `Void SetError(Exception)`

- `ExceptionDispatchInfo CheckThrowDisposed(Boolean, ref)`

- `Void SetPriorityRequest(WebOperation)`

- `WebRequestStream get_WriteStream()`

- `Void <RegisterRequest>b__48_0()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebOperation
{
	private readonly HttpWebRequest <Request>k__BackingField; // 0x10
	private WebConnection <Connection>k__BackingField; // 0x18
	private ServicePoint <ServicePoint>k__BackingField; // 0x20
	private readonly BufferOffsetSize <WriteBuffer>k__BackingField; // 0x28
	private readonly Boolean <IsNtlmChallenge>k__BackingField; // 0x30
	private CancellationTokenSource cts; // 0x38
	private WebCompletionSource`1 requestTask; // 0x40
	private WebCompletionSource`1 requestWrittenTask; // 0x48
	private WebCompletionSource`1 responseTask; // 0x50
	private WebCompletionSource`1 finishedTask; // 0x58
	private WebRequestStream writeStream; // 0x60
	private WebResponseStream responseStream; // 0x68
	private ExceptionDispatchInfo disposedInfo; // 0x70
	private ExceptionDispatchInfo closedInfo; // 0x78
	private WebOperation priorityRequest; // 0x80
	private Int32 requestSent; // 0x88
	private Int32 finished; // 0x8c

	public HttpWebRequest Request { get; }
	public WebConnection Connection { get; set; }
	public ServicePoint ServicePoint { get; set; }
	public BufferOffsetSize WriteBuffer { get; }
	public Boolean IsNtlmChallenge { get; }
	public Boolean Aborted { get; }
	public Boolean Closed { get; }
	public WebRequestStream WriteStream { get; }
	internal WebCompletionSource`1 Finished { get; }

	// RVA: 0x633bd4c VA: 0x7598953d4c
	public HttpWebRequest get_Request() { }
	// RVA: 0x633bd54 VA: 0x7598953d54
	public WebConnection get_Connection() { }
	// RVA: 0x633bd5c VA: 0x7598953d5c
	private Void set_Connection(WebConnection value) { }
	// RVA: 0x633bd64 VA: 0x7598953d64
	public ServicePoint get_ServicePoint() { }
	// RVA: 0x633bd6c VA: 0x7598953d6c
	private Void set_ServicePoint(ServicePoint value) { }
	// RVA: 0x633bd74 VA: 0x7598953d74
	public BufferOffsetSize get_WriteBuffer() { }
	// RVA: 0x633bd7c VA: 0x7598953d7c
	public Boolean get_IsNtlmChallenge() { }
	// RVA: 0x633bd84 VA: 0x7598953d84
	public Void .ctor(HttpWebRequest request, BufferOffsetSize writeBuffer, Boolean isNtlmChallenge, CancellationToken cancellationToken) { }
	// RVA: 0x633bf6c VA: 0x7598953f6c
	public Boolean get_Aborted() { }
	// RVA: 0x633bfbc VA: 0x7598953fbc
	public Boolean get_Closed() { }
	// RVA: 0x633bfe8 VA: 0x7598953fe8
	public Void Abort() { }
	// RVA: 0x633c1e4 VA: 0x75989541e4
	public Void Close() { }
	// RVA: 0x633c118 VA: 0x7598954118
	private Void SetCanceled() { }
	// RVA: 0x633c4d4 VA: 0x75989544d4
	private Void SetError(Exception error) { }
	// RVA: 0x633c028 VA: 0x7598954028
	private ValueTuple`2 SetDisposed(ref ExceptionDispatchInfo field) { }
	// RVA: 0x633c578 VA: 0x7598954578
	internal ExceptionDispatchInfo CheckDisposed(CancellationToken cancellationToken) { }
	// RVA: 0x633c658 VA: 0x7598954658
	internal Void ThrowIfDisposed() { }
	// RVA: 0x633c6b8 VA: 0x75989546b8
	internal Void ThrowIfDisposed(CancellationToken cancellationToken) { }
	// RVA: 0x633c738 VA: 0x7598954738
	internal Void ThrowIfClosedOrDisposed() { }
	// RVA: 0x633c798 VA: 0x7598954798
	internal Void ThrowIfClosedOrDisposed(CancellationToken cancellationToken) { }
	// RVA: 0x633c600 VA: 0x7598954600
	private ExceptionDispatchInfo CheckThrowDisposed(Boolean throwIt, ref ExceptionDispatchInfo field) { }
	// RVA: 0x633c820 VA: 0x7598954820
	internal Void RegisterRequest(ServicePoint servicePoint, WebConnection connection) { }
	// RVA: 0x633cabc VA: 0x7598954abc
	public Void SetPriorityRequest(WebOperation operation) { }
	// RVA: 0x633cc48 VA: 0x7598954c48
	internal Task`1 GetRequestStreamInternal() { }
	// RVA: 0x633cc98 VA: 0x7598954c98
	public WebRequestStream get_WriteStream() { }
	// RVA: 0x633ccb0 VA: 0x7598954cb0
	public Task`1 GetResponseStream() { }
	// RVA: 0x633cd00 VA: 0x7598954d00
	internal WebCompletionSource`1 get_Finished() { }
	// RVA: 0x633cd08 VA: 0x7598954d08
	internal Void Run() { }
	// RVA: 0x633cdb8 VA: 0x7598954db8
	internal Void CompleteRequestWritten(WebRequestStream stream, Exception error) { }
	// RVA: 0x633c290 VA: 0x7598954290
	internal Void Finish(Boolean ok, Exception error) { }
	// RVA: 0x633ce38 VA: 0x7598954e38
	private Void <RegisterRequest>b__48_0() { }
}
```