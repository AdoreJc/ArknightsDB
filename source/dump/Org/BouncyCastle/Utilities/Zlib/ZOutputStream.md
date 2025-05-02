# ZOutputStream

**Namespace:** `Org.BouncyCastle.Utilities.Zlib`


## Fields

- `ZStream z`

- `Int32 flushLevel`

- `Boolean compress`

- `Stream output`

- `Boolean closed`


## Methods

- `Void DoClose()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.Zlib
public class ZOutputStream : Stream
{
	private const Int32 BufferSize; // 0x0
	protected ZStream z; // 0x28
	protected Int32 flushLevel; // 0x30
	protected Byte[] buf; // 0x38
	protected Byte[] buf1; // 0x40
	protected Boolean compress; // 0x48
	protected Stream output; // 0x50
	protected Boolean closed; // 0x58

	public sealed override Boolean CanRead { get; }
	public sealed override Boolean CanSeek { get; }
	public sealed override Boolean CanWrite { get; }
	public virtual Int32 FlushMode { get; set; }
	public sealed override Int64 Length { get; }
	public sealed override Int64 Position { get; set; }
	public virtual Int64 TotalIn { get; }
	public virtual Int64 TotalOut { get; }

	// RVA: 0x66f4500 VA: 0x7598d0c500
	private static ZStream GetDefaultZStream(Boolean nowrap) { }
	// RVA: 0x66f45ec VA: 0x7598d0c5ec
	public Void .ctor(Stream output) { }
	// RVA: 0x66f461c VA: 0x7598d0c61c
	public Void .ctor(Stream output, Boolean nowrap) { }
	// RVA: 0x66f464c VA: 0x7598d0c64c
	public Void .ctor(Stream output, ZStream z) { }
	// RVA: 0x66f4794 VA: 0x7598d0c794
	public Void .ctor(Stream output, Int32 level) { }
	// RVA: 0x66f479c VA: 0x7598d0c79c
	public Void .ctor(Stream output, Int32 level, Boolean nowrap) { }
	// RVA: 0x66f48d8 VA: 0x7598d0c8d8
	public sealed override Boolean get_CanRead() { }
	// RVA: 0x66f48e0 VA: 0x7598d0c8e0
	public sealed override Boolean get_CanSeek() { }
	// RVA: 0x66f48e8 VA: 0x7598d0c8e8
	public sealed override Boolean get_CanWrite() { }
	// RVA: 0x66f48f8 VA: 0x7598d0c8f8
	public override Void Close() { }
	// RVA: 0x66f4924 VA: 0x7598d0c924
	private Void DoClose() { }
	// RVA: 0x66f4ae4 VA: 0x7598d0cae4
	public virtual Void End() { }
	// RVA: 0x66f4c10 VA: 0x7598d0cc10
	public virtual Void Finish() { }
	// RVA: 0x66f4df8 VA: 0x7598d0cdf8
	public override Void Flush() { }
	// RVA: 0x66f4e1c VA: 0x7598d0ce1c
	public virtual Int32 get_FlushMode() { }
	// RVA: 0x66f4e24 VA: 0x7598d0ce24
	public virtual Void set_FlushMode(Int32 value) { }
	// RVA: 0x66f4e2c VA: 0x7598d0ce2c
	public sealed override Int64 get_Length() { }
	// RVA: 0x66f4e6c VA: 0x7598d0ce6c
	public sealed override Int64 get_Position() { }
	// RVA: 0x66f4eac VA: 0x7598d0ceac
	public sealed override Void set_Position(Int64 value) { }
	// RVA: 0x66f4eec VA: 0x7598d0ceec
	public sealed override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66f4f2c VA: 0x7598d0cf2c
	public sealed override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x66f4f6c VA: 0x7598d0cf6c
	public sealed override Void SetLength(Int64 value) { }
	// RVA: 0x66f4fac VA: 0x7598d0cfac
	public virtual Int64 get_TotalIn() { }
	// RVA: 0x66f4fc8 VA: 0x7598d0cfc8
	public virtual Int64 get_TotalOut() { }
	// RVA: 0x66f4fe4 VA: 0x7598d0cfe4
	public override Void Write(Byte[] b, Int32 off, Int32 len) { }
	// RVA: 0x66f5190 VA: 0x7598d0d190
	public override Void WriteByte(Byte b) { }
}
```