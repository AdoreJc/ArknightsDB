# BsonNetConverter

**Namespace:** `Torappu.DB`


## Fields

- `JsonSerializerSettings m_settings`

- `Formatting m_format`

- `JsonSerializer m_serializer`


## Properties

- `JsonSerializer serializer`


## Methods

- `JsonSerializer get_serializer()`

- `T Deserialize(Stream)`

- `T Deserialize(ConverterInput)`

- `Object Deserialize(Stream)`

- `Object Deserialize(ConverterInput)`

- `Void Populate(Stream, Object)`

- `Void Populate(TextAsset, Object)`

- `Void SerializeBytes(Byte[], Stream)`

- `JContainer _DeserializePlainJSON(Stream)`

- `Boolean PreprocessText(TextAsset, Stream, ITableDataType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class BsonNetConverter : IConverter
{
	private JsonSerializerSettings m_settings; // 0x10
	private Formatting m_format; // 0x18
	private JsonSerializer m_serializer; // 0x20

	protected virtual JsonSerializerSettings serializerSetting { get; }
	protected JsonSerializer serializer { get; }

	// RVA: 0x37160f8 VA: 0x7595d2e0f8
	protected virtual JsonSerializerSettings get_serializerSetting() { }
	// RVA: 0x3716100 VA: 0x7595d2e100
	protected JsonSerializer get_serializer() { }
	// RVA: 0x371609c VA: 0x7595d2e09c
	public Void .ctor(Formatting format) { }
	// RVA: 0x37163b0 VA: 0x7595d2e3b0
	public virtual Void Serialize(Object value, Stream stream) { }
	// RVA: 0x VA: 0x0
	public T Deserialize(Stream stream) { }
	// RVA: 0x VA: 0x0
	protected virtual T DeserializeInternal(Stream stream) { }
	// RVA: 0x VA: 0x0
	public T Deserialize(ConverterInput text) { }
	// RVA: 0x37166c4 VA: 0x7595d2e6c4
	public Object Deserialize(Stream stream) { }
	// RVA: 0x3716744 VA: 0x7595d2e744
	public Object Deserialize(ConverterInput text) { }
	// RVA: 0x37168e0 VA: 0x7595d2e8e0
	public Void Populate(Stream stream, Object target) { }
	// RVA: 0x3716a84 VA: 0x7595d2ea84
	public Void Populate(TextAsset text, Object target) { }
	// RVA: 0x3716c34 VA: 0x7595d2ec34
	public Void SerializeBytes(Byte[] bytes, Stream stream) { }
	// RVA: 0x3716e84 VA: 0x7595d2ee84
	private JContainer _DeserializePlainJSON(Stream input) { }
	// RVA: 0x37171a4 VA: 0x7595d2f1a4
	public Byte[] DeserializeBytes(Stream stream) { }
	// RVA: 0x3717378 VA: 0x7595d2f378
	public Boolean PreprocessText(TextAsset textAsset, Stream outStream, ITableDataType table) { }
	// RVA: 0x3717380 VA: 0x7595d2f380
	protected virtual Void ProcessStreamAfterSerialize(Stream inStream, Stream outStream) { }
}
```