# CommandStream

**Namespace:** `System.Net`


## Fields

- `Boolean _recoverableFailure`

- `WebRequest _request`

- `Boolean _isAsync`

- `Boolean _aborted`

- `Int32 _index`

- `Boolean _doRead`

- `Boolean _doSend`

- `ResponseDescription _currentResponseDescription`

- `String _abortReason`

- `String _buffer`

- `Encoding _encoding`

- `Decoder _decoder`


## Properties

- `Encoding Encoding`


## Methods

- `Void InvokeRequestCallback(Object)`

- `Void MarkAsRecoverableFailure()`

- `Exception GenerateException(String, WebExceptionStatus, Exception)`

- `Exception GenerateException(FtpStatusCode, String, Exception)`

- `Void InitCommandPipeline(WebRequest, PipelineEntry[], Boolean)`

- `Stream ContinueCommandPipeline()`

- `Boolean PostSendCommandProcessing(ref)`

- `Boolean PostReadCommandProcessing(ref)`

- `Encoding get_Encoding()`

- `Void set_Encoding(Encoding)`

- `ResponseDescription ReceiveCommandResponse()`

- `Void ReceiveCommandResponseCallback(ReceiveState, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class CommandStream : NetworkStreamWrapper
{
	private static readonly AsyncCallback s_writeCallbackDelegate; // 0x0
	private static readonly AsyncCallback s_readCallbackDelegate; // 0x8
	private Boolean _recoverableFailure; // 0x38
	protected WebRequest _request; // 0x40
	protected Boolean _isAsync; // 0x48
	private Boolean _aborted; // 0x49
	protected PipelineEntry[] _commands; // 0x50
	protected Int32 _index; // 0x58
	private Boolean _doRead; // 0x5c
	private Boolean _doSend; // 0x5d
	private ResponseDescription _currentResponseDescription; // 0x60
	protected String _abortReason; // 0x68
	private String _buffer; // 0x70
	private Encoding _encoding; // 0x78
	private Decoder _decoder; // 0x80

	internal Boolean RecoverableFailure { get; }
	protected Encoding Encoding { get; set; }

	// RVA: 0x6419130 VA: 0x7598a31130
	internal Void .ctor(TcpClient client) { }
	// RVA: 0x641927c VA: 0x7598a3127c
	internal virtual Void Abort(Exception e) { }
	// RVA: 0x64194a4 VA: 0x7598a314a4
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6419538 VA: 0x7598a31538
	protected Void InvokeRequestCallback(Object obj) { }
	// RVA: 0x64195b8 VA: 0x7598a315b8
	internal Boolean get_RecoverableFailure() { }
	// RVA: 0x64195c0 VA: 0x7598a315c0
	protected Void MarkAsRecoverableFailure() { }
	// RVA: 0x64195d8 VA: 0x7598a315d8
	internal Stream SubmitRequest(WebRequest request, Boolean isAsync, Boolean readInitalResponseOnConnect) { }
	// RVA: 0x6419bf4 VA: 0x7598a31bf4
	protected virtual Void ClearState() { }
	// RVA: 0x6419c04 VA: 0x7598a31c04
	protected virtual PipelineEntry[] BuildCommandsList(WebRequest request) { }
	// RVA: 0x6419c0c VA: 0x7598a31c0c
	protected Exception GenerateException(String message, WebExceptionStatus status, Exception innerException) { }
	// RVA: 0x6419c8c VA: 0x7598a31c8c
	protected Exception GenerateException(FtpStatusCode code, String statusDescription, Exception innerException) { }
	// RVA: 0x6419658 VA: 0x7598a31658
	protected Void InitCommandPipeline(WebRequest request, PipelineEntry[] commands, Boolean isAsync) { }
	// RVA: 0x6419d54 VA: 0x7598a31d54
	internal Void CheckContinuePipeline() { }
	// RVA: 0x6419710 VA: 0x7598a31710
	protected Stream ContinueCommandPipeline() { }
	// RVA: 0x6419e18 VA: 0x7598a31e18
	private Boolean PostSendCommandProcessing(ref Stream stream) { }
	// RVA: 0x641a284 VA: 0x7598a32284
	private Boolean PostReadCommandProcessing(ref Stream stream) { }
	// RVA: 0x641a4b4 VA: 0x7598a324b4
	protected virtual PipelineInstruction PipelineCallback(PipelineEntry entry, ResponseDescription response, Boolean timeout, ref Stream stream) { }
	// RVA: 0x641a4bc VA: 0x7598a324bc
	private static Void ReadCallback(IAsyncResult asyncResult) { }
	// RVA: 0x641ad50 VA: 0x7598a32d50
	private static Void WriteCallback(IAsyncResult asyncResult) { }
	// RVA: 0x641b004 VA: 0x7598a33004
	protected Encoding get_Encoding() { }
	// RVA: 0x641b00c VA: 0x7598a3300c
	protected Void set_Encoding(Encoding value) { }
	// RVA: 0x641b05c VA: 0x7598a3305c
	protected virtual Boolean CheckValid(ResponseDescription response, ref Int32 validThrough, ref Int32 completeLength) { }
	// RVA: 0x6419f58 VA: 0x7598a31f58
	private ResponseDescription ReceiveCommandResponse() { }
	// RVA: 0x641a7c4 VA: 0x7598a327c4
	private Void ReceiveCommandResponseCallback(ReceiveState state, Int32 bytesRead) { }
	// RVA: 0x641b128 VA: 0x7598a33128
	private static Void .cctor() { }
}
```