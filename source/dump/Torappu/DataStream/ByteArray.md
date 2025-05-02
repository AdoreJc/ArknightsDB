# ByteArray

**Namespace:** `Torappu.DataStream`


## Fields

- `Int32 m_inc`

- `Int32 m_pos`

- `Int32 m_size`


## Properties

- `Boolean isLittleEndian`

- `Int32 position`

- `Int32 size`

- `Int32 capacity`

- `Int32 residualCapacity`

- `Int32 bytesAvailable`


## Methods

- `Void Clear()`

- `Void RemoveFront(Int32)`

- `Boolean get_isLittleEndian()`

- `Void set_isLittleEndian(Boolean)`

- `Int32 get_position()`

- `Void set_position(Int32)`

- `Int32 get_size()`

- `Void set_size(Int32)`

- `Int32 get_capacity()`

- `Int32 get_residualCapacity()`

- `Int32 get_bytesAvailable()`

- `Boolean ReadBool()`

- `SByte ReadSByte()`

- `Byte ReadByte()`

- `Int16 ReadInt16()`

- `UInt16 ReadUint16()`

- `Int32 ReadInt32()`

- `UInt32 ReadUint32()`

- `Int64 ReadInt64()`

- `UInt64 ReadUint64()`

- `String ReadString()`

- `String ReadString2()`

- `String _ReadString(Int32)`

- `Int32 ReadBytes(Byte[], Int32, Int32)`

- `Void _CheckAvaliable(Int32)`

- `Void WriteBool(Boolean)`

- `Void WriteSByte(SByte)`

- `Void WriteByte(Byte)`

- `Void WriteInt16(Int16)`

- `Void WriteUint16(UInt16)`

- `Void WriteInt32(Int32)`

- `Void WriteUint32(UInt32)`

- `Void WriteInt64(Int64)`

- `Void WriteUint64(UInt64)`

- `Int32 WriteBytes(Byte[], Int32, Int32)`

- `Void WriteString(String)`

- `Void WriteString2(String)`

- `Int32 WriteBytes(ByteArray, Int32, Int32)`

- `Void _AdjustCapacity(Int32)`

- `Int32 _CalculateInitialOffset(Int32)`

- `Int32 _Offset(ref)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataStream
public class ByteArray : IReusable, IStreamReader, IHotfixable, IStreamWriter
{
	private static readonly Encoding ENCODING; // 0x0
	private Int32 m_inc; // 0x10
	private Byte[] m_buffer; // 0x18
	private Int32 m_pos; // 0x20
	private Int32 m_size; // 0x24
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge _c__Hotfix1_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Clear; // 0x18
	private static DelegateBridge __Hotfix0_RemoveFront; // 0x20
	private static DelegateBridge __Hotfix0_get_isLittleEndian; // 0x28
	private static DelegateBridge __Hotfix0_set_isLittleEndian; // 0x30
	private static DelegateBridge __Hotfix0_get_bytes; // 0x38
	private static DelegateBridge __Hotfix0_get_position; // 0x40
	private static DelegateBridge __Hotfix0_set_position; // 0x48
	private static DelegateBridge __Hotfix0_get_size; // 0x50
	private static DelegateBridge __Hotfix0_set_size; // 0x58
	private static DelegateBridge __Hotfix0_get_capacity; // 0x60
	private static DelegateBridge __Hotfix0_get_residualCapacity; // 0x68
	private static DelegateBridge __Hotfix0_get_bytesAvailable; // 0x70
	private static DelegateBridge __Hotfix0_ReadBool; // 0x78
	private static DelegateBridge __Hotfix0_ReadSByte; // 0x80
	private static DelegateBridge __Hotfix0_ReadByte; // 0x88
	private static DelegateBridge __Hotfix0_ReadInt16; // 0x90
	private static DelegateBridge __Hotfix0_ReadUint16; // 0x98
	private static DelegateBridge __Hotfix0_ReadInt32; // 0xa0
	private static DelegateBridge __Hotfix0_ReadUint32; // 0xa8
	private static DelegateBridge __Hotfix0_ReadInt64; // 0xb0
	private static DelegateBridge __Hotfix0_ReadUint64; // 0xb8
	private static DelegateBridge __Hotfix0_ReadString; // 0xc0
	private static DelegateBridge __Hotfix0_ReadString2; // 0xc8
	private static DelegateBridge __Hotfix0__ReadString; // 0xd0
	private static DelegateBridge __Hotfix0_ReadBytes; // 0xd8
	private static DelegateBridge __Hotfix0__CheckAvaliable; // 0xe0
	private static DelegateBridge __Hotfix0_WriteBool; // 0xe8
	private static DelegateBridge __Hotfix0_WriteSByte; // 0xf0
	private static DelegateBridge __Hotfix0_WriteByte; // 0xf8
	private static DelegateBridge __Hotfix0_WriteInt16; // 0x100
	private static DelegateBridge __Hotfix0_WriteUint16; // 0x108
	private static DelegateBridge __Hotfix0_WriteInt32; // 0x110
	private static DelegateBridge __Hotfix0_WriteUint32; // 0x118
	private static DelegateBridge __Hotfix0_WriteInt64; // 0x120
	private static DelegateBridge __Hotfix0_WriteUint64; // 0x128
	private static DelegateBridge __Hotfix0_WriteBytes; // 0x130
	private static DelegateBridge __Hotfix0_WriteString; // 0x138
	private static DelegateBridge __Hotfix0_WriteString2; // 0x140
	private static DelegateBridge __Hotfix1_WriteBytes; // 0x148
	private static DelegateBridge __Hotfix0__AdjustCapacity; // 0x150
	private static DelegateBridge __Hotfix0__CalculateInitialOffset; // 0x158
	private static DelegateBridge __Hotfix0__Offset; // 0x160
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x168
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x170

	private Boolean isLittleEndian { get; set; }
	public Byte[] bytes { get; }
	public Int32 position { get; set; }
	public Int32 size { get; set; }
	public Int32 capacity { get; }
	public Int32 residualCapacity { get; }
	public Int32 bytesAvailable { get; }

	// RVA: 0x371f4cc VA: 0x7595d374cc
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x371f564 VA: 0x7595d37564
	private Void .ctor(Int32 capacity, Boolean littleEndian) { }
	// RVA: 0x371f6f0 VA: 0x7595d376f0
	public Void Clear() { }
	// RVA: 0x371f768 VA: 0x7595d37768
	public Void RemoveFront(Int32 len) { }
	// RVA: 0x371f83c VA: 0x7595d3783c
	private Boolean get_isLittleEndian() { }
	// RVA: 0x371f650 VA: 0x7595d37650
	private Void set_isLittleEndian(Boolean value) { }
	// RVA: 0x371f8bc VA: 0x7595d378bc
	public Byte[] get_bytes() { }
	// RVA: 0x371f934 VA: 0x7595d37934
	public Int32 get_position() { }
	// RVA: 0x371f9ac VA: 0x7595d379ac
	public Void set_position(Int32 value) { }
	// RVA: 0x371fa48 VA: 0x7595d37a48
	public Int32 get_size() { }
	// RVA: 0x371fac0 VA: 0x7595d37ac0
	public Void set_size(Int32 value) { }
	// RVA: 0x371fca0 VA: 0x7595d37ca0
	public Int32 get_capacity() { }
	// RVA: 0x371fd24 VA: 0x7595d37d24
	public Int32 get_residualCapacity() { }
	// RVA: 0x371fdb0 VA: 0x7595d37db0
	public Int32 get_bytesAvailable() { }
	// RVA: 0x371fe2c VA: 0x7595d37e2c
	public Boolean ReadBool() { }
	// RVA: 0x371ff60 VA: 0x7595d37f60
	public SByte ReadSByte() { }
	// RVA: 0x371feb0 VA: 0x7595d37eb0
	public Byte ReadByte() { }
	// RVA: 0x37200bc VA: 0x7595d380bc
	public Int16 ReadInt16() { }
	// RVA: 0x3720310 VA: 0x7595d38310
	public UInt16 ReadUint16() { }
	// RVA: 0x3720428 VA: 0x7595d38428
	public Int32 ReadInt32() { }
	// RVA: 0x37205d0 VA: 0x7595d385d0
	public UInt32 ReadUint32() { }
	// RVA: 0x3720778 VA: 0x7595d38778
	public Int64 ReadInt64() { }
	// RVA: 0x3720a54 VA: 0x7595d38a54
	public UInt64 ReadUint64() { }
	// RVA: 0x3720d30 VA: 0x7595d38d30
	public String ReadString() { }
	// RVA: 0x3720e94 VA: 0x7595d38e94
	public String ReadString2() { }
	// RVA: 0x3720db4 VA: 0x7595d38db4
	public String _ReadString(Int32 len) { }
	// RVA: 0x3720f18 VA: 0x7595d38f18
	public Int32 ReadBytes(Byte[] dest, Int32 offset, Int32 len) { }
	// RVA: 0x371ffd8 VA: 0x7595d37fd8
	private Void _CheckAvaliable(Int32 bytesToRead) { }
	// RVA: 0x3721008 VA: 0x7595d39008
	public Void WriteBool(Boolean v) { }
	// RVA: 0x37211a4 VA: 0x7595d391a4
	public Void WriteSByte(SByte v) { }
	// RVA: 0x37210a0 VA: 0x7595d390a0
	public Void WriteByte(Byte v) { }
	// RVA: 0x3721234 VA: 0x7595d39234
	public Void WriteInt16(Int16 v) { }
	// RVA: 0x3721390 VA: 0x7595d39390
	public Void WriteUint16(UInt16 v) { }
	// RVA: 0x37214ec VA: 0x7595d394ec
	public Void WriteInt32(Int32 v) { }
	// RVA: 0x37216b4 VA: 0x7595d396b4
	public Void WriteUint32(UInt32 v) { }
	// RVA: 0x372187c VA: 0x7595d3987c
	public Void WriteInt64(Int64 v) { }
	// RVA: 0x3721b24 VA: 0x7595d39b24
	public Void WriteUint64(UInt64 v) { }
	// RVA: 0x3721dcc VA: 0x7595d39dcc
	public Int32 WriteBytes(Byte[] src, Int32 offset, Int32 len) { }
	// RVA: 0x3721efc VA: 0x7595d39efc
	public Void WriteString(String v) { }
	// RVA: 0x37220d0 VA: 0x7595d3a0d0
	public Void WriteString2(String v) { }
	// RVA: 0x37222a4 VA: 0x7595d3a2a4
	public Int32 WriteBytes(ByteArray src, Int32 offset, Int32 len) { }
	// RVA: 0x371fb70 VA: 0x7595d37b70
	private Void _AdjustCapacity(Int32 size) { }
	// RVA: 0x37201d4 VA: 0x7595d381d4
	private Int32 _CalculateInitialOffset(Int32 cntOfByte) { }
	// RVA: 0x3720278 VA: 0x7595d38278
	private Int32 _Offset(ref Int32 offset) { }
	// RVA: 0x37223e0 VA: 0x7595d3a3e0
	public Void OnAllocate() { }
	// RVA: 0x3722454 VA: 0x7595d3a454
	public Void OnRecycle() { }
	// RVA: 0x37224cc VA: 0x7595d3a4cc
	private static Void .cctor() { }
}
```