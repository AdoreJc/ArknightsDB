# Tree

**Namespace:** ` `


## Fields

- `Int32 minNumCodes`

- `Int32 numCodes`

- `Int32 maxLength`

- `DeflaterHuffman dh`


## Methods

- `Void Reset()`

- `Void WriteSymbol(Int32)`

- `Void SetStaticCodes(Int16[], Byte[])`

- `Void BuildCodes()`

- `Void BuildTree()`

- `Int32 GetEncodedLength()`

- `Void CalcBLFreq(Tree)`

- `Void WriteTree(Tree)`

- `Void BuildLength(Int32[])`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : 
private class Tree
{
	public Int16[] freqs; // 0x10
	public Byte[] length; // 0x18
	public Int32 minNumCodes; // 0x20
	public Int32 numCodes; // 0x24
	private Int16[] codes; // 0x28
	private Int32[] bl_counts; // 0x30
	private Int32 maxLength; // 0x38
	private DeflaterHuffman dh; // 0x40


	// RVA: 0x5ec9d3c VA: 0x75984e1d3c
	public Void .ctor(DeflaterHuffman dh, Int32 elems, Int32 minCodes, Int32 maxLength) { }
	// RVA: 0x5ec9e10 VA: 0x75984e1e10
	public Void Reset() { }
	// RVA: 0x5eca5c8 VA: 0x75984e25c8
	public Void WriteSymbol(Int32 code) { }
	// RVA: 0x5ecaf94 VA: 0x75984e2f94
	public Void SetStaticCodes(Int16[] staticCodes, Byte[] staticLengths) { }
	// RVA: 0x5ec9ff4 VA: 0x75984e1ff4
	public Void BuildCodes() { }
	// RVA: 0x5eca70c VA: 0x75984e270c
	public Void BuildTree() { }
	// RVA: 0x5ecaf14 VA: 0x75984e2f14
	public Int32 GetEncodedLength() { }
	// RVA: 0x5ecada0 VA: 0x75984e2da0
	public Void CalcBLFreq(Tree blTree) { }
	// RVA: 0x5eca1e4 VA: 0x75984e21e4
	public Void WriteTree(Tree blTree) { }
	// RVA: 0x5ecafc4 VA: 0x75984e2fc4
	private Void BuildLength(Int32[] childs) { }
}
```