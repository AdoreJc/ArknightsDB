# PkzipClassicEncryptCryptoTransform

**Namespace:** `ICSharpCode.SharpZipLib.Encryption`


## Properties

- `Boolean CanReuseTransform`

- `Int32 InputBlockSize`

- `Int32 OutputBlockSize`

- `Boolean CanTransformMultipleBlocks`


## Methods

- `Int32 TransformBlock(Byte[], Int32, Int32, Byte[], Int32)`

- `Boolean get_CanReuseTransform()`

- `Int32 get_InputBlockSize()`

- `Int32 get_OutputBlockSize()`

- `Boolean get_CanTransformMultipleBlocks()`

- `Void Dispose()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Encryption
internal class PkzipClassicEncryptCryptoTransform : PkzipClassicCryptoBase, ICryptoTransform, IDisposable
{

	public Boolean CanReuseTransform { get; }
	public Int32 InputBlockSize { get; }
	public Int32 OutputBlockSize { get; }
	public Boolean CanTransformMultipleBlocks { get; }

	// RVA: 0x5ec36ac VA: 0x75984db6ac
	internal Void .ctor(Byte[] keyBlock) { }
	// RVA: 0x5ec36d8 VA: 0x75984db6d8
	public Byte[] TransformFinalBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5ec3764 VA: 0x75984db764
	public Int32 TransformBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount, Byte[] outputBuffer, Int32 outputOffset) { }
	// RVA: 0x5ec3834 VA: 0x75984db834
	public Boolean get_CanReuseTransform() { }
	// RVA: 0x5ec383c VA: 0x75984db83c
	public Int32 get_InputBlockSize() { }
	// RVA: 0x5ec3844 VA: 0x75984db844
	public Int32 get_OutputBlockSize() { }
	// RVA: 0x5ec384c VA: 0x75984db84c
	public Boolean get_CanTransformMultipleBlocks() { }
	// RVA: 0x5ec3854 VA: 0x75984db854
	public Void Dispose() { }
}
```