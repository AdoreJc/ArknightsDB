# TraceJsonWriter

**Namespace:** `Newtonsoft.Json.Serialization`


## Methods

- `String GetSerializedJsonMessage()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class TraceJsonWriter : JsonWriter
{
	private readonly JsonWriter _innerWriter; // 0x60
	private readonly JsonTextWriter _textWriter; // 0x68
	private readonly StringWriter _sw; // 0x70


	// RVA: 0x61654c4 VA: 0x759877d4c4
	public Void .ctor(JsonWriter innerWriter) { }
	// RVA: 0x61656d4 VA: 0x759877d6d4
	public String GetSerializedJsonMessage() { }
	// RVA: 0x61656f4 VA: 0x759877d6f4
	public override Void WriteValue(Decimal value) { }
	// RVA: 0x6165760 VA: 0x759877d760
	public override Void WriteValue(Boolean value) { }
	// RVA: 0x61657c4 VA: 0x759877d7c4
	public override Void WriteValue(Byte value) { }
	// RVA: 0x6165824 VA: 0x759877d824
	public override Void WriteValue(Nullable`1 value) { }
	// RVA: 0x6165888 VA: 0x759877d888
	public override Void WriteValue(Char value) { }
	// RVA: 0x61658e8 VA: 0x759877d8e8
	public override Void WriteValue(Byte[] value) { }
	// RVA: 0x6165948 VA: 0x759877d948
	public override Void WriteValue(DateTime value) { }
	// RVA: 0x61659a8 VA: 0x759877d9a8
	public override Void WriteValue(DateTimeOffset value) { }
	// RVA: 0x6165a14 VA: 0x759877da14
	public override Void WriteValue(Double value) { }
	// RVA: 0x6165a74 VA: 0x759877da74
	public override Void WriteUndefined() { }
	// RVA: 0x6165ac0 VA: 0x759877dac0
	public override Void WriteNull() { }
	// RVA: 0x6165b0c VA: 0x759877db0c
	public override Void WriteValue(Single value) { }
	// RVA: 0x6165b6c VA: 0x759877db6c
	public override Void WriteValue(Guid value) { }
	// RVA: 0x6165bd8 VA: 0x759877dbd8
	public override Void WriteValue(Int32 value) { }
	// RVA: 0x6165c38 VA: 0x759877dc38
	public override Void WriteValue(Int64 value) { }
	// RVA: 0x6165c98 VA: 0x759877dc98
	public override Void WriteValue(Object value) { }
	// RVA: 0x6165cf8 VA: 0x759877dcf8
	public override Void WriteValue(SByte value) { }
	// RVA: 0x6165d58 VA: 0x759877dd58
	public override Void WriteValue(Int16 value) { }
	// RVA: 0x6165db8 VA: 0x759877ddb8
	public override Void WriteValue(String value) { }
	// RVA: 0x6165e18 VA: 0x759877de18
	public override Void WriteValue(TimeSpan value) { }
	// RVA: 0x6165e78 VA: 0x759877de78
	public override Void WriteValue(UInt32 value) { }
	// RVA: 0x6165ed8 VA: 0x759877ded8
	public override Void WriteValue(UInt64 value) { }
	// RVA: 0x6165f38 VA: 0x759877df38
	public override Void WriteValue(Uri value) { }
	// RVA: 0x6165f98 VA: 0x759877df98
	public override Void WriteValue(UInt16 value) { }
	// RVA: 0x6165ff8 VA: 0x759877dff8
	public override Void WriteComment(String text) { }
	// RVA: 0x6166058 VA: 0x759877e058
	public override Void WriteStartArray() { }
	// RVA: 0x616609c VA: 0x759877e09c
	public override Void WriteEndArray() { }
	// RVA: 0x61660e0 VA: 0x759877e0e0
	public override Void WriteStartConstructor(String name) { }
	// RVA: 0x6166138 VA: 0x759877e138
	public override Void WriteEndConstructor() { }
	// RVA: 0x616617c VA: 0x759877e17c
	public override Void WritePropertyName(String name) { }
	// RVA: 0x61661dc VA: 0x759877e1dc
	public override Void WritePropertyName(String name, Boolean escape) { }
	// RVA: 0x6166248 VA: 0x759877e248
	public override Void WriteStartObject() { }
	// RVA: 0x616628c VA: 0x759877e28c
	public override Void WriteEndObject() { }
	// RVA: 0x61662d0 VA: 0x759877e2d0
	public override Void WriteRawValue(String json) { }
	// RVA: 0x6166330 VA: 0x759877e330
	public override Void WriteRaw(String json) { }
	// RVA: 0x6166390 VA: 0x759877e390
	public override Void Close() { }
}
```