# HexEncoder

**Namespace:** `Org.BouncyCastle.Utilities.Encoders`


## Methods

- `Void InitialiseDecodingTable()`

- `Int32 Encode(Byte[], Int32, Int32, Stream)`

- `Int32 Decode(Byte[], Int32, Int32, Stream)`

- `Int32 DecodeString(String, Stream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.Encoders
public class HexEncoder : IEncoder
{
	protected readonly Byte[] encodingTable; // 0x10
	protected readonly Byte[] decodingTable; // 0x18


	// RVA: 0x66fa8a0 VA: 0x7598d128a0
	protected Void InitialiseDecodingTable() { }
	// RVA: 0x66fa7ec VA: 0x7598d127ec
	public Void .ctor() { }
	// RVA: 0x66fa9c0 VA: 0x7598d129c0
	public Int32 Encode(Byte[] data, Int32 off, Int32 length, Stream outStream) { }
	// RVA: 0x66faaa4 VA: 0x7598d12aa4
	private static Boolean Ignore(Char c) { }
	// RVA: 0x66faadc VA: 0x7598d12adc
	public Int32 Decode(Byte[] data, Int32 off, Int32 length, Stream outStream) { }
	// RVA: 0x66fad24 VA: 0x7598d12d24
	public Int32 DecodeString(String data, Stream outStream) { }
}
```