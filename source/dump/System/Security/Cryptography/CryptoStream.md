# CryptoStream

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 _inputBufferIndex`

- `Int32 _inputBlockSize`

- `Int32 _outputBufferIndex`

- `Int32 _outputBlockSize`

- `Boolean _canRead`

- `Boolean _canWrite`

- `Boolean _finalBlockTransformed`

- `SemaphoreSlim _lazyAsyncActiveSemaphore`


## Properties

- `Boolean HasFlushedFinalBlock`

- `SemaphoreSlim AsyncActiveSemaphore`


## Methods

- `Boolean get_HasFlushedFinalBlock()`

- `Void FlushFinalBlock()`

- `Void CheckReadArguments(Byte[], Int32, Int32)`

- `Task WriteAsyncInternal(Byte[], Int32, Int32, CancellationToken)`

- `Void CheckWriteArguments(Byte[], Int32, Int32)`

- `Task WriteAsyncCore(Byte[], Int32, Int32, CancellationToken, Boolean)`

- `Void Clear()`

- `Void InitializeBuffer()`

- `SemaphoreSlim get_AsyncActiveSemaphore()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class CryptoStream : Stream, IDisposable
{
	private readonly Stream _stream; // 0x28
	private readonly ICryptoTransform _transform; // 0x30
	private readonly CryptoStreamMode _transformMode; // 0x38
	private Byte[] _inputBuffer; // 0x40
	private Int32 _inputBufferIndex; // 0x48
	private Int32 _inputBlockSize; // 0x4c
	private Byte[] _outputBuffer; // 0x50
	private Int32 _outputBufferIndex; // 0x58
	private Int32 _outputBlockSize; // 0x5c
	private Boolean _canRead; // 0x60
	private Boolean _canWrite; // 0x61
	private Boolean _finalBlockTransformed; // 0x62
	private SemaphoreSlim _lazyAsyncActiveSemaphore; // 0x68
	private readonly Boolean _leaveOpen; // 0x70

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	public Boolean HasFlushedFinalBlock { get; }
	private SemaphoreSlim AsyncActiveSemaphore { get; }

	// RVA: 0x5f4730c VA: 0x759855f30c
	public Void .ctor(Stream stream, ICryptoTransform transform, CryptoStreamMode mode) { }
	// RVA: 0x5f47314 VA: 0x759855f314
	public Void .ctor(Stream stream, ICryptoTransform transform, CryptoStreamMode mode, Boolean leaveOpen) { }
	// RVA: 0x5f47680 VA: 0x759855f680
	public override Boolean get_CanRead() { }
	// RVA: 0x5f47688 VA: 0x759855f688
	public override Boolean get_CanSeek() { }
	// RVA: 0x5f47690 VA: 0x759855f690
	public override Boolean get_CanWrite() { }
	// RVA: 0x5f47698 VA: 0x759855f698
	public override Int64 get_Length() { }
	// RVA: 0x5f476e8 VA: 0x759855f6e8
	public override Int64 get_Position() { }
	// RVA: 0x5f47738 VA: 0x759855f738
	public override Void set_Position(Int64 value) { }
	// RVA: 0x5f47788 VA: 0x759855f788
	public Boolean get_HasFlushedFinalBlock() { }
	// RVA: 0x5f47790 VA: 0x759855f790
	public Void FlushFinalBlock() { }
	// RVA: 0x5f479c0 VA: 0x759855f9c0
	public override Void Flush() { }
	// RVA: 0x5f479c4 VA: 0x759855f9c4
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x5f47b50 VA: 0x759855fb50
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x5f47ba0 VA: 0x759855fba0
	public override Void SetLength(Int64 value) { }
	// RVA: 0x5f47bf0 VA: 0x759855fbf0
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5f47ee8 VA: 0x759855fee8
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x5f47f9c VA: 0x759855ff9c
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x5f47d80 VA: 0x759855fd80
	private Task`1 ReadAsyncInternal(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5f47fe4 VA: 0x759855ffe4
	public override Int32 ReadByte() { }
	// RVA: 0x5f48060 VA: 0x7598560060
	public override Void WriteByte(Byte value) { }
	// RVA: 0x5f480b4 VA: 0x75985600b4
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5f47c38 VA: 0x759855fc38
	private Void CheckReadArguments(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5f48178 VA: 0x7598560178
	private Task`1 ReadAsyncCore(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken, Boolean useAsync) { }
	// RVA: 0x5f482f8 VA: 0x75985602f8
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5f485c0 VA: 0x75985605c0
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x5f48674 VA: 0x7598560674
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x5f48488 VA: 0x7598560488
	private Task WriteAsyncInternal(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x5f48680 VA: 0x7598560680
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5f48340 VA: 0x7598560340
	private Void CheckWriteArguments(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5f486f0 VA: 0x75985606f0
	private Task WriteAsyncCore(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken, Boolean useAsync) { }
	// RVA: 0x5f48848 VA: 0x7598560848
	public Void Clear() { }
	// RVA: 0x5f48858 VA: 0x7598560858
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x5f4750c VA: 0x759855f50c
	private Void InitializeBuffer() { }
	// RVA: 0x5f48908 VA: 0x7598560908
	private SemaphoreSlim get_AsyncActiveSemaphore() { }
}
```