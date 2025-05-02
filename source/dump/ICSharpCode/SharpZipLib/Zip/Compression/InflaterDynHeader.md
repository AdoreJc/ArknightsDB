# InflaterDynHeader

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `InflaterHuffmanTree blTree`

- `Int32 mode`

- `Int32 lnum`

- `Int32 dnum`

- `Int32 blnum`

- `Int32 num`

- `Int32 repSymbol`

- `Byte lastLen`

- `Int32 ptr`


## Methods

- `Boolean Decode(StreamManipulator)`

- `InflaterHuffmanTree BuildLitLenTree()`

- `InflaterHuffmanTree BuildDistTree()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
internal class InflaterDynHeader
{
	private static readonly Int32[] repMin; // 0x0
	private static readonly Int32[] repBits; // 0x8
	private static readonly Int32[] BL_ORDER; // 0x10
	private Byte[] blLens; // 0x10
	private Byte[] litdistLens; // 0x18
	private InflaterHuffmanTree blTree; // 0x20
	private Int32 mode; // 0x28
	private Int32 lnum; // 0x2c
	private Int32 dnum; // 0x30
	private Int32 blnum; // 0x34
	private Int32 num; // 0x38
	private Int32 repSymbol; // 0x3c
	private Byte lastLen; // 0x40
	private Int32 ptr; // 0x44


	// RVA: 0x5ecc140 VA: 0x75984e4140
	public Void .ctor() { }
	// RVA: 0x5ecc148 VA: 0x75984e4148
	public Boolean Decode(StreamManipulator input) { }
	// RVA: 0x5ecc5d8 VA: 0x75984e45d8
	public InflaterHuffmanTree BuildLitLenTree() { }
	// RVA: 0x5ecc690 VA: 0x75984e4690
	public InflaterHuffmanTree BuildDistTree() { }
	// RVA: 0x5ecc938 VA: 0x75984e4938
	private static Void .cctor() { }
}
```