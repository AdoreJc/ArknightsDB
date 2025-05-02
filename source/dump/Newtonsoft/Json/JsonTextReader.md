# JsonTextReader

**Namespace:** `Newtonsoft.Json`


## Fields

- `Int32 _charsUsed`

- `Int32 _charPos`

- `Int32 _lineStartPos`

- `Int32 _lineNumber`

- `Boolean _isEndOfFile`

- `StringBuffer _stringBuffer`

- `StringReference _stringReference`


## Properties

- `Int32 LineNumber`

- `Int32 LinePosition`


## Methods

- `Void EnsureBufferNotEmpty()`

- `Void OnNewLine(Int32)`

- `Void ParseString(Char, ReadType)`

- `Void ShiftBufferIfNeeded()`

- `Int32 ReadData(Boolean)`

- `Int32 ReadData(Boolean, Int32)`

- `Boolean EnsureChars(Int32, Boolean)`

- `Boolean ReadChars(Int32, Boolean)`

- `Object ReadStringValue(ReadType)`

- `JsonReaderException CreateUnexpectedCharacterException(Char)`

- `Void ProcessValueComma()`

- `Object ReadNumberValue(ReadType)`

- `Void HandleNull()`

- `Void ReadFinished()`

- `Boolean ReadNullChar()`

- `Void EnsureBuffer()`

- `Void ReadStringIntoBuffer(Char)`

- `Void WriteCharToBuffer(Char, Int32, Int32)`

- `Char ParseUnicode()`

- `Void ReadNumberIntoBuffer()`

- `Void ClearRecentString()`

- `Boolean ParsePostValue()`

- `Boolean ParseObject()`

- `Boolean ParseProperty()`

- `Boolean ValidIdentifierChar(Char)`

- `Void ParseUnquotedProperty()`

- `Boolean ParseValue()`

- `Void ProcessLineFeed()`

- `Void ProcessCarriageReturn(Boolean)`

- `Boolean EatWhitespace(Boolean)`

- `Void ParseConstructor()`

- `Void ParseNumber(ReadType)`

- `Void ParseComment(Boolean)`

- `Void EndComment(Boolean, Int32, Int32)`

- `Boolean MatchValue(String)`

- `Boolean MatchValueWithTrailingSeparator(String)`

- `Boolean IsSeparator(Char)`

- `Void ParseTrue()`

- `Void ParseNull()`

- `Void ParseUndefined()`

- `Void ParseFalse()`

- `Object ParseNumberNegativeInfinity(ReadType)`

- `Object ParseNumberPositiveInfinity(ReadType)`

- `Object ParseNumberNaN(ReadType)`

- `Boolean HasLineInfo()`

- `Int32 get_LineNumber()`

- `Int32 get_LinePosition()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json
public class JsonTextReader : JsonReader, IJsonLineInfo
{
	private readonly TextReader _reader; // 0x78
	private Char[] _chars; // 0x80
	private Int32 _charsUsed; // 0x88
	private Int32 _charPos; // 0x8c
	private Int32 _lineStartPos; // 0x90
	private Int32 _lineNumber; // 0x94
	private Boolean _isEndOfFile; // 0x98
	private StringBuffer _stringBuffer; // 0xa0
	private StringReference _stringReference; // 0xb0
	private IArrayPool`1 _arrayPool; // 0xc0
	internal PropertyNameTable NameTable; // 0xc8

	public Int32 LineNumber { get; }
	public Int32 LinePosition { get; }

	// RVA: 0x613ebd0 VA: 0x7598756bd0
	public Void .ctor(TextReader reader) { }
	// RVA: 0x613ecb0 VA: 0x7598756cb0
	private Void EnsureBufferNotEmpty() { }
	// RVA: 0x613ed10 VA: 0x7598756d10
	private Void OnNewLine(Int32 pos) { }
	// RVA: 0x613ed20 VA: 0x7598756d20
	private Void ParseString(Char quote, ReadType readType) { }
	// RVA: 0x613f7b0 VA: 0x75987577b0
	private static Void BlockCopyChars(Char[] src, Int32 srcOffset, Char[] dst, Int32 dstOffset, Int32 count) { }
	// RVA: 0x613f034 VA: 0x7598757034
	private Void ShiftBufferIfNeeded() { }
	// RVA: 0x613f7c4 VA: 0x75987577c4
	private Int32 ReadData(Boolean append) { }
	// RVA: 0x613f7d0 VA: 0x75987577d0
	private Int32 ReadData(Boolean append, Int32 charsRequired) { }
	// RVA: 0x613f9f8 VA: 0x75987579f8
	private Boolean EnsureChars(Int32 relativePosition, Boolean append) { }
	// RVA: 0x613fa18 VA: 0x7598757a18
	private Boolean ReadChars(Int32 relativePosition, Boolean append) { }
	// RVA: 0x613fa88 VA: 0x7598757a88
	public override Boolean Read() { }
	// RVA: 0x61408f8 VA: 0x75987588f8
	public override Nullable`1 ReadAsInt32() { }
	// RVA: 0x6140e48 VA: 0x7598758e48
	public override Nullable`1 ReadAsDateTime() { }
	// RVA: 0x61415f0 VA: 0x75987595f0
	public override String ReadAsString() { }
	// RVA: 0x6141654 VA: 0x7598759654
	public override Byte[] ReadAsBytes() { }
	// RVA: 0x6140ed8 VA: 0x7598758ed8
	private Object ReadStringValue(ReadType readType) { }
	// RVA: 0x6142074 VA: 0x759875a074
	private JsonReaderException CreateUnexpectedCharacterException(Char c) { }
	// RVA: 0x6143aac VA: 0x759875baac
	public override Nullable`1 ReadAsBoolean() { }
	// RVA: 0x614201c VA: 0x759875a01c
	private Void ProcessValueComma() { }
	// RVA: 0x6140988 VA: 0x7598758988
	private Object ReadNumberValue(ReadType readType) { }
	// RVA: 0x614462c VA: 0x759875c62c
	public override Nullable`1 ReadAsDateTimeOffset() { }
	// RVA: 0x61446f8 VA: 0x759875c6f8
	public override Nullable`1 ReadAsDecimal() { }
	// RVA: 0x61447c4 VA: 0x759875c7c4
	public override Nullable`1 ReadAsDouble() { }
	// RVA: 0x6141f4c VA: 0x7598759f4c
	private Void HandleNull() { }
	// RVA: 0x61421e0 VA: 0x759875a1e0
	private Void ReadFinished() { }
	// RVA: 0x6141aa0 VA: 0x7598759aa0
	private Boolean ReadNullChar() { }
	// RVA: 0x613fcac VA: 0x7598757cac
	private Void EnsureBuffer() { }
	// RVA: 0x613f0dc VA: 0x75987570dc
	private Void ReadStringIntoBuffer(Char quote) { }
	// RVA: 0x6144a80 VA: 0x759875ca80
	private Void WriteCharToBuffer(Char writeChar, Int32 lastWritePosition, Int32 writeToPosition) { }
	// RVA: 0x6144970 VA: 0x759875c970
	private Char ParseUnicode() { }
	// RVA: 0x6144ad0 VA: 0x759875cad0
	private Void ReadNumberIntoBuffer() { }
	// RVA: 0x6144ca0 VA: 0x759875cca0
	private Void ClearRecentString() { }
	// RVA: 0x61402b8 VA: 0x75987582b8
	private Boolean ParsePostValue() { }
	// RVA: 0x6140128 VA: 0x7598758128
	private Boolean ParseObject() { }
	// RVA: 0x6144cac VA: 0x759875ccac
	private Boolean ParseProperty() { }
	// RVA: 0x6144ed0 VA: 0x759875ced0
	private Boolean ValidIdentifierChar(Char value) { }
	// RVA: 0x6144f50 VA: 0x759875cf50
	private Void ParseUnquotedProperty() { }
	// RVA: 0x613fd0c VA: 0x7598757d0c
	private Boolean ParseValue() { }
	// RVA: 0x61421c4 VA: 0x759875a1c4
	private Void ProcessLineFeed() { }
	// RVA: 0x6142144 VA: 0x759875a144
	private Void ProcessCarriageReturn(Boolean append) { }
	// RVA: 0x6140528 VA: 0x7598758528
	private Boolean EatWhitespace(Boolean oneOrMore) { }
	// RVA: 0x61452cc VA: 0x759875d2cc
	private Void ParseConstructor() { }
	// RVA: 0x61428a0 VA: 0x759875a8a0
	private Void ParseNumber(ReadType readType) { }
	// RVA: 0x6140664 VA: 0x7598758664
	private Void ParseComment(Boolean setToken) { }
	// RVA: 0x6145730 VA: 0x759875d730
	private Void EndComment(Boolean setToken, Int32 initialPosition, Int32 endPosition) { }
	// RVA: 0x614579c VA: 0x759875d79c
	private Boolean MatchValue(String value) { }
	// RVA: 0x6143740 VA: 0x759875b740
	private Boolean MatchValueWithTrailingSeparator(String value) { }
	// RVA: 0x61458a0 VA: 0x759875d8a0
	private Boolean IsSeparator(Char c) { }
	// RVA: 0x6145110 VA: 0x759875d110
	private Void ParseTrue() { }
	// RVA: 0x6144878 VA: 0x759875c878
	private Void ParseNull() { }
	// RVA: 0x6145600 VA: 0x759875d600
	private Void ParseUndefined() { }
	// RVA: 0x61451f0 VA: 0x759875d1f0
	private Void ParseFalse() { }
	// RVA: 0x6142740 VA: 0x759875a740
	private Object ParseNumberNegativeInfinity(ReadType readType) { }
	// RVA: 0x61437ec VA: 0x759875b7ec
	private Object ParseNumberPositiveInfinity(ReadType readType) { }
	// RVA: 0x614394c VA: 0x759875b94c
	private Object ParseNumberNaN(ReadType readType) { }
	// RVA: 0x61459f8 VA: 0x759875d9f8
	public override Void Close() { }
	// RVA: 0x6145a90 VA: 0x759875da90
	public Boolean HasLineInfo() { }
	// RVA: 0x6145a98 VA: 0x759875da98
	public Int32 get_LineNumber() { }
	// RVA: 0x6145ae0 VA: 0x759875dae0
	public Int32 get_LinePosition() { }
}
```