# Base64Encoder

**Namespace:** `Org.BouncyCastle.Utilities.Encoders`


## Fields

- `Byte padding`


## Methods

- `Void InitialiseDecodingTable()`

- `Int32 Encode(Byte[], Int32, Int32, Stream)`

- `Boolean ignore(Char)`

- `Int32 Decode(Byte[], Int32, Int32, Stream)`

- `Int32 nextI(Byte[], Int32, Int32)`

- `Int32 DecodeString(String, Stream)`

- `Int32 decodeLastBlock(Stream, Char, Char, Char, Char)`

- `Int32 nextI(String, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.Encoders
public class Base64Encoder : IEncoder
{
	protected readonly Byte[] encodingTable; // 0x10
	protected Byte padding; // 0x18
	protected readonly Byte[] decodingTable; // 0x20


	// RVA: 0x66f91e0 VA: 0x7598d111e0
	protected Void InitialiseDecodingTable() { }
	// RVA: 0x66f9258 VA: 0x7598d11258
	public Void .ctor() { }
	// RVA: 0x66f9314 VA: 0x7598d11314
	public Int32 Encode(Byte[] data, Int32 off, Int32 length, Stream outStream) { }
	// RVA: 0x66f9684 VA: 0x7598d11684
	private Boolean ignore(Char c) { }
	// RVA: 0x66f96bc VA: 0x7598d116bc
	public Int32 Decode(Byte[] data, Int32 off, Int32 length, Stream outStream) { }
	// RVA: 0x66f99b0 VA: 0x7598d119b0
	private Int32 nextI(Byte[] data, Int32 i, Int32 finish) { }
	// RVA: 0x66f9c20 VA: 0x7598d11c20
	public Int32 DecodeString(String data, Stream outStream) { }
	// RVA: 0x66f9a24 VA: 0x7598d11a24
	private Int32 decodeLastBlock(Stream outStream, Char c1, Char c2, Char c3, Char c4) { }
	// RVA: 0x66f9f24 VA: 0x7598d11f24
	private Int32 nextI(String data, Int32 i, Int32 finish) { }
}
```