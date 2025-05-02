# NetworkStream

**Namespace:** `System.Net.Sockets`


## Fields

- `Boolean _readable`

- `Boolean _writeable`

- `Int32 _closeTimeout`

- `Boolean _cleanedUp`

- `Int32 _currentReadTimeout`

- `Int32 _currentWriteTimeout`


## Methods

- `Void Close(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class NetworkStream : Stream
{
	private readonly Socket _streamSocket; // 0x28
	private readonly Boolean _ownsSocket; // 0x30
	private Boolean _readable; // 0x31
	private Boolean _writeable; // 0x32
	private Int32 _closeTimeout; // 0x34
	private Boolean _cleanedUp; // 0x38
	private Int32 _currentReadTimeout; // 0x3c
	private Int32 _currentWriteTimeout; // 0x40

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Boolean CanTimeout { get; }
	public override Int32 ReadTimeout { get; set; }
	public override Int32 WriteTimeout { get; set; }
	public virtual Boolean DataAvailable { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	internal Socket InternalSocket { get; }

	// RVA: 0x634c904 VA: 0x7598964904
	public Void .ctor(Socket socket) { }
	// RVA: 0x634cad0 VA: 0x7598964ad0
	public Void .ctor(Socket socket, Boolean ownsSocket) { }
	// RVA: 0x634c910 VA: 0x7598964910
	public Void .ctor(Socket socket, FileAccess access, Boolean ownsSocket) { }
	// RVA: 0x634cadc VA: 0x7598964adc
	public override Boolean get_CanRead() { }
	// RVA: 0x634cae4 VA: 0x7598964ae4
	public override Boolean get_CanSeek() { }
	// RVA: 0x634caec VA: 0x7598964aec
	public override Boolean get_CanWrite() { }
	// RVA: 0x634caf4 VA: 0x7598964af4
	public override Boolean get_CanTimeout() { }
	// RVA: 0x634cafc VA: 0x7598964afc
	public override Int32 get_ReadTimeout() { }
	// RVA: 0x634cd28 VA: 0x7598964d28
	public override Void set_ReadTimeout(Int32 value) { }
	// RVA: 0x634cf7c VA: 0x7598964f7c
	public override Int32 get_WriteTimeout() { }
	// RVA: 0x634d004 VA: 0x7598965004
	public override Void set_WriteTimeout(Int32 value) { }
	// RVA: 0x634d08c VA: 0x759896508c
	public virtual Boolean get_DataAvailable() { }
	// RVA: 0x634d1f0 VA: 0x75989651f0
	public override Int64 get_Length() { }
	// RVA: 0x634d240 VA: 0x7598965240
	public override Int64 get_Position() { }
	// RVA: 0x634d290 VA: 0x7598965290
	public override Void set_Position(Int64 value) { }
	// RVA: 0x634d2e0 VA: 0x75989652e0
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x634d330 VA: 0x7598965330
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x634d6a4 VA: 0x75989656a4
	public override Int32 Read(Span`1 destination) { }
	// RVA: 0x634da08 VA: 0x7598965a08
	public override Int32 ReadByte() { }
	// RVA: 0x634da8c VA: 0x7598965a8c
	public override Void Write(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x634de00 VA: 0x7598965e00
	public override Void Write(ReadOnlySpan`1 source) { }
	// RVA: 0x634e100 VA: 0x7598966100
	public override Void WriteByte(Byte value) { }
	// RVA: 0x634e178 VA: 0x7598966178
	public Void Close(Int32 timeout) { }
	// RVA: 0x634e1e0 VA: 0x75989661e0
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x634e2e8 VA: 0x75989662e8
	protected override Void Finalize() { }
	// RVA: 0x634e38c VA: 0x759896638c
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x634e730 VA: 0x7598966730
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x634e9b4 VA: 0x75989669b4
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x634ed58 VA: 0x7598966d58
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x634efdc VA: 0x7598966fdc
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x634f6bc VA: 0x75989676bc
	public override ValueTask`1 ReadAsync(Memory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x634f914 VA: 0x7598967914
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x634ffdc VA: 0x7598967fdc
	public override ValueTask WriteAsync(ReadOnlyMemory`1 buffer, CancellationToken cancellationToken) { }
	// RVA: 0x6350230 VA: 0x7598968230
	public override Void Flush() { }
	// RVA: 0x6350234 VA: 0x7598968234
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x63502bc VA: 0x75989682bc
	public override Void SetLength(Int64 value) { }
	// RVA: 0x634cdb0 VA: 0x7598964db0
	internal Void SetSocketTimeoutOption(SocketShutdown mode, Int32 timeout, Boolean silent) { }
	// RVA: 0x635045c VA: 0x759896845c
	internal Socket get_InternalSocket() { }
}
```