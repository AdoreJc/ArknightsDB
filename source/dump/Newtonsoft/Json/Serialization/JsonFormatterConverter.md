# JsonFormatterConverter

**Namespace:** `Newtonsoft.Json.Serialization`


## Methods

- `T GetTokenValue(Object)`

- `Object Convert(Object, Type)`

- `Boolean ToBoolean(Object)`

- `Int32 ToInt32(Object)`

- `Int64 ToInt64(Object)`

- `Single ToSingle(Object)`

- `String ToString(Object)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class JsonFormatterConverter : IFormatterConverter
{
	private readonly JsonSerializerInternalReader _reader; // 0x10
	private readonly JsonISerializableContract _contract; // 0x18
	private readonly JsonProperty _member; // 0x20


	// RVA: 0x61663d4 VA: 0x759877e3d4
	public Void .ctor(JsonSerializerInternalReader reader, JsonISerializableContract contract, JsonProperty member) { }
	// RVA: 0x VA: 0x0
	private T GetTokenValue(Object value) { }
	// RVA: 0x6166494 VA: 0x759877e494
	public Object Convert(Object value, Type type) { }
	// RVA: 0x61665b0 VA: 0x759877e5b0
	public Boolean ToBoolean(Object value) { }
	// RVA: 0x6166608 VA: 0x759877e608
	public Int32 ToInt32(Object value) { }
	// RVA: 0x6166660 VA: 0x759877e660
	public Int64 ToInt64(Object value) { }
	// RVA: 0x61666b8 VA: 0x759877e6b8
	public Single ToSingle(Object value) { }
	// RVA: 0x6166710 VA: 0x759877e710
	public String ToString(Object value) { }
}
```