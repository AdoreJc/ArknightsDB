# FtpDataStream

**Namespace:** `System.Net`


## Fields

- `FtpWebRequest _request`

- `NetworkStream _networkStream`

- `Boolean _writeable`

- `Boolean _readable`

- `Boolean _isFullyRead`

- `Boolean _closing`


## Methods

- `Void CheckError()`

- `Void AsyncReadCallback(IAsyncResult)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class FtpDataStream : Stream, ICloseEx
{
	private FtpWebRequest _request; // 0x28
	private NetworkStream _networkStream; // 0x30
	private Boolean _writeable; // 0x38
	private Boolean _readable; // 0x39
	private Boolean _isFullyRead; // 0x3a
	private Boolean _closing; // 0x3b

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	public override Boolean CanTimeout { get; }
	public override Int32 ReadTimeout { get; set; }
	public override Int32 WriteTimeout { get; set; }

	// RVA: 0x641c09c VA: 0x7598a3409c
	internal Void .ctor(NetworkStream networkStream, FtpWebRequest request, TriState writeOnly) { }
	// RVA: 0x641ffac VA: 0x7598a37fac
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6420134 VA: 0x7598a38134
	private Void System.Net.ICloseEx.CloseEx(CloseExState closeState) { }
	// RVA: 0x642052c VA: 0x7598a3852c
	private Void CheckError() { }
	// RVA: 0x6420570 VA: 0x7598a38570
	public override Boolean get_CanRead() { }
	// RVA: 0x6420578 VA: 0x7598a38578
	public override Boolean get_CanSeek() { }
	// RVA: 0x6420598 VA: 0x7598a38598
	public override Boolean get_CanWrite() { }
	// RVA: 0x64205a0 VA: 0x7598a385a0
	public override Int64 get_Length() { }
	// RVA: 0x64205c0 VA: 0x7598a385c0
	public override Int64 get_Position() { }
	// RVA: 0x64205e0 VA: 0x7598a385e0
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6420604 VA: 0x7598a38604
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x64206d0 VA: 0x7598a386d0
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x64207d4 VA: 0x7598a387d4
	public override Void Write(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x64208ac VA: 0x7598a388ac
	private Void AsyncReadCallback(IAsyncResult ar) { }
	// RVA: 0x6420b5c VA: 0x7598a38b5c
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x6420d08 VA: 0x7598a38d08
	public override Int32 EndRead(IAsyncResult ar) { }
	// RVA: 0x6420ea8 VA: 0x7598a38ea8
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x6420f9c VA: 0x7598a38f9c
	public override Void EndWrite(IAsyncResult asyncResult) { }
	// RVA: 0x642103c VA: 0x7598a3903c
	public override Void Flush() { }
	// RVA: 0x6421060 VA: 0x7598a39060
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6421084 VA: 0x7598a39084
	public override Boolean get_CanTimeout() { }
	// RVA: 0x64210a4 VA: 0x7598a390a4
	public override Int32 get_ReadTimeout() { }
	// RVA: 0x64210c8 VA: 0x7598a390c8
	public override Void set_ReadTimeout(Int32 value) { }
	// RVA: 0x64210ec VA: 0x7598a390ec
	public override Int32 get_WriteTimeout() { }
	// RVA: 0x6421110 VA: 0x7598a39110
	public override Void set_WriteTimeout(Int32 value) { }
	// RVA: 0x6421134 VA: 0x7598a39134
	internal Void SetSocketTimeoutOption(Int32 timeout) { }
}
```