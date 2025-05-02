# ByteQueueStream

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class ByteQueueStream : Stream
{
	private readonly ByteQueue buffer; // 0x28

	public virtual Int32 Available { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x64db6e4 VA: 0x7598af36e4
	public Void .ctor() { }
	// RVA: 0x64db77c VA: 0x7598af377c
	public virtual Int32 get_Available() { }
	// RVA: 0x64db798 VA: 0x7598af3798
	public override Boolean get_CanRead() { }
	// RVA: 0x64db7a0 VA: 0x7598af37a0
	public override Boolean get_CanSeek() { }
	// RVA: 0x64db7a8 VA: 0x7598af37a8
	public override Boolean get_CanWrite() { }
	// RVA: 0x64db7b0 VA: 0x7598af37b0
	public override Void Flush() { }
	// RVA: 0x64db7b4 VA: 0x7598af37b4
	public override Int64 get_Length() { }
	// RVA: 0x64db7f4 VA: 0x7598af37f4
	public virtual Int32 Peek(Byte[] buf) { }
	// RVA: 0x64db894 VA: 0x7598af3894
	public override Int64 get_Position() { }
	// RVA: 0x64db8d4 VA: 0x7598af38d4
	public override Void set_Position(Int64 value) { }
	// RVA: 0x64db914 VA: 0x7598af3914
	public virtual Int32 Read(Byte[] buf) { }
	// RVA: 0x64db93c VA: 0x7598af393c
	public override Int32 Read(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64db9f4 VA: 0x7598af39f4
	public override Int32 ReadByte() { }
	// RVA: 0x64dba3c VA: 0x7598af3a3c
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x64dba7c VA: 0x7598af3a7c
	public override Void SetLength(Int64 value) { }
	// RVA: 0x64dbabc VA: 0x7598af3abc
	public virtual Int32 Skip(Int32 n) { }
	// RVA: 0x64dbb4c VA: 0x7598af3b4c
	public virtual Void Write(Byte[] buf) { }
	// RVA: 0x64dbb70 VA: 0x7598af3b70
	public override Void Write(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64dbb88 VA: 0x7598af3b88
	public override Void WriteByte(Byte b) { }
}
```