# DeflateStreamNative

**Namespace:** `System.IO.Compression`


## Fields

- `UnmanagedReadOrWrite feeder`

- `Stream base_stream`

- `SafeDeflateStreamHandle z_stream`

- `GCHandle data`

- `Boolean disposed`

- `Exception last_error`


## Methods

- `Void Dispose(Boolean)`

- `Void Flush()`

- `Int32 ReadZStream(IntPtr, Int32)`

- `Void WriteZStream(IntPtr, Int32)`

- `Int32 UnmanagedRead(IntPtr, Int32)`

- `Int32 UnmanagedWrite(IntPtr, Int32)`

- `Void CheckResult(Int32, String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.IO.Compression
internal class DeflateStreamNative
{
	private UnmanagedReadOrWrite feeder; // 0x10
	private Stream base_stream; // 0x18
	private SafeDeflateStreamHandle z_stream; // 0x20
	private GCHandle data; // 0x28
	private Boolean disposed; // 0x30
	private Byte[] io_buffer; // 0x38
	private Exception last_error; // 0x40


	// RVA: 0x6412eb4 VA: 0x7598a2aeb4
	private Void .ctor() { }
	// RVA: 0x6411468 VA: 0x7598a29468
	public static DeflateStreamNative Create(Stream compressedStream, CompressionMode mode, Boolean gzip) { }
	// RVA: 0x6413028 VA: 0x7598a2b028
	protected override Void Finalize() { }
	// RVA: 0x6411744 VA: 0x7598a29744
	public Void Dispose(Boolean disposing) { }
	// RVA: 0x641201c VA: 0x7598a2a01c
	public Void Flush() { }
	// RVA: 0x64118a8 VA: 0x7598a298a8
	public Int32 ReadZStream(IntPtr buffer, Int32 length) { }
	// RVA: 0x6411c74 VA: 0x7598a29c74
	public Void WriteZStream(IntPtr buffer, Int32 length) { }
	// RVA: 0x6412d3c VA: 0x7598a2ad3c
	private static Int32 UnmanagedRead(IntPtr buffer, Int32 length, IntPtr data) { }
	// RVA: 0x6413350 VA: 0x7598a2b350
	private Int32 UnmanagedRead(IntPtr buffer, Int32 length) { }
	// RVA: 0x6412df8 VA: 0x7598a2adf8
	private static Int32 UnmanagedWrite(IntPtr buffer, Int32 length, IntPtr data) { }
	// RVA: 0x6413510 VA: 0x7598a2b510
	private Int32 UnmanagedWrite(IntPtr buffer, Int32 length) { }
	// RVA: 0x6413124 VA: 0x7598a2b124
	private Void CheckResult(Int32 result, String where) { }
	// RVA: 0x6412f90 VA: 0x7598a2af90
	private static extern SafeDeflateStreamHandle CreateZStream(CompressionMode compress, Boolean gzip, UnmanagedReadOrWrite feeder, IntPtr data) { }
	// RVA: 0x6413760 VA: 0x7598a2b760
	private static extern Int32 CloseZStream(IntPtr stream) { }
	// RVA: 0x64130c0 VA: 0x7598a2b0c0
	private static extern Int32 Flush(SafeDeflateStreamHandle stream) { }
	// RVA: 0x6413258 VA: 0x7598a2b258
	private static extern Int32 ReadZStream(SafeDeflateStreamHandle stream, IntPtr buffer, Int32 length) { }
	// RVA: 0x64132d4 VA: 0x7598a2b2d4
	private static extern Int32 WriteZStream(SafeDeflateStreamHandle stream, IntPtr buffer, Int32 length) { }
}
```