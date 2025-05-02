# Deflater

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `Int32 level`

- `Boolean noZlibHeaderOrFooter`

- `Int32 state`

- `Int64 totalOut`

- `DeflaterPending pending`

- `DeflaterEngine engine`


## Properties

- `Int64 TotalOut`

- `Boolean IsFinished`

- `Boolean IsNeedingInput`


## Methods

- `Void Reset()`

- `Int64 get_TotalOut()`

- `Void Flush()`

- `Void Finish()`

- `Boolean get_IsFinished()`

- `Boolean get_IsNeedingInput()`

- `Void SetInput(Byte[])`

- `Void SetInput(Byte[], Int32, Int32)`

- `Void SetLevel(Int32)`

- `Void SetStrategy(DeflateStrategy)`

- `Int32 Deflate(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class Deflater
{
	private Int32 level; // 0x10
	private Boolean noZlibHeaderOrFooter; // 0x14
	private Int32 state; // 0x18
	private Int64 totalOut; // 0x20
	private DeflaterPending pending; // 0x28
	private DeflaterEngine engine; // 0x30

	public Int64 TotalOut { get; }
	public Boolean IsFinished { get; }
	public Boolean IsNeedingInput { get; }

	// RVA: 0x5ec7584 VA: 0x75984df584
	public Void .ctor() { }
	// RVA: 0x5ec7590 VA: 0x75984df590
	public Void .ctor(Int32 level, Boolean noZlibHeaderOrFooter) { }
	// RVA: 0x5ec7924 VA: 0x75984df924
	public Void Reset() { }
	// RVA: 0x5ec7a14 VA: 0x75984dfa14
	public Int64 get_TotalOut() { }
	// RVA: 0x5ec6748 VA: 0x75984de748
	public Void Flush() { }
	// RVA: 0x5ec5dec VA: 0x75984dddec
	public Void Finish() { }
	// RVA: 0x5ec614c VA: 0x75984de14c
	public Boolean get_IsFinished() { }
	// RVA: 0x5ec6444 VA: 0x75984de444
	public Boolean get_IsNeedingInput() { }
	// RVA: 0x5ec7a3c VA: 0x75984dfa3c
	public Void SetInput(Byte[] input) { }
	// RVA: 0x5ec698c VA: 0x75984de98c
	public Void SetInput(Byte[] input, Int32 offset, Int32 count) { }
	// RVA: 0x5ec7890 VA: 0x75984df890
	public Void SetLevel(Int32 level) { }
	// RVA: 0x5ec7874 VA: 0x75984df874
	public Void SetStrategy(DeflateStrategy strategy) { }
	// RVA: 0x5ec5dfc VA: 0x75984dddfc
	public Int32 Deflate(Byte[] output, Int32 offset, Int32 length) { }
}
```