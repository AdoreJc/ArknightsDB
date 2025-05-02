# BsonWriter

**Namespace:** `Newtonsoft.Json.Bson`


## Fields

- `BsonToken _root`

- `BsonToken _parent`

- `String _propertyName`


## Methods

- `Void AddParent(BsonToken)`

- `Void RemoveParent()`

- `Void AddValue(Object, BsonType)`

- `Void WriteObjectId(Byte[])`

- `Void WriteRegex(String, String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Bson
public class BsonWriter : JsonWriter
{
	private readonly BsonBinaryWriter _writer; // 0x60
	private BsonToken _root; // 0x68
	private BsonToken _parent; // 0x70
	private String _propertyName; // 0x78


	// RVA: 0x61ba0e8 VA: 0x75987d20e8
	public Void .ctor(Stream stream) { }
	// RVA: 0x61ba1f8 VA: 0x75987d21f8
	protected override Void WriteEnd(JsonToken token) { }
	// RVA: 0x61ba280 VA: 0x75987d2280
	public override Void WriteComment(String text) { }
	// RVA: 0x61ba2c4 VA: 0x75987d22c4
	public override Void WriteStartConstructor(String name) { }
	// RVA: 0x61ba308 VA: 0x75987d2308
	public override Void WriteRaw(String json) { }
	// RVA: 0x61ba34c VA: 0x75987d234c
	public override Void WriteRawValue(String json) { }
	// RVA: 0x61ba390 VA: 0x75987d2390
	public override Void WriteStartArray() { }
	// RVA: 0x61ba438 VA: 0x75987d2438
	public override Void WriteStartObject() { }
	// RVA: 0x61ba4b4 VA: 0x75987d24b4
	public override Void WritePropertyName(String name) { }
	// RVA: 0x61ba4e4 VA: 0x75987d24e4
	public override Void Close() { }
	// RVA: 0x61ba40c VA: 0x75987d240c
	private Void AddParent(BsonToken container) { }
	// RVA: 0x61ba260 VA: 0x75987d2260
	private Void RemoveParent() { }
	// RVA: 0x61ba738 VA: 0x75987d2738
	private Void AddValue(Object value, BsonType type) { }
	// RVA: 0x61ba528 VA: 0x75987d2528
	internal Void AddToken(BsonToken token) { }
	// RVA: 0x61ba7c0 VA: 0x75987d27c0
	public override Void WriteValue(Object value) { }
	// RVA: 0x61ba7c8 VA: 0x75987d27c8
	public override Void WriteNull() { }
	// RVA: 0x61ba7ec VA: 0x75987d27ec
	public override Void WriteUndefined() { }
	// RVA: 0x61ba810 VA: 0x75987d2810
	public override Void WriteValue(String value) { }
	// RVA: 0x61ba8c4 VA: 0x75987d28c4
	public override Void WriteValue(Int32 value) { }
	// RVA: 0x61ba940 VA: 0x75987d2940
	public override Void WriteValue(UInt32 value) { }
	// RVA: 0x61ba9fc VA: 0x75987d29fc
	public override Void WriteValue(Int64 value) { }
	// RVA: 0x61baa78 VA: 0x75987d2a78
	public override Void WriteValue(UInt64 value) { }
	// RVA: 0x61bab34 VA: 0x75987d2b34
	public override Void WriteValue(Single value) { }
	// RVA: 0x61babb0 VA: 0x75987d2bb0
	public override Void WriteValue(Double value) { }
	// RVA: 0x61bac2c VA: 0x75987d2c2c
	public override Void WriteValue(Boolean value) { }
	// RVA: 0x61baca8 VA: 0x75987d2ca8
	public override Void WriteValue(Int16 value) { }
	// RVA: 0x61bad24 VA: 0x75987d2d24
	public override Void WriteValue(UInt16 value) { }
	// RVA: 0x61bada0 VA: 0x75987d2da0
	public override Void WriteValue(Char value) { }
	// RVA: 0x61baeb8 VA: 0x75987d2eb8
	public override Void WriteValue(Byte value) { }
	// RVA: 0x61baf34 VA: 0x75987d2f34
	public override Void WriteValue(SByte value) { }
	// RVA: 0x61bafb0 VA: 0x75987d2fb0
	public override Void WriteValue(Decimal value) { }
	// RVA: 0x61bb064 VA: 0x75987d3064
	public override Void WriteValue(DateTime value) { }
	// RVA: 0x61bb11c VA: 0x75987d311c
	public override Void WriteValue(DateTimeOffset value) { }
	// RVA: 0x61bb1a8 VA: 0x75987d31a8
	public override Void WriteValue(Byte[] value) { }
	// RVA: 0x61bb240 VA: 0x75987d3240
	public override Void WriteValue(Guid value) { }
	// RVA: 0x61bb304 VA: 0x75987d3304
	public override Void WriteValue(TimeSpan value) { }
	// RVA: 0x61bb3e4 VA: 0x75987d33e4
	public override Void WriteValue(Uri value) { }
	// RVA: 0x61a7f9c VA: 0x75987bff9c
	public Void WriteObjectId(Byte[] value) { }
	// RVA: 0x61a8764 VA: 0x75987c0764
	public Void WriteRegex(String pattern, String options) { }
}
```