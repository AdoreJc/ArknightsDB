# Inflater

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `Int32 mode`

- `Int32 readAdler`

- `Int32 neededBits`

- `Int32 repLength`

- `Int32 repDist`

- `Int32 uncomprLen`

- `Boolean isLastBlock`

- `Int64 totalOut`

- `Int64 totalIn`

- `Boolean noHeader`

- `StreamManipulator input`

- `OutputWindow outputWindow`

- `InflaterDynHeader dynHeader`

- `InflaterHuffmanTree litlenTree`

- `InflaterHuffmanTree distTree`

- `Adler32 adler`


## Properties

- `Boolean IsNeedingInput`

- `Boolean IsNeedingDictionary`

- `Boolean IsFinished`

- `Int64 TotalOut`

- `Int64 TotalIn`

- `Int32 RemainingInput`


## Methods

- `Void Reset()`

- `Boolean DecodeHeader()`

- `Boolean DecodeDict()`

- `Boolean DecodeHuffman()`

- `Boolean DecodeChksum()`

- `Boolean Decode()`

- `Void SetInput(Byte[])`

- `Void SetInput(Byte[], Int32, Int32)`

- `Int32 Inflate(Byte[], Int32, Int32)`

- `Boolean get_IsNeedingInput()`

- `Boolean get_IsNeedingDictionary()`

- `Boolean get_IsFinished()`

- `Int64 get_TotalOut()`

- `Int64 get_TotalIn()`

- `Int32 get_RemainingInput()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class Inflater
{
	private static readonly Int32[] CPLENS; // 0x0
	private static readonly Int32[] CPLEXT; // 0x8
	private static readonly Int32[] CPDIST; // 0x10
	private static readonly Int32[] CPDEXT; // 0x18
	private Int32 mode; // 0x10
	private Int32 readAdler; // 0x14
	private Int32 neededBits; // 0x18
	private Int32 repLength; // 0x1c
	private Int32 repDist; // 0x20
	private Int32 uncomprLen; // 0x24
	private Boolean isLastBlock; // 0x28
	private Int64 totalOut; // 0x30
	private Int64 totalIn; // 0x38
	private Boolean noHeader; // 0x40
	private StreamManipulator input; // 0x48
	private OutputWindow outputWindow; // 0x50
	private InflaterDynHeader dynHeader; // 0x58
	private InflaterHuffmanTree litlenTree; // 0x60
	private InflaterHuffmanTree distTree; // 0x68
	private Adler32 adler; // 0x70

	public Boolean IsNeedingInput { get; }
	public Boolean IsNeedingDictionary { get; }
	public Boolean IsFinished { get; }
	public Int64 TotalOut { get; }
	public Int64 TotalIn { get; }
	public Int32 RemainingInput { get; }

	// RVA: 0x5ecb3fc VA: 0x75984e33fc
	public Void .ctor() { }
	// RVA: 0x5ec4e38 VA: 0x75984dce38
	public Void .ctor(Boolean noHeader) { }
	// RVA: 0x5ec5840 VA: 0x75984dd840
	public Void Reset() { }
	// RVA: 0x5ecb404 VA: 0x75984e3404
	private Boolean DecodeHeader() { }
	// RVA: 0x5ecb518 VA: 0x75984e3518
	private Boolean DecodeDict() { }
	// RVA: 0x5ecb584 VA: 0x75984e3584
	private Boolean DecodeHuffman() { }
	// RVA: 0x5ecbb30 VA: 0x75984e3b30
	private Boolean DecodeChksum() { }
	// RVA: 0x5ecbd38 VA: 0x75984e3d38
	private Boolean Decode() { }
	// RVA: 0x5ecc744 VA: 0x75984e4744
	public Void SetInput(Byte[] buffer) { }
	// RVA: 0x5ec6a10 VA: 0x75984dea10
	public Void SetInput(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x5ec4b30 VA: 0x75984dcb30
	public Int32 Inflate(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ec4d88 VA: 0x75984dcd88
	public Boolean get_IsNeedingInput() { }
	// RVA: 0x5ec4b0c VA: 0x75984dcb0c
	public Boolean get_IsNeedingDictionary() { }
	// RVA: 0x5ec4d50 VA: 0x75984dcd50
	public Boolean get_IsFinished() { }
	// RVA: 0x5ecc760 VA: 0x75984e4760
	public Int64 get_TotalOut() { }
	// RVA: 0x5ecc768 VA: 0x75984e4768
	public Int64 get_TotalIn() { }
	// RVA: 0x5ec5818 VA: 0x75984dd818
	public Int32 get_RemainingInput() { }
	// RVA: 0x5ecc798 VA: 0x75984e4798
	private static Void .cctor() { }
}
```