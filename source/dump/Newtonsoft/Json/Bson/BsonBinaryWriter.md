# BsonBinaryWriter

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `DateTimeKind <DateTimeKindHandling>k__BackingField`


## Properties

- `DateTimeKind DateTimeKindHandling`


## Methods

- `DateTimeKind get_DateTimeKindHandling()`

- `Void set_DateTimeKindHandling(DateTimeKind)`

- `Void Close()`

- `Void WriteToken(BsonToken)`

- `Void WriteTokenInternal(BsonToken)`

- `Void WriteString(String, Int32, Nullable`1)`

- `Void WriteUtf8Bytes(String, Int32)`

- `Int32 CalculateSize(Int32)`

- `Int32 CalculateSizeWithLength(Int32, Boolean)`

- `Int32 CalculateSize(BsonToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
internal class BsonBinaryWriter
{
	private static readonly Encoding Encoding; // 0x0
	private readonly BinaryWriter _writer; // 0x10
	private Byte[] _largeByteBuffer; // 0x18
	private DateTimeKind <DateTimeKindHandling>k__BackingField; // 0x20

	public DateTimeKind DateTimeKindHandling { get; set; }

	// RVA: 0x61b64ac VA: 0x75987ce4ac
	public DateTimeKind get_DateTimeKindHandling() { }
	// RVA: 0x61b64b4 VA: 0x75987ce4b4
	public Void set_DateTimeKindHandling(DateTimeKind value) { }
	// RVA: 0x61b64bc VA: 0x75987ce4bc
	public Void .ctor(BinaryWriter writer) { }
	// RVA: 0x61b64f4 VA: 0x75987ce4f4
	public Void Close() { }
	// RVA: 0x61b6514 VA: 0x75987ce514
	public Void WriteToken(BsonToken t) { }
	// RVA: 0x61b6dd8 VA: 0x75987cedd8
	private Void WriteTokenInternal(BsonToken t) { }
	// RVA: 0x61b7ce8 VA: 0x75987cfce8
	private Void WriteString(String s, Int32 byteCount, Nullable`1 calculatedlengthPrefix) { }
	// RVA: 0x61b7e1c VA: 0x75987cfe1c
	public Void WriteUtf8Bytes(String s, Int32 byteCount) { }
	// RVA: 0x61b7f68 VA: 0x75987cff68
	private Int32 CalculateSize(Int32 stringByteCount) { }
	// RVA: 0x61b7f70 VA: 0x75987cff70
	private Int32 CalculateSizeWithLength(Int32 stringByteCount, Boolean includeSize) { }
	// RVA: 0x61b653c VA: 0x75987ce53c
	private Int32 CalculateSize(BsonToken t) { }
	// RVA: 0x61b7f84 VA: 0x75987cff84
	private static Void .cctor() { }
}
```