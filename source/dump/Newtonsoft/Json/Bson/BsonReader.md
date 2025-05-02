# BsonReader

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `BsonType _currentElementType`

- `BsonReaderState _bsonReaderState`

- `ContainerContext _currentContext`

- `Boolean _readRootValueAsArray`

- `Boolean _jsonNet35BinaryCompatibility`

- `DateTimeKind _dateTimeKindHandling`


## Properties

- `DateTimeKind DateTimeKindHandling`


## Methods

- `DateTimeKind get_DateTimeKindHandling()`

- `String ReadElement()`

- `Boolean ReadCodeWScope()`

- `Boolean ReadReference()`

- `Boolean ReadNormal()`

- `Void PopContext()`

- `Void PushContext(ContainerContext)`

- `Byte ReadByte()`

- `Void ReadType(BsonType)`

- `String ReadString()`

- `String ReadLengthString()`

- `String GetString(Int32)`

- `Int32 GetLastFullCharStop(Int32)`

- `Int32 BytesInSequence(Byte)`

- `Void EnsureBuffers()`

- `Double ReadDouble()`

- `Int32 ReadInt32()`

- `Int64 ReadInt64()`

- `BsonType ReadType()`

- `Void MovePosition(Int32)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
public class BsonReader : JsonReader
{
	private static readonly Byte[] SeqRange1; // 0x0
	private static readonly Byte[] SeqRange2; // 0x8
	private static readonly Byte[] SeqRange3; // 0x10
	private static readonly Byte[] SeqRange4; // 0x18
	private readonly BinaryReader _reader; // 0x78
	private readonly List`1 _stack; // 0x80
	private Byte[] _byteBuffer; // 0x88
	private Char[] _charBuffer; // 0x90
	private BsonType _currentElementType; // 0x98
	private BsonReaderState _bsonReaderState; // 0x9c
	private ContainerContext _currentContext; // 0xa0
	private Boolean _readRootValueAsArray; // 0xa8
	private Boolean _jsonNet35BinaryCompatibility; // 0xa9
	private DateTimeKind _dateTimeKindHandling; // 0xac

	public DateTimeKind DateTimeKindHandling { get; }

	// RVA: 0x61b800c VA: 0x75987d000c
	public DateTimeKind get_DateTimeKindHandling() { }
	// RVA: 0x61b8014 VA: 0x75987d0014
	public Void .ctor(Stream stream) { }
	// RVA: 0x61b8020 VA: 0x75987d0020
	public Void .ctor(Stream stream, Boolean readRootValueAsArray, DateTimeKind dateTimeKindHandling) { }
	// RVA: 0x61b8138 VA: 0x75987d0138
	private String ReadElement() { }
	// RVA: 0x61b83f8 VA: 0x75987d03f8
	public override Boolean Read() { }
	// RVA: 0x61b8b30 VA: 0x75987d0b30
	public override Void Close() { }
	// RVA: 0x61b8950 VA: 0x75987d0950
	private Boolean ReadCodeWScope() { }
	// RVA: 0x61b8794 VA: 0x75987d0794
	private Boolean ReadReference() { }
	// RVA: 0x61b85a0 VA: 0x75987d05a0
	private Boolean ReadNormal() { }
	// RVA: 0x61b928c VA: 0x75987d128c
	private Void PopContext() { }
	// RVA: 0x61b8c20 VA: 0x75987d0c20
	private Void PushContext(ContainerContext newContext) { }
	// RVA: 0x61b9258 VA: 0x75987d1258
	private Byte ReadByte() { }
	// RVA: 0x61b8d14 VA: 0x75987d0d14
	private Void ReadType(BsonType type) { }
	// RVA: 0x61b939c VA: 0x75987d139c
	private Byte[] ReadBinary(out BsonBinaryType binaryType) { }
	// RVA: 0x61b8188 VA: 0x75987d0188
	private String ReadString() { }
	// RVA: 0x61b8ba0 VA: 0x75987d0ba0
	private String ReadLengthString() { }
	// RVA: 0x61b9580 VA: 0x75987d1580
	private String GetString(Int32 length) { }
	// RVA: 0x61b94fc VA: 0x75987d14fc
	private Int32 GetLastFullCharStop(Int32 start) { }
	// RVA: 0x61b97f4 VA: 0x75987d17f4
	private Int32 BytesInSequence(Byte b) { }
	// RVA: 0x61b942c VA: 0x75987d142c
	private Void EnsureBuffers() { }
	// RVA: 0x61b9364 VA: 0x75987d1364
	private Double ReadDouble() { }
	// RVA: 0x61b8b68 VA: 0x75987d0b68
	private Int32 ReadInt32() { }
	// RVA: 0x61b93f4 VA: 0x75987d13f4
	private Int64 ReadInt64() { }
	// RVA: 0x61b8154 VA: 0x75987d0154
	private BsonType ReadType() { }
	// RVA: 0x61b9340 VA: 0x75987d1340
	private Void MovePosition(Int32 count) { }
	// RVA: 0x61b8cdc VA: 0x75987d0cdc
	private Byte[] ReadBytes(Int32 count) { }
	// RVA: 0x61b99c4 VA: 0x75987d19c4
	private static Void .cctor() { }
}
```