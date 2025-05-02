# BufferedReadStream

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class BufferedReadStream : WebReadStream
{
	private readonly BufferOffsetSize readBuffer; // 0x40


	// RVA: 0x6322cd8 VA: 0x759893acd8
	public Void .ctor(WebOperation operation, Stream innerStream, BufferOffsetSize readBuffer) { }
	// RVA: 0x6322d08 VA: 0x759893ad08
	protected override Task`1 ProcessReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x6322e78 VA: 0x759893ae78
	internal Boolean TryReadFromBuffer(Byte[] buffer, Int32 offset, Int32 size, out Int32 result) { }
}
```