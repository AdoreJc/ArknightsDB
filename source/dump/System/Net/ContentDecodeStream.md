# ContentDecodeStream

**Namespace:** `System.Net`


## Properties

- `Stream OriginalInnerStream`


## Methods

- `Stream get_OriginalInnerStream()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ContentDecodeStream : WebReadStream
{
	private readonly Stream <OriginalInnerStream>k__BackingField; // 0x40

	private Stream OriginalInnerStream { get; }

	// RVA: 0x63232c0 VA: 0x759893b2c0
	public static ContentDecodeStream Create(WebOperation operation, Stream innerStream, Mode mode) { }
	// RVA: 0x63233e8 VA: 0x759893b3e8
	private Stream get_OriginalInnerStream() { }
	// RVA: 0x63233b8 VA: 0x759893b3b8
	private Void .ctor(WebOperation operation, Stream decodeStream, Stream originalInnerStream) { }
	// RVA: 0x63233f0 VA: 0x759893b3f0
	protected override Task`1 ProcessReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
	// RVA: 0x6323414 VA: 0x759893b414
	internal override Task FinishReading(CancellationToken cancellationToken) { }
}
```