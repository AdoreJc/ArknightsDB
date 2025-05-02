# DeflaterEngine

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `Int32 ins_h`

- `Int32 matchStart`

- `Int32 matchLen`

- `Boolean prevAvailable`

- `Int32 blockStart`

- `Int32 strstart`

- `Int32 lookahead`

- `DeflateStrategy strategy`

- `Int32 max_chain`

- `Int32 max_lazy`

- `Int32 niceLength`

- `Int32 goodLength`

- `Int32 compressionFunction`

- `Int64 totalIn`

- `Int32 inputOff`

- `Int32 inputEnd`

- `DeflaterPending pending`

- `DeflaterHuffman huffman`

- `Adler32 adler`


## Properties

- `Int32 Adler`

- `DeflateStrategy Strategy`


## Methods

- `Boolean Deflate(Boolean, Boolean)`

- `Void SetInput(Byte[], Int32, Int32)`

- `Boolean NeedsInput()`

- `Void Reset()`

- `Void ResetAdler()`

- `Int32 get_Adler()`

- `Void set_Strategy(DeflateStrategy)`

- `Void SetLevel(Int32)`

- `Void FillWindow()`

- `Void UpdateHash()`

- `Int32 InsertString()`

- `Void SlideWindow()`

- `Boolean FindLongestMatch(Int32)`

- `Boolean DeflateStored(Boolean, Boolean)`

- `Boolean DeflateFast(Boolean, Boolean)`

- `Boolean DeflateSlow(Boolean, Boolean)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class DeflaterEngine : DeflaterConstants
{
	private Int32 ins_h; // 0x10
	private Int16[] head; // 0x18
	private Int16[] prev; // 0x20
	private Int32 matchStart; // 0x28
	private Int32 matchLen; // 0x2c
	private Boolean prevAvailable; // 0x30
	private Int32 blockStart; // 0x34
	private Int32 strstart; // 0x38
	private Int32 lookahead; // 0x3c
	private Byte[] window; // 0x40
	private DeflateStrategy strategy; // 0x48
	private Int32 max_chain; // 0x4c
	private Int32 max_lazy; // 0x50
	private Int32 niceLength; // 0x54
	private Int32 goodLength; // 0x58
	private Int32 compressionFunction; // 0x5c
	private Byte[] inputBuf; // 0x60
	private Int64 totalIn; // 0x68
	private Int32 inputOff; // 0x70
	private Int32 inputEnd; // 0x74
	private DeflaterPending pending; // 0x78
	private DeflaterHuffman huffman; // 0x80
	private Adler32 adler; // 0x88

	public Int32 Adler { get; }
	public DeflateStrategy Strategy { set; }

	// RVA: 0x5ec76f4 VA: 0x75984df6f4
	public Void .ctor(DeflaterPending pending) { }
	// RVA: 0x5ec7f78 VA: 0x75984dff78
	public Boolean Deflate(Boolean flush, Boolean finish) { }
	// RVA: 0x5ec7a58 VA: 0x75984dfa58
	public Void SetInput(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ec7a2c VA: 0x75984dfa2c
	public Boolean NeedsInput() { }
	// RVA: 0x5ec796c VA: 0x75984df96c
	public Void Reset() { }
	// RVA: 0x5ec7e9c VA: 0x75984dfe9c
	public Void ResetAdler() { }
	// RVA: 0x5ec7e80 VA: 0x75984dfe80
	public Int32 get_Adler() { }
	// RVA: 0x5ec8c18 VA: 0x75984e0c18
	public Void set_Strategy(DeflateStrategy value) { }
	// RVA: 0x5ec7b94 VA: 0x75984dfb94
	public Void SetLevel(Int32 level) { }
	// RVA: 0x5ec84ec VA: 0x75984e04ec
	public Void FillWindow() { }
	// RVA: 0x5ec8cc4 VA: 0x75984e0cc4
	private Void UpdateHash() { }
	// RVA: 0x5ec91f0 VA: 0x75984e11f0
	private Int32 InsertString() { }
	// RVA: 0x5ec9130 VA: 0x75984e1130
	private Void SlideWindow() { }
	// RVA: 0x5ec927c VA: 0x75984e127c
	private Boolean FindLongestMatch(Int32 curMatch) { }
	// RVA: 0x5ec85c8 VA: 0x75984e05c8
	private Boolean DeflateStored(Boolean flush, Boolean finish) { }
	// RVA: 0x5ec8710 VA: 0x75984e0710
	private Boolean DeflateFast(Boolean flush, Boolean finish) { }
	// RVA: 0x5ec8944 VA: 0x75984e0944
	private Boolean DeflateSlow(Boolean flush, Boolean finish) { }
}
```