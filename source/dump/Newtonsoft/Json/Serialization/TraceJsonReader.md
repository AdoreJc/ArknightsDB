# TraceJsonReader

**Namespace:** `Newtonsoft.Json.Serialization`


## Methods

- `String GetDeserializedJsonMessage()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class TraceJsonReader : JsonReader, IJsonLineInfo
{
	private readonly JsonReader _innerReader; // 0x78
	private readonly JsonTextWriter _textWriter; // 0x80
	private readonly StringWriter _sw; // 0x88

	public override Int32 Depth { get; }
	public override String Path { get; }
	public override JsonToken TokenType { get; }
	public override Object Value { get; }
	public override Type ValueType { get; }
	private Int32 Newtonsoft.Json.IJsonLineInfo.LineNumber { get; }
	private Int32 Newtonsoft.Json.IJsonLineInfo.LinePosition { get; }

	// RVA: 0x6164c64 VA: 0x759877cc64
	public Void .ctor(JsonReader innerReader) { }
	// RVA: 0x6164dd8 VA: 0x759877cdd8
	public String GetDeserializedJsonMessage() { }
	// RVA: 0x6164df8 VA: 0x759877cdf8
	public override Boolean Read() { }
	// RVA: 0x6164e5c VA: 0x759877ce5c
	public override Nullable`1 ReadAsInt32() { }
	// RVA: 0x6164ec0 VA: 0x759877cec0
	public override String ReadAsString() { }
	// RVA: 0x6164f24 VA: 0x759877cf24
	public override Byte[] ReadAsBytes() { }
	// RVA: 0x6164f8c VA: 0x759877cf8c
	public override Nullable`1 ReadAsDecimal() { }
	// RVA: 0x6165028 VA: 0x759877d028
	public override Nullable`1 ReadAsDouble() { }
	// RVA: 0x6165094 VA: 0x759877d094
	public override Nullable`1 ReadAsBoolean() { }
	// RVA: 0x61650f4 VA: 0x759877d0f4
	public override Nullable`1 ReadAsDateTime() { }
	// RVA: 0x6165160 VA: 0x759877d160
	public override Nullable`1 ReadAsDateTimeOffset() { }
	// RVA: 0x61651dc VA: 0x759877d1dc
	public override Int32 get_Depth() { }
	// RVA: 0x61651fc VA: 0x759877d1fc
	public override String get_Path() { }
	// RVA: 0x616521c VA: 0x759877d21c
	public override JsonToken get_TokenType() { }
	// RVA: 0x616523c VA: 0x759877d23c
	public override Object get_Value() { }
	// RVA: 0x616525c VA: 0x759877d25c
	public override Type get_ValueType() { }
	// RVA: 0x616527c VA: 0x759877d27c
	public override Void Close() { }
	// RVA: 0x61652a0 VA: 0x759877d2a0
	private Boolean Newtonsoft.Json.IJsonLineInfo.HasLineInfo() { }
	// RVA: 0x6165354 VA: 0x759877d354
	private Int32 Newtonsoft.Json.IJsonLineInfo.get_LineNumber() { }
	// RVA: 0x616540c VA: 0x759877d40c
	private Int32 Newtonsoft.Json.IJsonLineInfo.get_LinePosition() { }
}
```