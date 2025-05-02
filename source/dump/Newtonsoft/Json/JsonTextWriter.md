# JsonTextWriter

**Namespace:** `Newtonsoft.Json`


## Fields

- `Base64Encoder _base64Encoder`

- `Char _indentChar`

- `Int32 _indentation`

- `Char _quoteChar`

- `Boolean _quoteName`


## Properties

- `Base64Encoder Base64Encoder`

- `Char QuoteChar`


## Methods

- `Base64Encoder get_Base64Encoder()`

- `Char get_QuoteChar()`

- `Void UpdateCharEscapeFlags()`

- `Void WriteValueInternal(String, JsonToken)`

- `Void WriteEscapedString(String, Boolean)`

- `Void EnsureWriteBuffer()`

- `Void WriteIntegerValue(Int64)`

- `Void WriteIntegerValue(UInt64)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonTextWriter : JsonWriter
{
	private readonly TextWriter _writer; // 0x60
	private Base64Encoder _base64Encoder; // 0x68
	private Char _indentChar; // 0x70
	private Int32 _indentation; // 0x74
	private Char _quoteChar; // 0x78
	private Boolean _quoteName; // 0x7a
	private Boolean[] _charEscapeFlags; // 0x80
	private Char[] _writeBuffer; // 0x88
	private IArrayPool`1 _arrayPool; // 0x90
	private Char[] _indentChars; // 0x98

	private Base64Encoder Base64Encoder { get; }
	public Char QuoteChar { get; }

	// RVA: 0x6145c24 VA: 0x759875dc24
	private Base64Encoder get_Base64Encoder() { }
	// RVA: 0x6145ca8 VA: 0x759875dca8
	public Char get_QuoteChar() { }
	// RVA: 0x6145cb0 VA: 0x759875dcb0
	public Void .ctor(TextWriter textWriter) { }
	// RVA: 0x6145e4c VA: 0x759875de4c
	public override Void Close() { }
	// RVA: 0x6145eb8 VA: 0x759875deb8
	public override Void WriteStartObject() { }
	// RVA: 0x6145f30 VA: 0x759875df30
	public override Void WriteStartArray() { }
	// RVA: 0x6145f68 VA: 0x759875df68
	public override Void WriteStartConstructor(String name) { }
	// RVA: 0x6146010 VA: 0x759875e010
	protected override Void WriteEnd(JsonToken token) { }
	// RVA: 0x6146118 VA: 0x759875e118
	public override Void WritePropertyName(String name) { }
	// RVA: 0x6146254 VA: 0x759875e254
	public override Void WritePropertyName(String name, Boolean escape) { }
	// RVA: 0x6146324 VA: 0x759875e324
	internal override Void OnStringEscapeHandlingChanged() { }
	// RVA: 0x6145dd8 VA: 0x759875ddd8
	private Void UpdateCharEscapeFlags() { }
	// RVA: 0x6146328 VA: 0x759875e328
	protected override Void WriteIndent() { }
	// RVA: 0x6146488 VA: 0x759875e488
	protected override Void WriteValueDelimiter() { }
	// RVA: 0x61464b0 VA: 0x759875e4b0
	protected override Void WriteIndentSpace() { }
	// RVA: 0x61464d8 VA: 0x759875e4d8
	private Void WriteValueInternal(String value, JsonToken token) { }
	// RVA: 0x61464fc VA: 0x759875e4fc
	public override Void WriteValue(Object value) { }
	// RVA: 0x61465d8 VA: 0x759875e5d8
	public override Void WriteNull() { }
	// RVA: 0x6146684 VA: 0x759875e684
	public override Void WriteUndefined() { }
	// RVA: 0x6146718 VA: 0x759875e718
	public override Void WriteRaw(String json) { }
	// RVA: 0x6146740 VA: 0x759875e740
	public override Void WriteValue(String value) { }
	// RVA: 0x6146194 VA: 0x759875e194
	private Void WriteEscapedString(String value, Boolean quote) { }
	// RVA: 0x6146840 VA: 0x759875e840
	public override Void WriteValue(Int32 value) { }
	// RVA: 0x61468fc VA: 0x759875e8fc
	public override Void WriteValue(UInt32 value) { }
	// RVA: 0x6146940 VA: 0x759875e940
	public override Void WriteValue(Int64 value) { }
	// RVA: 0x6146984 VA: 0x759875e984
	public override Void WriteValue(UInt64 value) { }
	// RVA: 0x6146a9c VA: 0x759875ea9c
	public override Void WriteValue(Single value) { }
	// RVA: 0x6146c44 VA: 0x759875ec44
	public override Void WriteValue(Nullable`1 value) { }
	// RVA: 0x6146d44 VA: 0x759875ed44
	public override Void WriteValue(Double value) { }
	// RVA: 0x6146ee8 VA: 0x759875eee8
	public override Void WriteValue(Nullable`1 value) { }
	// RVA: 0x6146ff4 VA: 0x759875eff4
	public override Void WriteValue(Boolean value) { }
	// RVA: 0x61470fc VA: 0x759875f0fc
	public override Void WriteValue(Int16 value) { }
	// RVA: 0x6147140 VA: 0x759875f140
	public override Void WriteValue(UInt16 value) { }
	// RVA: 0x6147184 VA: 0x759875f184
	public override Void WriteValue(Char value) { }
	// RVA: 0x61472ac VA: 0x759875f2ac
	public override Void WriteValue(Byte value) { }
	// RVA: 0x61472f0 VA: 0x759875f2f0
	public override Void WriteValue(SByte value) { }
	// RVA: 0x6147334 VA: 0x759875f334
	public override Void WriteValue(Decimal value) { }
	// RVA: 0x61474d4 VA: 0x759875f4d4
	public override Void WriteValue(DateTime value) { }
	// RVA: 0x6147760 VA: 0x759875f760
	public override Void WriteValue(Byte[] value) { }
	// RVA: 0x6147828 VA: 0x759875f828
	public override Void WriteValue(DateTimeOffset value) { }
	// RVA: 0x6147a68 VA: 0x759875fa68
	public override Void WriteValue(Guid value) { }
	// RVA: 0x6147b74 VA: 0x759875fb74
	public override Void WriteValue(TimeSpan value) { }
	// RVA: 0x6147c54 VA: 0x759875fc54
	public override Void WriteValue(Uri value) { }
	// RVA: 0x6147d24 VA: 0x759875fd24
	public override Void WriteComment(String text) { }
	// RVA: 0x61467f4 VA: 0x759875e7f4
	private Void EnsureWriteBuffer() { }
	// RVA: 0x6146884 VA: 0x759875e884
	private Void WriteIntegerValue(Int64 value) { }
	// RVA: 0x61469c8 VA: 0x759875e9c8
	private Void WriteIntegerValue(UInt64 uvalue) { }
}
```