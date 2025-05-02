# XmlRegisteredNonCachedStream

**Namespace:** `System.Xml`


## Fields

- `Stream stream`

- `XmlDownloadManager downloadManager`

- `String host`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlRegisteredNonCachedStream : Stream
{
	protected Stream stream; // 0x28
	private XmlDownloadManager downloadManager; // 0x30
	private String host; // 0x38

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x62ca60c VA: 0x75988e260c
	internal Void .ctor(Stream stream, XmlDownloadManager downloadManager, String host) { }
	// RVA: 0x62cb5dc VA: 0x75988e35dc
	protected override Void Finalize() { }
	// RVA: 0x62cb690 VA: 0x75988e3690
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x62cb7d4 VA: 0x75988e37d4
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x62cb7f8 VA: 0x75988e37f8
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x62cb81c VA: 0x75988e381c
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x62cb840 VA: 0x75988e3840
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x62cb864 VA: 0x75988e3864
	public override Void Flush() { }
	// RVA: 0x62cb888 VA: 0x75988e3888
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x62cb8ac VA: 0x75988e38ac
	public override Int32 ReadByte() { }
	// RVA: 0x62cb8d0 VA: 0x75988e38d0
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x62cb8f4 VA: 0x75988e38f4
	public override Void SetLength(Int64 value) { }
	// RVA: 0x62cb918 VA: 0x75988e3918
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x62cb93c VA: 0x75988e393c
	public override Void WriteByte(Byte value) { }
	// RVA: 0x62cb960 VA: 0x75988e3960
	public override Boolean get_CanRead() { }
	// RVA: 0x62cb980 VA: 0x75988e3980
	public override Boolean get_CanSeek() { }
	// RVA: 0x62cb9a0 VA: 0x75988e39a0
	public override Boolean get_CanWrite() { }
	// RVA: 0x62cb9c0 VA: 0x75988e39c0
	public override Int64 get_Length() { }
	// RVA: 0x62cb9e0 VA: 0x75988e39e0
	public override Int64 get_Position() { }
	// RVA: 0x62cba00 VA: 0x75988e3a00
	public override Void set_Position(Int64 value) { }
}
```