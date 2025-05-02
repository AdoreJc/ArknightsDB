# CRC32

**Namespace:** `BestHTTP.Decompression.Crc`


## Fields

- `UInt32 dwPolynomial`

- `Int64 _TotalBytesRead`

- `Boolean reverseBits`

- `UInt32 _register`


## Properties

- `Int64 TotalBytesRead`

- `Int32 Crc32Result`


## Methods

- `Int64 get_TotalBytesRead()`

- `Int32 get_Crc32Result()`

- `Int32 GetCrc32(Stream)`

- `Int32 GetCrc32AndCopy(Stream, Stream)`

- `Int32 ComputeCrc32(Int32, Byte)`

- `Void SlurpBlock(Byte[], Int32, Int32)`

- `Void UpdateCRC(Byte)`

- `Void UpdateCRC(Byte, Int32)`

- `Void GenerateLookupTable()`

- `UInt32 gf2_matrix_times(UInt32[], UInt32)`

- `Void gf2_matrix_square(UInt32[], UInt32[])`

- `Void Combine(Int32, Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Decompression.Crc
internal class CRC32
{
	private UInt32 dwPolynomial; // 0x10
	private Int64 _TotalBytesRead; // 0x18
	private Boolean reverseBits; // 0x20
	private UInt32[] crc32Table; // 0x28
	private const Int32 BUFFER_SIZE; // 0x0
	private UInt32 _register; // 0x30

	public Int64 TotalBytesRead { get; }
	public Int32 Crc32Result { get; }

	// RVA: 0x662fa28 VA: 0x7598c47a28
	public Int64 get_TotalBytesRead() { }
	// RVA: 0x662bfec VA: 0x7598c43fec
	public Int32 get_Crc32Result() { }
	// RVA: 0x662fa30 VA: 0x7598c47a30
	public Int32 GetCrc32(Stream input) { }
	// RVA: 0x662fa38 VA: 0x7598c47a38
	public Int32 GetCrc32AndCopy(Stream input, Stream output) { }
	// RVA: 0x662fbc0 VA: 0x7598c47bc0
	public Int32 ComputeCrc32(Int32 W, Byte B) { }
	// RVA: 0x662fbc4 VA: 0x7598c47bc4
	internal Int32 _InternalComputeCrc32(UInt32 W, Byte B) { }
	// RVA: 0x662c690 VA: 0x7598c44690
	public Void SlurpBlock(Byte[] block, Int32 offset, Int32 count) { }
	// RVA: 0x662fc00 VA: 0x7598c47c00
	public Void UpdateCRC(Byte b) { }
	// RVA: 0x662fc78 VA: 0x7598c47c78
	public Void UpdateCRC(Byte b, Int32 n) { }
	// RVA: 0x662fd04 VA: 0x7598c47d04
	private static UInt32 ReverseBits(UInt32 data) { }
	// RVA: 0x662fd0c VA: 0x7598c47d0c
	private static Byte ReverseBits(Byte data) { }
	// RVA: 0x662fd58 VA: 0x7598c47d58
	private Void GenerateLookupTable() { }
	// RVA: 0x662fe94 VA: 0x7598c47e94
	private UInt32 gf2_matrix_times(UInt32[] matrix, UInt32 vec) { }
	// RVA: 0x662fee8 VA: 0x7598c47ee8
	private Void gf2_matrix_square(UInt32[] square, UInt32[] mat) { }
	// RVA: 0x662ff5c VA: 0x7598c47f5c
	public Void Combine(Int32 crc, Int32 length) { }
	// RVA: 0x662c180 VA: 0x7598c44180
	public Void .ctor() { }
	// RVA: 0x66300a4 VA: 0x7598c480a4
	public Void .ctor(Boolean reverseBits) { }
	// RVA: 0x66300e4 VA: 0x7598c480e4
	public Void .ctor(Int32 polynomial, Boolean reverseBits) { }
	// RVA: 0x6630120 VA: 0x7598c48120
	public Void Reset() { }
}
```