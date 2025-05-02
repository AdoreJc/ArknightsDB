# JTokenWriter

**Namespace:** `Newtonsoft.Json.Linq`


## Fields

- `JContainer _token`

- `JContainer _parent`

- `JValue _value`

- `JToken _current`


## Properties

- `JToken Token`


## Methods

- `JToken get_Token()`

- `Void AddParent(JContainer)`

- `Void RemoveParent()`

- `Void AddValue(Object, JsonToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JTokenWriter : JsonWriter
{
	private JContainer _token; // 0x60
	private JContainer _parent; // 0x68
	private JValue _value; // 0x70
	private JToken _current; // 0x78

	public JToken Token { get; }

	// RVA: 0x6192d94 VA: 0x75987aad94
	public JToken get_Token() { }
	// RVA: 0x6192db0 VA: 0x75987aadb0
	public Void .ctor() { }
	// RVA: 0x6192e08 VA: 0x75987aae08
	public override Void Close() { }
	// RVA: 0x6192e10 VA: 0x75987aae10
	public override Void WriteStartObject() { }
	// RVA: 0x6192e7c VA: 0x75987aae7c
	private Void AddParent(JContainer container) { }
	// RVA: 0x6192edc VA: 0x75987aaedc
	private Void RemoveParent() { }
	// RVA: 0x6192f4c VA: 0x75987aaf4c
	public override Void WriteStartArray() { }
	// RVA: 0x6192fb8 VA: 0x75987aafb8
	public override Void WriteStartConstructor(String name) { }
	// RVA: 0x6193038 VA: 0x75987ab038
	protected override Void WriteEnd(JsonToken token) { }
	// RVA: 0x619303c VA: 0x75987ab03c
	public override Void WritePropertyName(String name) { }
	// RVA: 0x6193104 VA: 0x75987ab104
	private Void AddValue(Object value, JsonToken token) { }
	// RVA: 0x6193188 VA: 0x75987ab188
	internal Void AddValue(JValue value, JsonToken token) { }
	// RVA: 0x6193250 VA: 0x75987ab250
	public override Void WriteValue(Object value) { }
	// RVA: 0x6193258 VA: 0x75987ab258
	public override Void WriteNull() { }
	// RVA: 0x6193278 VA: 0x75987ab278
	public override Void WriteUndefined() { }
	// RVA: 0x6193298 VA: 0x75987ab298
	public override Void WriteRaw(String json) { }
	// RVA: 0x619331c VA: 0x75987ab31c
	public override Void WriteComment(String text) { }
	// RVA: 0x6193350 VA: 0x75987ab350
	public override Void WriteValue(String value) { }
	// RVA: 0x6193380 VA: 0x75987ab380
	public override Void WriteValue(Int32 value) { }
	// RVA: 0x61933fc VA: 0x75987ab3fc
	public override Void WriteValue(UInt32 value) { }
	// RVA: 0x6193478 VA: 0x75987ab478
	public override Void WriteValue(Int64 value) { }
	// RVA: 0x61934f4 VA: 0x75987ab4f4
	public override Void WriteValue(UInt64 value) { }
	// RVA: 0x6193570 VA: 0x75987ab570
	public override Void WriteValue(Single value) { }
	// RVA: 0x61935ec VA: 0x75987ab5ec
	public override Void WriteValue(Double value) { }
	// RVA: 0x6193668 VA: 0x75987ab668
	public override Void WriteValue(Boolean value) { }
	// RVA: 0x61936e4 VA: 0x75987ab6e4
	public override Void WriteValue(Int16 value) { }
	// RVA: 0x6193760 VA: 0x75987ab760
	public override Void WriteValue(UInt16 value) { }
	// RVA: 0x61937dc VA: 0x75987ab7dc
	public override Void WriteValue(Char value) { }
	// RVA: 0x61938a0 VA: 0x75987ab8a0
	public override Void WriteValue(Byte value) { }
	// RVA: 0x619391c VA: 0x75987ab91c
	public override Void WriteValue(SByte value) { }
	// RVA: 0x6193998 VA: 0x75987ab998
	public override Void WriteValue(Decimal value) { }
	// RVA: 0x6193a4c VA: 0x75987aba4c
	public override Void WriteValue(DateTime value) { }
	// RVA: 0x6193b04 VA: 0x75987abb04
	public override Void WriteValue(DateTimeOffset value) { }
	// RVA: 0x6193b90 VA: 0x75987abb90
	public override Void WriteValue(Byte[] value) { }
	// RVA: 0x6193bc0 VA: 0x75987abbc0
	public override Void WriteValue(TimeSpan value) { }
	// RVA: 0x6193c3c VA: 0x75987abc3c
	public override Void WriteValue(Guid value) { }
	// RVA: 0x6193cc8 VA: 0x75987abcc8
	public override Void WriteValue(Uri value) { }
	// RVA: 0x6193cf8 VA: 0x75987abcf8
	internal override Void WriteToken(JsonReader reader, Boolean writeChildren, Boolean writeDateConstructorAsDate, Boolean writeComments) { }
}
```