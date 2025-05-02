# TlsStream

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
internal class TlsStream : Stream
{
	private readonly TlsProtocol handler; // 0x28

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x64ffb20 VA: 0x7598b17b20
	internal Void .ctor(TlsProtocol handler) { }
	// RVA: 0x64ffb94 VA: 0x7598b17b94
	public override Boolean get_CanRead() { }
	// RVA: 0x64ffbc4 VA: 0x7598b17bc4
	public override Boolean get_CanSeek() { }
	// RVA: 0x64ffbcc VA: 0x7598b17bcc
	public override Boolean get_CanWrite() { }
	// RVA: 0x64ffbfc VA: 0x7598b17bfc
	public override Void Close() { }
	// RVA: 0x64ffc30 VA: 0x7598b17c30
	public override Void Flush() { }
	// RVA: 0x64ffc54 VA: 0x7598b17c54
	public override Int64 get_Length() { }
	// RVA: 0x64ffc94 VA: 0x7598b17c94
	public override Int64 get_Position() { }
	// RVA: 0x64ffcd4 VA: 0x7598b17cd4
	public override Void set_Position(Int64 value) { }
	// RVA: 0x64ffd14 VA: 0x7598b17d14
	public override Int32 Read(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64ffd38 VA: 0x7598b17d38
	public override Int32 ReadByte() { }
	// RVA: 0x64ffdd0 VA: 0x7598b17dd0
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x64ffe10 VA: 0x7598b17e10
	public override Void SetLength(Int64 value) { }
	// RVA: 0x64ffe50 VA: 0x7598b17e50
	public override Void Write(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x64ffe74 VA: 0x7598b17e74
	public override Void WriteByte(Byte b) { }
}
```