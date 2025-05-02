# JsonNetConverter

**Namespace:** `Torappu.DB`


## Fields

- `JsonSerializerSettings m_settings`

- `Formatting m_format`

- `JsonSerializer m_serializer`


## Methods

- `Void Serialize(Object, Stream)`

- `String Serialize(Object)`

- `T Deserialize(ConverterInput)`

- `T Deserialize(Stream)`

- `Object Deserialize(ConverterInput)`

- `Object DeserializeWithType(ConverterInput, Type)`

- `Object Deserialize(Stream)`

- `Void Populate(TextAsset, Object)`

- `Void Populate(Stream, Object)`

- `Void SerializeBytes(Byte[], Stream)`

- `Boolean PreprocessText(TextAsset, Stream, ITableDataType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class JsonNetConverter : IConverter
{
	private JsonSerializerSettings m_settings; // 0x10
	private Formatting m_format; // 0x18
	private JsonSerializer m_serializer; // 0x20

	protected virtual JsonSerializerSettings serializerSetting { get; }

	// RVA: 0x3717764 VA: 0x7595d2f764
	public Void .ctor(Formatting format) { }
	// RVA: 0x371aba8 VA: 0x7595d32ba8
	protected virtual JsonSerializerSettings get_serializerSetting() { }
	// RVA: 0x371abb0 VA: 0x7595d32bb0
	public Void Serialize(Object value, Stream stream) { }
	// RVA: 0x371aebc VA: 0x7595d32ebc
	public String Serialize(Object value) { }
	// RVA: 0x VA: 0x0
	public T Deserialize(ConverterInput value) { }
	// RVA: 0x VA: 0x0
	public T Deserialize(Stream stream) { }
	// RVA: 0x371af48 VA: 0x7595d32f48
	public Object Deserialize(ConverterInput value) { }
	// RVA: 0x371afcc VA: 0x7595d32fcc
	public Object DeserializeWithType(ConverterInput value, Type type) { }
	// RVA: 0x371b058 VA: 0x7595d33058
	public Object Deserialize(Stream stream) { }
	// RVA: 0x371b364 VA: 0x7595d33364
	public Void Populate(TextAsset value, Object target) { }
	// RVA: 0x371b408 VA: 0x7595d33408
	public Void Populate(Stream stream, Object target) { }
	// RVA: 0x371b700 VA: 0x7595d33700
	public Void SerializeBytes(Byte[] bytes, Stream stream) { }
	// RVA: 0x371b940 VA: 0x7595d33940
	public Byte[] DeserializeBytes(Stream stream) { }
	// RVA: 0x371bb08 VA: 0x7595d33b08
	public Boolean PreprocessText(TextAsset textAsset, Stream outStream, ITableDataType table) { }
}
```