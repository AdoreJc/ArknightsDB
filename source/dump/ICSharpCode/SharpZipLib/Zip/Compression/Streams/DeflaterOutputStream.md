# DeflaterOutputStream

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression.Streams`


## Fields

- `String password`

- `ICryptoTransform cryptoTransform_`

- `Deflater deflater_`

- `Stream baseOutputStream_`

- `Boolean isClosed_`

- `Boolean isStreamOwner_`


## Properties

- `Boolean CanPatchEntries`

- `String Password`


## Methods

- `Boolean get_CanPatchEntries()`

- `String get_Password()`

- `Void EncryptBlock(Byte[], Int32, Int32)`

- `Void InitializePassword(String)`

- `Void Deflate()`

- `Void GetAuthCodeIfAES()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression.Streams
public class DeflaterOutputStream : Stream
{
	private String password; // 0x28
	private ICryptoTransform cryptoTransform_; // 0x30
	protected Byte[] AESAuthCode; // 0x38
	private Byte[] buffer_; // 0x40
	protected Deflater deflater_; // 0x48
	protected Stream baseOutputStream_; // 0x50
	private Boolean isClosed_; // 0x58
	private Boolean isStreamOwner_; // 0x59

	public Boolean CanPatchEntries { get; }
	public String Password { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x5ec5a08 VA: 0x75984dda08
	public Void .ctor(Stream baseOutputStream, Deflater deflater) { }
	// RVA: 0x5ec5a10 VA: 0x75984dda10
	public Void .ctor(Stream baseOutputStream, Deflater deflater, Int32 bufferSize) { }
	// RVA: 0x5ec5c04 VA: 0x75984ddc04
	public virtual Void Finish() { }
	// RVA: 0x5ec6184 VA: 0x75984de184
	public Boolean get_CanPatchEntries() { }
	// RVA: 0x5ec61a4 VA: 0x75984de1a4
	public String get_Password() { }
	// RVA: 0x5ec6084 VA: 0x75984de084
	protected Void EncryptBlock(Byte[] buffer, Int32 offset, Int32 length) { }
	// RVA: 0x5ec61ac VA: 0x75984de1ac
	protected Void InitializePassword(String password) { }
	// RVA: 0x5ec6344 VA: 0x75984de344
	protected Void Deflate() { }
	// RVA: 0x5ec6468 VA: 0x75984de468
	public override Boolean get_CanRead() { }
	// RVA: 0x5ec6470 VA: 0x75984de470
	public override Boolean get_CanSeek() { }
	// RVA: 0x5ec6478 VA: 0x75984de478
	public override Boolean get_CanWrite() { }
	// RVA: 0x5ec6498 VA: 0x75984de498
	public override Int64 get_Length() { }
	// RVA: 0x5ec64b8 VA: 0x75984de4b8
	public override Int64 get_Position() { }
	// RVA: 0x5ec64d8 VA: 0x75984de4d8
	public override Void set_Position(Int64 value) { }
	// RVA: 0x5ec6528 VA: 0x75984de528
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x5ec6578 VA: 0x75984de578
	public override Void SetLength(Int64 value) { }
	// RVA: 0x5ec65c8 VA: 0x75984de5c8
	public override Int32 ReadByte() { }
	// RVA: 0x5ec6618 VA: 0x75984de618
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ec6668 VA: 0x75984de668
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x5ec66b8 VA: 0x75984de6b8
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x5ec6708 VA: 0x75984de708
	public override Void Flush() { }
	// RVA: 0x5ec6758 VA: 0x75984de758
	public override Void Close() { }
	// RVA: 0x5ec68d8 VA: 0x75984de8d8
	private Void GetAuthCodeIfAES() { }
	// RVA: 0x5ec68dc VA: 0x75984de8dc
	public override Void WriteByte(Byte value) { }
	// RVA: 0x5ec6968 VA: 0x75984de968
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
}
```