# NetworkStreamWrapper

**Namespace:** `System.Net`


## Fields

- `TcpClient _client`

- `NetworkStream _networkStream`


## Properties

- `Boolean UsingSecureStream`


## Methods

- `Boolean get_UsingSecureStream()`

- `Void Close(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class NetworkStreamWrapper : Stream
{
	private TcpClient _client; // 0x28
	private NetworkStream _networkStream; // 0x30

	protected Boolean UsingSecureStream { get; }
	internal IPAddress ServerAddress { get; }
	internal Socket Socket { get; }
	internal NetworkStream NetworkStream { get; set; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Boolean CanTimeout { get; }
	public override Int32 ReadTimeout { get; set; }
	public override Int32 WriteTimeout { get; set; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x64191e4 VA: 0x7598a311e4
	internal Void .ctor(TcpClient client) { }
	// RVA: 0x641c1b0 VA: 0x7598a341b0
	protected Boolean get_UsingSecureStream() { }
	// RVA: 0x641b934 VA: 0x7598a33934
	internal IPAddress get_ServerAddress() { }
	// RVA: 0x641d790 VA: 0x7598a35790
	internal Socket get_Socket() { }
	// RVA: 0x6427314 VA: 0x7598a3f314
	internal NetworkStream get_NetworkStream() { }
	// RVA: 0x642731c VA: 0x7598a3f31c
	internal Void set_NetworkStream(NetworkStream value) { }
	// RVA: 0x6427324 VA: 0x7598a3f324
	public override Boolean get_CanRead() { }
	// RVA: 0x6427344 VA: 0x7598a3f344
	public override Boolean get_CanSeek() { }
	// RVA: 0x6427364 VA: 0x7598a3f364
	public override Boolean get_CanWrite() { }
	// RVA: 0x6427384 VA: 0x7598a3f384
	public override Boolean get_CanTimeout() { }
	// RVA: 0x64273a4 VA: 0x7598a3f3a4
	public override Int32 get_ReadTimeout() { }
	// RVA: 0x64273c8 VA: 0x7598a3f3c8
	public override Void set_ReadTimeout(Int32 value) { }
	// RVA: 0x64273ec VA: 0x7598a3f3ec
	public override Int32 get_WriteTimeout() { }
	// RVA: 0x6427410 VA: 0x7598a3f410
	public override Void set_WriteTimeout(Int32 value) { }
	// RVA: 0x6427434 VA: 0x7598a3f434
	public override Int64 get_Length() { }
	// RVA: 0x6427454 VA: 0x7598a3f454
	public override Int64 get_Position() { }
	// RVA: 0x6427474 VA: 0x7598a3f474
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6427498 VA: 0x7598a3f498
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x64274bc VA: 0x7598a3f4bc
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x64274e0 VA: 0x7598a3f4e0
	public override Void Write(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x6427504 VA: 0x7598a3f504
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x641a78c VA: 0x7598a3278c
	internal Void CloseSocket() { }
	// RVA: 0x6419474 VA: 0x7598a31474
	public Void Close(Int32 timeout) { }
	// RVA: 0x64275b0 VA: 0x7598a3f5b0
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x64275d4 VA: 0x7598a3f5d4
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x64275f8 VA: 0x7598a3f5f8
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x642761c VA: 0x7598a3f61c
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x6427640 VA: 0x7598a3f640
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x6427664 VA: 0x7598a3f664
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6427688 VA: 0x7598a3f688
	public override Void Flush() { }
	// RVA: 0x64276ac VA: 0x7598a3f6ac
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x64276d0 VA: 0x7598a3f6d0
	public override Void SetLength(Int64 value) { }
	// RVA: 0x642487c VA: 0x7598a3c87c
	internal Void SetSocketTimeoutOption(Int32 timeout) { }
}
```