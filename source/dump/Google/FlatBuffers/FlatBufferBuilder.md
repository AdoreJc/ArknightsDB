# FlatBufferBuilder

**Namespace:** `Google.FlatBuffers`


## Fields

- `Int32 _space`

- `ByteBuffer _bb`

- `Int32 _minAlign`

- `Int32 _vtableSize`

- `Int32 _objectStart`

- `Int32 _numVtables`

- `Int32 _vectorNumElems`

- `Boolean <ForceDefaults>k__BackingField`


## Properties

- `Boolean ForceDefaults`

- `Int32 Offset`

- `ByteBuffer DataBuffer`


## Methods

- `Void Clear()`

- `Boolean get_ForceDefaults()`

- `Void set_ForceDefaults(Boolean)`

- `Int32 get_Offset()`

- `Void Pad(Int32)`

- `Void GrowBuffer()`

- `Void Prep(Int32, Int32)`

- `Void PutBool(Boolean)`

- `Void PutSbyte(SByte)`

- `Void PutByte(Byte)`

- `Void PutShort(Int16)`

- `Void PutUshort(UInt16)`

- `Void PutInt(Int32)`

- `Void PutUint(UInt32)`

- `Void PutLong(Int64)`

- `Void PutUlong(UInt64)`

- `Void PutFloat(Single)`

- `Void Put(T[])`

- `Void Put(ArraySegment`1)`

- `Void Put(IntPtr, Int32)`

- `Void PutDouble(Double)`

- `Void AddBool(Boolean)`

- `Void AddSbyte(SByte)`

- `Void AddByte(Byte)`

- `Void AddShort(Int16)`

- `Void AddUshort(UInt16)`

- `Void AddInt(Int32)`

- `Void AddUint(UInt32)`

- `Void AddLong(Int64)`

- `Void AddUlong(UInt64)`

- `Void AddFloat(Single)`

- `Void Add(T[])`

- `Void Add(ArraySegment`1)`

- `Void Add(IntPtr, Int32)`

- `Void AddDouble(Double)`

- `Void AddOffset(Int32)`

- `Void StartVector(Int32, Int32, Int32)`

- `VectorOffset EndVector()`

- `VectorOffset CreateVectorOfTables(Offset`1[])`

- `Void Nested(Int32)`

- `Void NotNested()`

- `Void StartTable(Int32)`

- `Void Slot(Int32)`

- `Void AddBool(Int32, Boolean, Boolean)`

- `Void AddBool(Int32, Nullable`1)`

- `Void AddSbyte(Int32, SByte, SByte)`

- `Void AddSbyte(Int32, Nullable`1)`

- `Void AddByte(Int32, Byte, Byte)`

- `Void AddByte(Int32, Nullable`1)`

- `Void AddShort(Int32, Int16, Int32)`

- `Void AddShort(Int32, Nullable`1)`

- `Void AddUshort(Int32, UInt16, UInt16)`

- `Void AddUshort(Int32, Nullable`1)`

- `Void AddInt(Int32, Int32, Int32)`

- `Void AddInt(Int32, Nullable`1)`

- `Void AddUint(Int32, UInt32, UInt32)`

- `Void AddUint(Int32, Nullable`1)`

- `Void AddLong(Int32, Int64, Int64)`

- `Void AddLong(Int32, Nullable`1)`

- `Void AddUlong(Int32, UInt64, UInt64)`

- `Void AddUlong(Int32, Nullable`1)`

- `Void AddFloat(Int32, Single, Double)`

- `Void AddFloat(Int32, Nullable`1)`

- `Void AddDouble(Int32, Double, Double)`

- `Void AddDouble(Int32, Nullable`1)`

- `Void AddOffset(Int32, Int32, Int32)`

- `StringOffset CreateString(String)`

- `StringOffset CreateSharedString(String)`

- `Void AddStruct(Int32, Int32, Int32)`

- `Int32 EndTable()`

- `Void Required(Int32, Int32)`

- `Void Finish(Int32, Boolean)`

- `Void Finish(Int32)`

- `Void FinishSizePrefixed(Int32)`

- `ByteBuffer get_DataBuffer()`

- `Void Finish(Int32, String, Boolean)`

- `Void Finish(Int32, String)`

- `Void FinishSizePrefixed(Int32, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Google.FlatBuffers
public class FlatBufferBuilder
{
	private Int32 _space; // 0x10
	private ByteBuffer _bb; // 0x18
	private Int32 _minAlign; // 0x20
	private Int32[] _vtable; // 0x28
	private Int32 _vtableSize; // 0x30
	private Int32 _objectStart; // 0x34
	private Int32[] _vtables; // 0x38
	private Int32 _numVtables; // 0x40
	private Int32 _vectorNumElems; // 0x44
	private Dictionary`2 _sharedStringMap; // 0x48
	private Boolean <ForceDefaults>k__BackingField; // 0x50

	public Boolean ForceDefaults { get; set; }
	public Int32 Offset { get; }
	public ByteBuffer DataBuffer { get; }

	// RVA: 0x66c77d4 VA: 0x7598cdf7d4
	public Void .ctor(Int32 initialSize) { }
	// RVA: 0x66c793c VA: 0x7598cdf93c
	public Void .ctor(ByteBuffer buffer) { }
	// RVA: 0x66c7a08 VA: 0x7598cdfa08
	public Void Clear() { }
	// RVA: 0x66c7ad8 VA: 0x7598cdfad8
	public Boolean get_ForceDefaults() { }
	// RVA: 0x66c7ae0 VA: 0x7598cdfae0
	public Void set_ForceDefaults(Boolean value) { }
	// RVA: 0x66c7aec VA: 0x7598cdfaec
	public Int32 get_Offset() { }
	// RVA: 0x66c7b18 VA: 0x7598cdfb18
	public Void Pad(Int32 size) { }
	// RVA: 0x66c7b48 VA: 0x7598cdfb48
	private Void GrowBuffer() { }
	// RVA: 0x66c7b78 VA: 0x7598cdfb78
	public Void Prep(Int32 size, Int32 additionalBytes) { }
	// RVA: 0x66c7c40 VA: 0x7598cdfc40
	public Void PutBool(Boolean x) { }
	// RVA: 0x66c7c70 VA: 0x7598cdfc70
	public Void PutSbyte(SByte x) { }
	// RVA: 0x66c7c9c VA: 0x7598cdfc9c
	public Void PutByte(Byte x) { }
	// RVA: 0x66c7cc8 VA: 0x7598cdfcc8
	public Void PutShort(Int16 x) { }
	// RVA: 0x66c7d18 VA: 0x7598cdfd18
	public Void PutUshort(UInt16 x) { }
	// RVA: 0x66c7d68 VA: 0x7598cdfd68
	public Void PutInt(Int32 x) { }
	// RVA: 0x66c7db8 VA: 0x7598cdfdb8
	public Void PutUint(UInt32 x) { }
	// RVA: 0x66c7e08 VA: 0x7598cdfe08
	public Void PutLong(Int64 x) { }
	// RVA: 0x66c7e58 VA: 0x7598cdfe58
	public Void PutUlong(UInt64 x) { }
	// RVA: 0x66c7ea8 VA: 0x7598cdfea8
	public Void PutFloat(Single x) { }
	// RVA: 0x VA: 0x0
	public Void Put(T[] x) { }
	// RVA: 0x VA: 0x0
	public Void Put(ArraySegment`1 x) { }
	// RVA: 0x VA: 0x0
	public Void Put(IntPtr ptr, Int32 sizeInBytes) { }
	// RVA: 0x66c7f04 VA: 0x7598cdff04
	public Void PutDouble(Double x) { }
	// RVA: 0x66c7f2c VA: 0x7598cdff2c
	public Void AddBool(Boolean x) { }
	// RVA: 0x66c7f5c VA: 0x7598cdff5c
	public Void AddSbyte(SByte x) { }
	// RVA: 0x66c7f8c VA: 0x7598cdff8c
	public Void AddByte(Byte x) { }
	// RVA: 0x66c7fbc VA: 0x7598cdffbc
	public Void AddShort(Int16 x) { }
	// RVA: 0x66c7fec VA: 0x7598cdffec
	public Void AddUshort(UInt16 x) { }
	// RVA: 0x66c801c VA: 0x7598ce001c
	public Void AddInt(Int32 x) { }
	// RVA: 0x66c804c VA: 0x7598ce004c
	public Void AddUint(UInt32 x) { }
	// RVA: 0x66c807c VA: 0x7598ce007c
	public Void AddLong(Int64 x) { }
	// RVA: 0x66c80ac VA: 0x7598ce00ac
	public Void AddUlong(UInt64 x) { }
	// RVA: 0x66c80dc VA: 0x7598ce00dc
	public Void AddFloat(Single x) { }
	// RVA: 0x VA: 0x0
	public Void Add(T[] x) { }
	// RVA: 0x VA: 0x0
	public Void Add(ArraySegment`1 x) { }
	// RVA: 0x VA: 0x0
	public Void Add(IntPtr ptr, Int32 sizeInBytes) { }
	// RVA: 0x66c810c VA: 0x7598ce010c
	public Void AddDouble(Double x) { }
	// RVA: 0x66c813c VA: 0x7598ce013c
	public Void AddOffset(Int32 off) { }
	// RVA: 0x66c81d0 VA: 0x7598ce01d0
	public Void StartVector(Int32 elemSize, Int32 count, Int32 alignment) { }
	// RVA: 0x66c8284 VA: 0x7598ce0284
	public VectorOffset EndVector() { }
	// RVA: 0x VA: 0x0
	public VectorOffset CreateVectorOfTables(Offset`1[] offsets) { }
	// RVA: 0x66c82a8 VA: 0x7598ce02a8
	public Void Nested(Int32 obj) { }
	// RVA: 0x66c8224 VA: 0x7598ce0224
	public Void NotNested() { }
	// RVA: 0x66c8310 VA: 0x7598ce0310
	public Void StartTable(Int32 numfields) { }
	// RVA: 0x66c83f4 VA: 0x7598ce03f4
	public Void Slot(Int32 voffset) { }
	// RVA: 0x66c848c VA: 0x7598ce048c
	public Void AddBool(Int32 o, Boolean x, Boolean d) { }
	// RVA: 0x66c84ec VA: 0x7598ce04ec
	public Void AddBool(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c858c VA: 0x7598ce058c
	public Void AddSbyte(Int32 o, SByte x, SByte d) { }
	// RVA: 0x66c85f0 VA: 0x7598ce05f0
	public Void AddSbyte(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8690 VA: 0x7598ce0690
	public Void AddByte(Int32 o, Byte x, Byte d) { }
	// RVA: 0x66c86f4 VA: 0x7598ce06f4
	public Void AddByte(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8794 VA: 0x7598ce0794
	public Void AddShort(Int32 o, Int16 x, Int32 d) { }
	// RVA: 0x66c87f4 VA: 0x7598ce07f4
	public Void AddShort(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8894 VA: 0x7598ce0894
	public Void AddUshort(Int32 o, UInt16 x, UInt16 d) { }
	// RVA: 0x66c88f8 VA: 0x7598ce08f8
	public Void AddUshort(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8998 VA: 0x7598ce0998
	public Void AddInt(Int32 o, Int32 x, Int32 d) { }
	// RVA: 0x66c89f8 VA: 0x7598ce09f8
	public Void AddInt(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8a98 VA: 0x7598ce0a98
	public Void AddUint(Int32 o, UInt32 x, UInt32 d) { }
	// RVA: 0x66c8af8 VA: 0x7598ce0af8
	public Void AddUint(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8b98 VA: 0x7598ce0b98
	public Void AddLong(Int32 o, Int64 x, Int64 d) { }
	// RVA: 0x66c8bf8 VA: 0x7598ce0bf8
	public Void AddLong(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8ca0 VA: 0x7598ce0ca0
	public Void AddUlong(Int32 o, UInt64 x, UInt64 d) { }
	// RVA: 0x66c8d00 VA: 0x7598ce0d00
	public Void AddUlong(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8da8 VA: 0x7598ce0da8
	public Void AddFloat(Int32 o, Single x, Double d) { }
	// RVA: 0x66c8e18 VA: 0x7598ce0e18
	public Void AddFloat(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8ec8 VA: 0x7598ce0ec8
	public Void AddDouble(Int32 o, Double x, Double d) { }
	// RVA: 0x66c8f34 VA: 0x7598ce0f34
	public Void AddDouble(Int32 o, Nullable`1 x) { }
	// RVA: 0x66c8fe4 VA: 0x7598ce0fe4
	public Void AddOffset(Int32 o, Int32 x, Int32 d) { }
	// RVA: 0x66c901c VA: 0x7598ce101c
	public StringOffset CreateString(String s) { }
	// RVA: 0x66c90d0 VA: 0x7598ce10d0
	public StringOffset CreateSharedString(String s) { }
	// RVA: 0x66c9214 VA: 0x7598ce1214
	public Void AddStruct(Int32 voffset, Int32 x, Int32 d) { }
	// RVA: 0x66c924c VA: 0x7598ce124c
	public Int32 EndTable() { }
	// RVA: 0x66c9614 VA: 0x7598ce1614
	public Void Required(Int32 table, Int32 field) { }
	// RVA: 0x66c970c VA: 0x7598ce170c
	protected Void Finish(Int32 rootTable, Boolean sizePrefix) { }
	// RVA: 0x66c97a4 VA: 0x7598ce17a4
	public Void Finish(Int32 rootTable) { }
	// RVA: 0x66c97ac VA: 0x7598ce17ac
	public Void FinishSizePrefixed(Int32 rootTable) { }
	// RVA: 0x66c97b4 VA: 0x7598ce17b4
	public ByteBuffer get_DataBuffer() { }
	// RVA: 0x66c97bc VA: 0x7598ce17bc
	public Byte[] SizedByteArray() { }
	// RVA: 0x66c97d4 VA: 0x7598ce17d4
	protected Void Finish(Int32 rootTable, String fileIdentifier, Boolean sizePrefix) { }
	// RVA: 0x66c990c VA: 0x7598ce190c
	public Void Finish(Int32 rootTable, String fileIdentifier) { }
	// RVA: 0x66c9914 VA: 0x7598ce1914
	public Void FinishSizePrefixed(Int32 rootTable, String fileIdentifier) { }
}
```