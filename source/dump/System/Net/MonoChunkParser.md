# MonoChunkParser

**Namespace:** `System.Net`


## Fields

- `WebHeaderCollection headers`

- `Int32 chunkSize`

- `Int32 chunkRead`

- `Int32 totalWritten`

- `State state`

- `StringBuilder saved`

- `Boolean sawCR`

- `Boolean gotit`

- `Int32 trailerState`

- `ArrayList chunks`


## Properties

- `Boolean WantMore`

- `Boolean DataAvailable`

- `Int32 ChunkLeft`


## Methods

- `Int32 Read(Byte[], Int32, Int32)`

- `Int32 ReadFromChunks(Byte[], Int32, Int32)`

- `Void Write(Byte[], Int32, Int32)`

- `Void InternalWrite(Byte[], ref, Int32)`

- `Boolean get_WantMore()`

- `Boolean get_DataAvailable()`

- `Int32 get_ChunkLeft()`

- `State ReadBody(Byte[], ref, Int32)`

- `State GetChunkSize(Byte[], ref, Int32)`

- `State ReadCRLF(Byte[], ref, Int32)`

- `State ReadTrailer(Byte[], ref, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class MonoChunkParser
{
	private WebHeaderCollection headers; // 0x10
	private Int32 chunkSize; // 0x18
	private Int32 chunkRead; // 0x1c
	private Int32 totalWritten; // 0x20
	private State state; // 0x24
	private StringBuilder saved; // 0x28
	private Boolean sawCR; // 0x30
	private Boolean gotit; // 0x31
	private Int32 trailerState; // 0x34
	private ArrayList chunks; // 0x38

	public Boolean WantMore { get; }
	public Boolean DataAvailable { get; }
	public Int32 ChunkLeft { get; }

	// RVA: 0x632ea6c VA: 0x7598946a6c
	public Void .ctor(WebHeaderCollection headers) { }
	// RVA: 0x632eb48 VA: 0x7598946b48
	public Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x632eb4c VA: 0x7598946b4c
	private Int32 ReadFromChunks(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x632eecc VA: 0x7598946ecc
	public Void Write(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x632eeec VA: 0x7598946eec
	private Void InternalWrite(Byte[] buffer, ref Int32 offset, Int32 size) { }
	// RVA: 0x632f840 VA: 0x7598947840
	public Boolean get_WantMore() { }
	// RVA: 0x632f868 VA: 0x7598947868
	public Boolean get_DataAvailable() { }
	// RVA: 0x632f968 VA: 0x7598947968
	public Int32 get_ChunkLeft() { }
	// RVA: 0x632f330 VA: 0x7598947330
	private State ReadBody(Byte[] buffer, ref Int32 offset, Int32 size) { }
	// RVA: 0x632f028 VA: 0x7598947028
	private State GetChunkSize(Byte[] buffer, ref Int32 offset, Int32 size) { }
	// RVA: 0x632f9fc VA: 0x75989479fc
	private static String RemoveChunkExtension(String input) { }
	// RVA: 0x632f474 VA: 0x7598947474
	private State ReadCRLF(Byte[] buffer, ref Int32 offset, Int32 size) { }
	// RVA: 0x632f574 VA: 0x7598947574
	private State ReadTrailer(Byte[] buffer, ref Int32 offset, Int32 size) { }
	// RVA: 0x632f9a4 VA: 0x75989479a4
	private static Void ThrowProtocolViolation(String message) { }
}
```