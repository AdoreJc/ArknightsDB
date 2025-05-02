# MonoChunkStream

**Namespace:** `System.Net`


## Properties

- `MonoChunkParser Decoder`


## Methods

- `MonoChunkParser get_Decoder()`

- `Task <>n__0(CancellationToken)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class MonoChunkStream : WebReadStream
{
	private readonly WebHeaderCollection <Headers>k__BackingField; // 0x40
	private readonly MonoChunkParser <Decoder>k__BackingField; // 0x48

	protected MonoChunkParser Decoder { get; }

	// RVA: 0x632fa44 VA: 0x7598947a44
	protected MonoChunkParser get_Decoder() { }
	// RVA: 0x632fa4c VA: 0x7598947a4c
	public Void .ctor(WebOperation operation, Stream innerStream, WebHeaderCollection headers) { }
	// RVA: 0x632faf4 VA: 0x7598947af4
	protected override Task`1 ProcessReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x632fc64 VA: 0x7598947c64
	internal override Task FinishReading(CancellationToken cancellationToken) { }
	// RVA: 0x632fd6c VA: 0x7598947d6c
	private static Void ThrowExpectingChunkTrailer() { }
	// RVA: 0x632fdc8 VA: 0x7598947dc8
	private Task <>n__0(CancellationToken cancellationToken) { }
}
```