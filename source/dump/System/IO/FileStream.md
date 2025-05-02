# FileStream

**Namespace:** `System.IO`


## Fields

- `String name`

- `SafeFileHandle safeHandle`

- `Boolean isExposed`

- `Int64 append_startpos`

- `FileAccess access`

- `Boolean owner`

- `Boolean async`

- `Boolean canseek`

- `Boolean anonymous`

- `Boolean buf_dirty`

- `Int32 buf_size`

- `Int32 buf_length`

- `Int32 buf_offset`

- `Int64 buf_start`


## Methods

- `Void Init(SafeFileHandle, FileAccess, Boolean, Int32, Boolean, Boolean)`

- `Void ExposeHandle()`

- `Int32 ReadInternal(Byte[], Int32, Int32)`

- `Void WriteInternal(Byte[], Int32, Int32)`

- `Int32 ReadSegment(Byte[], Int32, Int32)`

- `Int32 WriteSegment(Byte[], Int32, Int32)`

- `Void FlushBuffer()`

- `Void FlushBufferIfDirty()`

- `Void RefillBuffer()`

- `Int32 ReadData(SafeHandle, Byte[], Int32, Int32)`

- `Void InitBuffer(Int32, Boolean)`

- `String GetSecureFileName(String)`

- `String GetSecureFileName(String, Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class FileStream : Stream
{
	internal const Int32 DefaultBufferSize; // 0x0
	private static Byte[] buf_recycle; // 0x0
	private static readonly Object buf_recycle_lock; // 0x8
	private Byte[] buf; // 0x28
	private String name; // 0x30
	private SafeFileHandle safeHandle; // 0x38
	private Boolean isExposed; // 0x40
	private Int64 append_startpos; // 0x48
	private FileAccess access; // 0x50
	private Boolean owner; // 0x54
	private Boolean async; // 0x55
	private Boolean canseek; // 0x56
	private Boolean anonymous; // 0x57
	private Boolean buf_dirty; // 0x58
	private Int32 buf_size; // 0x5c
	private Int32 buf_length; // 0x60
	private Int32 buf_offset; // 0x64
	private Int64 buf_start; // 0x68

	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	public override Boolean CanSeek { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	public virtual SafeFileHandle SafeFileHandle { get; }

	// RVA: 0x6033bac VA: 0x759864bbac
	internal Void .ctor(IntPtr handle, FileAccess access, Boolean ownsHandle, Int32 bufferSize, Boolean isAsync, Boolean isConsoleWrapper) { }
	// RVA: 0x6034054 VA: 0x759864c054
	public Void .ctor(String path, FileMode mode) { }
	// RVA: 0x60347e4 VA: 0x759864c7e4
	public Void .ctor(String path, FileMode mode, FileAccess access) { }
	// RVA: 0x6034828 VA: 0x759864c828
	public Void .ctor(String path, FileMode mode, FileAccess access, FileShare share) { }
	// RVA: 0x603484c VA: 0x759864c84c
	public Void .ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize) { }
	// RVA: 0x603486c VA: 0x759864c86c
	public Void .ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, Boolean useAsync) { }
	// RVA: 0x6034894 VA: 0x759864c894
	public Void .ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, FileOptions options) { }
	// RVA: 0x6034810 VA: 0x759864c810
	internal Void .ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, Boolean isAsync, Boolean anonymous) { }
	// RVA: 0x6034088 VA: 0x759864c088
	internal Void .ctor(String path, FileMode mode, FileAccess access, FileShare share, Int32 bufferSize, Boolean anonymous, FileOptions options) { }
	// RVA: 0x6033d60 VA: 0x759864bd60
	private Void Init(SafeFileHandle safeHandle, FileAccess access, Boolean ownsHandle, Int32 bufferSize, Boolean isAsync, Boolean isConsoleWrapper) { }
	// RVA: 0x603617c VA: 0x759864e17c
	public override Boolean get_CanRead() { }
	// RVA: 0x6036190 VA: 0x759864e190
	public override Boolean get_CanWrite() { }
	// RVA: 0x60361a4 VA: 0x759864e1a4
	public override Boolean get_CanSeek() { }
	// RVA: 0x60361ac VA: 0x759864e1ac
	public override Int64 get_Length() { }
	// RVA: 0x6036448 VA: 0x759864e448
	public override Int64 get_Position() { }
	// RVA: 0x60365b8 VA: 0x759864e5b8
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6036648 VA: 0x759864e648
	public virtual SafeFileHandle get_SafeFileHandle() { }
	// RVA: 0x6036014 VA: 0x759864e014
	private Void ExposeHandle() { }
	// RVA: 0x60367fc VA: 0x759864e7fc
	public override Int32 ReadByte() { }
	// RVA: 0x6036a9c VA: 0x759864ea9c
	public override Void WriteByte(Byte value) { }
	// RVA: 0x6036bf8 VA: 0x759864ebf8
	public override Int32 Read([In] [Out] Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x6036e60 VA: 0x759864ee60
	private Int32 ReadInternal(Byte[] dest, Int32 offset, Int32 count) { }
	// RVA: 0x6036fb4 VA: 0x759864efb4
	public override IAsyncResult BeginRead(Byte[] array, Int32 offset, Int32 numBytes, AsyncCallback userCallback, Object stateObject) { }
	// RVA: 0x60373d4 VA: 0x759864f3d4
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x6037564 VA: 0x759864f564
	public override Void Write(Byte[] array, Int32 offset, Int32 count) { }
	// RVA: 0x60377a0 VA: 0x759864f7a0
	private Void WriteInternal(Byte[] src, Int32 offset, Int32 count) { }
	// RVA: 0x6037b14 VA: 0x759864fb14
	public override IAsyncResult BeginWrite(Byte[] array, Int32 offset, Int32 numBytes, AsyncCallback userCallback, Object stateObject) { }
	// RVA: 0x6038088 VA: 0x7598650088
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x6038200 VA: 0x7598650200
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x6038464 VA: 0x7598650464
	public override Void SetLength(Int64 value) { }
	// RVA: 0x60387a4 VA: 0x75986507a4
	public override Void Flush() { }
	// RVA: 0x603881c VA: 0x759865081c
	protected override Void Finalize() { }
	// RVA: 0x60388c0 VA: 0x75986508c0
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6038c10 VA: 0x7598650c10
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x6038c9c VA: 0x7598650c9c
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6038ca4 VA: 0x7598650ca4
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6036efc VA: 0x759864eefc
	private Int32 ReadSegment(Byte[] dest, Int32 dest_offset, Int32 count) { }
	// RVA: 0x6037a9c VA: 0x759864fa9c
	private Int32 WriteSegment(Byte[] src, Int32 src_offset, Int32 count) { }
	// RVA: 0x6036684 VA: 0x759864e684
	private Void FlushBuffer() { }
	// RVA: 0x6036310 VA: 0x759864e310
	private Void FlushBufferIfDirty() { }
	// RVA: 0x6036a6c VA: 0x759864ea6c
	private Void RefillBuffer() { }
	// RVA: 0x6036944 VA: 0x759864e944
	private Int32 ReadData(SafeHandle safeHandle, Byte[] buf, Int32 offset, Int32 count) { }
	// RVA: 0x6035d50 VA: 0x759864dd50
	private Void InitBuffer(Int32 size, Boolean isZeroSize) { }
	// RVA: 0x6035494 VA: 0x759864d494
	private String GetSecureFileName(String filename) { }
	// RVA: 0x6034f44 VA: 0x759864cf44
	private String GetSecureFileName(String filename, Boolean full) { }
	// RVA: 0x6038f04 VA: 0x7598650f04
	private static Void .cctor() { }
}
```