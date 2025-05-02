# DeflaterHuffman

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `DeflaterPending pending`

- `Tree literalTree`

- `Tree distTree`

- `Tree blTree`

- `Int32 last_lit`

- `Int32 extra_bits`


## Methods

- `Void Reset()`

- `Void SendAllTrees(Int32)`

- `Void CompressBlock()`

- `Void FlushStoredBlock(Byte[], Int32, Int32, Boolean)`

- `Void FlushBlock(Byte[], Int32, Int32, Boolean)`

- `Boolean IsFull()`

- `Boolean TallyLit(Int32)`

- `Boolean TallyDist(Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class DeflaterHuffman
{
	private static readonly Int32[] BL_ORDER; // 0x0
	private static readonly Byte[] bit4Reverse; // 0x8
	private static Int16[] staticLCodes; // 0x10
	private static Byte[] staticLLength; // 0x18
	private static Int16[] staticDCodes; // 0x20
	private static Byte[] staticDLength; // 0x28
	public DeflaterPending pending; // 0x10
	private Tree literalTree; // 0x18
	private Tree distTree; // 0x20
	private Tree blTree; // 0x28
	private Int16[] d_buf; // 0x30
	private Byte[] l_buf; // 0x38
	private Int32 last_lit; // 0x40
	private Int32 extra_bits; // 0x44


	// RVA: 0x5ec989c VA: 0x75984e189c
	private static Void .cctor() { }
	// RVA: 0x5ec8388 VA: 0x75984e0388
	public Void .ctor(DeflaterPending pending) { }
	// RVA: 0x5ec8be0 VA: 0x75984e0be0
	public Void Reset() { }
	// RVA: 0x5ec9e80 VA: 0x75984e1e80
	public Void SendAllTrees(Int32 blTreeCodes) { }
	// RVA: 0x5eca39c VA: 0x75984e239c
	public Void CompressBlock() { }
	// RVA: 0x5ec8c20 VA: 0x75984e0c20
	public Void FlushStoredBlock(Byte[] stored, Int32 storedOffset, Int32 storedLength, Boolean lastBlock) { }
	// RVA: 0x5ec8d10 VA: 0x75984e0d10
	public Void FlushBlock(Byte[] stored, Int32 storedOffset, Int32 storedLength, Boolean lastBlock) { }
	// RVA: 0x5ec988c VA: 0x75984e188c
	public Boolean IsFull() { }
	// RVA: 0x5ec909c VA: 0x75984e109c
	public Boolean TallyLit(Int32 literal) { }
	// RVA: 0x5ec96b4 VA: 0x75984e16b4
	public Boolean TallyDist(Int32 distance, Int32 length) { }
	// RVA: 0x5ec9c74 VA: 0x75984e1c74
	public static Int16 BitReverse(Int32 toReverse) { }
	// RVA: 0x5eca58c VA: 0x75984e258c
	private static Int32 Lcode(Int32 length) { }
	// RVA: 0x5eca628 VA: 0x75984e2628
	private static Int32 Dcode(Int32 distance) { }
}
```