# FixedSizeReadStream

**Namespace:** `System.Net`


## Fields

- `Int64 position`


## Properties

- `Int64 ContentLength`


## Methods

- `Int64 get_ContentLength()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class FixedSizeReadStream : WebReadStream
{
	private readonly Int64 <ContentLength>k__BackingField; // 0x40
	private Int64 position; // 0x48

	public Int64 ContentLength { get; }

	// RVA: 0x6326914 VA: 0x759893e914
	public Int64 get_ContentLength() { }
	// RVA: 0x632691c VA: 0x759893e91c
	public Void .ctor(WebOperation operation, Stream innerStream, Int64 contentLength) { }
	// RVA: 0x6326944 VA: 0x759893e944
	protected override Task`1 ProcessReadAsync(Byte[] buffer, Int32 offset, Int32 size, CancellationToken cancellationToken) { }
}
```