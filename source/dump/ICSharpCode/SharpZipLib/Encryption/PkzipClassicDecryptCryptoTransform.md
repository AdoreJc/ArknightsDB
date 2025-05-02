# PkzipClassicDecryptCryptoTransform

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
internal class PkzipClassicDecryptCryptoTransform : PkzipClassicCryptoBase, ICryptoTransform, IDisposable
{

	public Boolean CanReuseTransform { get; }
	public Int32 InputBlockSize { get; }
	public Int32 OutputBlockSize { get; }
	public Boolean CanTransformMultipleBlocks { get; }

	// RVA: 0x5ec3858 VA: 0x75984db858
	internal Void .ctor(Byte[] keyBlock) { }
	// RVA: 0x5ec3884 VA: 0x75984db884
	public Byte[] TransformFinalBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5ec3910 VA: 0x75984db910
	public Int32 TransformBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount, Byte[] outputBuffer, Int32 outputOffset) { }
	// RVA: 0x5ec39d4 VA: 0x75984db9d4
	public Boolean get_CanReuseTransform() { }
	// RVA: 0x5ec39dc VA: 0x75984db9dc
	public Int32 get_InputBlockSize() { }
	// RVA: 0x5ec39e4 VA: 0x75984db9e4
	public Int32 get_OutputBlockSize() { }
	// RVA: 0x5ec39ec VA: 0x75984db9ec
	public Boolean get_CanTransformMultipleBlocks() { }
	// RVA: 0x5ec39f4 VA: 0x75984db9f4
	public Void Dispose() { }
}
```