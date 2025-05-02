# NetDataReader

**Namespace:** `FlyingWormConsole3.LiteNetLib.Utils`


## Fields

- `Int32 _position`

- `Int32 _dataSize`

- `Int32 _offset`


## Properties

- `Int32 RawDataSize`

- `Int32 UserDataOffset`

- `Int32 UserDataSize`

- `Boolean IsNull`

- `Int32 Position`

- `Boolean EndOfData`

- `Int32 AvailableBytes`


## Methods

- `Int32 get_RawDataSize()`

- `Int32 get_UserDataOffset()`

- `Int32 get_UserDataSize()`

- `Boolean get_IsNull()`

- `Int32 get_Position()`

- `Boolean get_EndOfData()`

- `Int32 get_AvailableBytes()`

- `Void SkipBytes(Int32)`

- `Void SetSource(NetDataWriter)`

- `Void SetSource(Byte[])`

- `Void SetSource(Byte[], Int32)`

- `Void SetSource(Byte[], Int32, Int32)`

- `IPEndPoint GetNetEndPoint()`

- `Byte GetByte()`

- `SByte GetSByte()`

- `Boolean GetBool()`

- `Char GetChar()`

- `UInt16 GetUShort()`

- `Int16 GetShort()`

- `Int64 GetLong()`

- `UInt64 GetULong()`

- `Int32 GetInt()`

- `UInt32 GetUInt()`

- `Single GetFloat()`

- `Double GetDouble()`

- `String GetString(Int32)`

- `String GetString()`

- `T Get()`

- `Void GetBytes(Byte[], Int32, Int32)`

- `Void GetBytes(Byte[], Int32)`

- `Byte PeekByte()`

- `SByte PeekSByte()`

- `Boolean PeekBool()`

- `Char PeekChar()`

- `UInt16 PeekUShort()`

- `Int16 PeekShort()`

- `Int64 PeekLong()`

- `UInt64 PeekULong()`

- `Int32 PeekInt()`

- `UInt32 PeekUInt()`

- `Single PeekFloat()`

- `Double PeekDouble()`

- `String PeekString(Int32)`

- `String PeekString()`

- `Boolean TryGetByte(out)`

- `Boolean TryGetSByte(out)`

- `Boolean TryGetBool(out)`

- `Boolean TryGetChar(out)`

- `Boolean TryGetShort(out)`

- `Boolean TryGetUShort(out)`

- `Boolean TryGetInt(out)`

- `Boolean TryGetUInt(out)`

- `Boolean TryGetLong(out)`

- `Boolean TryGetULong(out)`

- `Boolean TryGetFloat(out)`

- `Boolean TryGetDouble(out)`

- `Boolean TryGetString(out)`

- `Boolean TryGetStringArray(out)`

- `Boolean TryGetBytesWithLength(out)`

- `Void Clear()`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Utils
public class NetDataReader
{
	protected Byte[] _data; // 0x10
	protected Int32 _position; // 0x18
	protected Int32 _dataSize; // 0x1c
	private Int32 _offset; // 0x20

	public Byte[] RawData { get; }
	public Int32 RawDataSize { get; }
	public Int32 UserDataOffset { get; }
	public Int32 UserDataSize { get; }
	public Boolean IsNull { get; }
	public Int32 Position { get; }
	public Boolean EndOfData { get; }
	public Int32 AvailableBytes { get; }

	// RVA: 0x4107700 VA: 0x759671f700
	public Byte[] get_RawData() { }
	// RVA: 0x4107708 VA: 0x759671f708
	public Int32 get_RawDataSize() { }
	// RVA: 0x4107710 VA: 0x759671f710
	public Int32 get_UserDataOffset() { }
	// RVA: 0x4107718 VA: 0x759671f718
	public Int32 get_UserDataSize() { }
	// RVA: 0x40fba94 VA: 0x7596713a94
	public Boolean get_IsNull() { }
	// RVA: 0x4107724 VA: 0x759671f724
	public Int32 get_Position() { }
	// RVA: 0x410772c VA: 0x759671f72c
	public Boolean get_EndOfData() { }
	// RVA: 0x410773c VA: 0x759671f73c
	public Int32 get_AvailableBytes() { }
	// RVA: 0x4107748 VA: 0x759671f748
	public Void SkipBytes(Int32 count) { }
	// RVA: 0x4107758 VA: 0x759671f758
	public Void SetSource(NetDataWriter dataWriter) { }
	// RVA: 0x410779c VA: 0x759671f79c
	public Void SetSource(Byte[] source) { }
	// RVA: 0x41077e0 VA: 0x759671f7e0
	public Void SetSource(Byte[] source, Int32 offset) { }
	// RVA: 0x40f8038 VA: 0x7596710038
	public Void SetSource(Byte[] source, Int32 offset, Int32 maxSize) { }
	// RVA: 0x40f7f04 VA: 0x759670ff04
	public Void .ctor() { }
	// RVA: 0x4107830 VA: 0x759671f830
	public Void .ctor(NetDataWriter writer) { }
	// RVA: 0x410785c VA: 0x759671f85c
	public Void .ctor(Byte[] source) { }
	// RVA: 0x4107888 VA: 0x759671f888
	public Void .ctor(Byte[] source, Int32 offset) { }
	// RVA: 0x41018e4 VA: 0x75967198e4
	public Void .ctor(Byte[] source, Int32 offset, Int32 maxSize) { }
	// RVA: 0x41078bc VA: 0x759671f8bc
	public IPEndPoint GetNetEndPoint() { }
	// RVA: 0x4107a8c VA: 0x759671fa8c
	public Byte GetByte() { }
	// RVA: 0x4107acc VA: 0x759671facc
	public SByte GetSByte() { }
	// RVA: 0x4107b0c VA: 0x759671fb0c
	public Boolean[] GetBoolArray() { }
	// RVA: 0x4107be8 VA: 0x759671fbe8
	public UInt16[] GetUShortArray() { }
	// RVA: 0x4107cc0 VA: 0x759671fcc0
	public Int16[] GetShortArray() { }
	// RVA: 0x4107d98 VA: 0x759671fd98
	public Int64[] GetLongArray() { }
	// RVA: 0x4107e70 VA: 0x759671fe70
	public UInt64[] GetULongArray() { }
	// RVA: 0x4107f48 VA: 0x759671ff48
	public Int32[] GetIntArray() { }
	// RVA: 0x4108020 VA: 0x7596720020
	public UInt32[] GetUIntArray() { }
	// RVA: 0x41080f8 VA: 0x75967200f8
	public Single[] GetFloatArray() { }
	// RVA: 0x41081d0 VA: 0x75967201d0
	public Double[] GetDoubleArray() { }
	// RVA: 0x41082a8 VA: 0x75967202a8
	public String[] GetStringArray() { }
	// RVA: 0x41083dc VA: 0x75967203dc
	public String[] GetStringArray(Int32 maxStringLength) { }
	// RVA: 0x4108520 VA: 0x7596720520
	public Boolean GetBool() { }
	// RVA: 0x4108568 VA: 0x7596720568
	public Char GetChar() { }
	// RVA: 0x41085dc VA: 0x75967205dc
	public UInt16 GetUShort() { }
	// RVA: 0x4108650 VA: 0x7596720650
	public Int16 GetShort() { }
	// RVA: 0x41086c4 VA: 0x75967206c4
	public Int64 GetLong() { }
	// RVA: 0x4108738 VA: 0x7596720738
	public UInt64 GetULong() { }
	// RVA: 0x4107a18 VA: 0x759671fa18
	public Int32 GetInt() { }
	// RVA: 0x41087ac VA: 0x75967207ac
	public UInt32 GetUInt() { }
	// RVA: 0x4108820 VA: 0x7596720820
	public Single GetFloat() { }
	// RVA: 0x4108894 VA: 0x7596720894
	public Double GetDouble() { }
	// RVA: 0x4107934 VA: 0x759671f934
	public String GetString(Int32 maxLength) { }
	// RVA: 0x40f52dc VA: 0x759670d2dc
	public String GetString() { }
	// RVA: 0x4108908 VA: 0x7596720908
	public ArraySegment`1 GetRemainingBytesSegment() { }
	// RVA: 0x VA: 0x0
	public T Get() { }
	// RVA: 0x4108984 VA: 0x7596720984
	public Byte[] GetRemainingBytes() { }
	// RVA: 0x4108a0c VA: 0x7596720a0c
	public Void GetBytes(Byte[] destination, Int32 start, Int32 count) { }
	// RVA: 0x4108a54 VA: 0x7596720a54
	public Void GetBytes(Byte[] destination, Int32 count) { }
	// RVA: 0x4108a9c VA: 0x7596720a9c
	public SByte[] GetSBytesWithLength() { }
	// RVA: 0x4108b2c VA: 0x7596720b2c
	public Byte[] GetBytesWithLength() { }
	// RVA: 0x4108bbc VA: 0x7596720bbc
	public Byte PeekByte() { }
	// RVA: 0x4108bf0 VA: 0x7596720bf0
	public SByte PeekSByte() { }
	// RVA: 0x4108c24 VA: 0x7596720c24
	public Boolean PeekBool() { }
	// RVA: 0x4108c60 VA: 0x7596720c60
	public Char PeekChar() { }
	// RVA: 0x4108cc4 VA: 0x7596720cc4
	public UInt16 PeekUShort() { }
	// RVA: 0x4108d28 VA: 0x7596720d28
	public Int16 PeekShort() { }
	// RVA: 0x4108d8c VA: 0x7596720d8c
	public Int64 PeekLong() { }
	// RVA: 0x4108df0 VA: 0x7596720df0
	public UInt64 PeekULong() { }
	// RVA: 0x4108e54 VA: 0x7596720e54
	public Int32 PeekInt() { }
	// RVA: 0x4108eb8 VA: 0x7596720eb8
	public UInt32 PeekUInt() { }
	// RVA: 0x4108f1c VA: 0x7596720f1c
	public Single PeekFloat() { }
	// RVA: 0x4108f80 VA: 0x7596720f80
	public Double PeekDouble() { }
	// RVA: 0x4108fe4 VA: 0x7596720fe4
	public String PeekString(Int32 maxLength) { }
	// RVA: 0x4109100 VA: 0x7596721100
	public String PeekString() { }
	// RVA: 0x41091cc VA: 0x75967211cc
	public Boolean TryGetByte(out Byte result) { }
	// RVA: 0x4109208 VA: 0x7596721208
	public Boolean TryGetSByte(out SByte result) { }
	// RVA: 0x4109244 VA: 0x7596721244
	public Boolean TryGetBool(out Boolean result) { }
	// RVA: 0x4109280 VA: 0x7596721280
	public Boolean TryGetChar(out Char result) { }
	// RVA: 0x41092bc VA: 0x75967212bc
	public Boolean TryGetShort(out Int16 result) { }
	// RVA: 0x41092f8 VA: 0x75967212f8
	public Boolean TryGetUShort(out UInt16 result) { }
	// RVA: 0x4109334 VA: 0x7596721334
	public Boolean TryGetInt(out Int32 result) { }
	// RVA: 0x4109370 VA: 0x7596721370
	public Boolean TryGetUInt(out UInt32 result) { }
	// RVA: 0x41093ac VA: 0x75967213ac
	public Boolean TryGetLong(out Int64 result) { }
	// RVA: 0x41093e8 VA: 0x75967213e8
	public Boolean TryGetULong(out UInt64 result) { }
	// RVA: 0x4109424 VA: 0x7596721424
	public Boolean TryGetFloat(out Single result) { }
	// RVA: 0x410945c VA: 0x759672145c
	public Boolean TryGetDouble(out Double result) { }
	// RVA: 0x4109494 VA: 0x7596721494
	public Boolean TryGetString(out String result) { }
	// RVA: 0x410950c VA: 0x759672150c
	public Boolean TryGetStringArray(out String[] result) { }
	// RVA: 0x4109600 VA: 0x7596721600
	public Boolean TryGetBytesWithLength(out Byte[] result) { }
	// RVA: 0x40f982c VA: 0x759671182c
	public Void Clear() { }
}
```