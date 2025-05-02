# InflaterHuffmanTree

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Methods

- `Void BuildTree(Byte[])`

- `Int32 GetSymbol(StreamManipulator)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class InflaterHuffmanTree
{
	private Int16[] tree; // 0x10
	public static InflaterHuffmanTree defLitLenTree; // 0x0
	public static InflaterHuffmanTree defDistTree; // 0x8


	// RVA: 0x5ecca68 VA: 0x75984e4a68
	private static Void .cctor() { }
	// RVA: 0x5ecc90c VA: 0x75984e490c
	public Void .ctor(Byte[] codeLengths) { }
	// RVA: 0x5eccd30 VA: 0x75984e4d30
	private Void BuildTree(Byte[] codeLengths) { }
	// RVA: 0x5ecb9f8 VA: 0x75984e39f8
	public Int32 GetSymbol(StreamManipulator input) { }
}
```