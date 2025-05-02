# JsonSerializerInternalWriter

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Type _rootType`

- `Int32 _rootLevel`


## Methods

- `Void Serialize(JsonWriter, Object, Type)`

- `JsonSerializerProxy GetInternalSerializer()`

- `JsonContract GetContractSafe(Object)`

- `Void SerializePrimitive(JsonWriter, Object, JsonPrimitiveContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void SerializeValue(JsonWriter, Object, JsonContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Boolean ShouldWriteReference(Object, JsonProperty, JsonContract, JsonContainerContract, JsonProperty)`

- `Boolean ShouldWriteProperty(Object, JsonProperty)`

- `Boolean CheckForCircularReference(JsonWriter, Object, JsonProperty, JsonContract, JsonContainerContract, JsonProperty)`

- `Void WriteReference(JsonWriter, Object)`

- `String GetReference(JsonWriter, Object)`

- `Void SerializeString(JsonWriter, Object, JsonStringContract)`

- `Void OnSerializing(JsonWriter, JsonContract, Object)`

- `Void OnSerialized(JsonWriter, JsonContract, Object)`

- `Void SerializeObject(JsonWriter, Object, JsonObjectContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Boolean CalculatePropertyValues(JsonWriter, Object, JsonContainerContract, JsonProperty, JsonProperty, out, out)`

- `Void WriteObjectStart(JsonWriter, Object, JsonContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void WriteReferenceIdProperty(JsonWriter, Type, Object)`

- `Void WriteTypeProperty(JsonWriter, Type)`

- `Boolean HasFlag(DefaultValueHandling, DefaultValueHandling)`

- `Boolean HasFlag(PreserveReferencesHandling, PreserveReferencesHandling)`

- `Boolean HasFlag(TypeNameHandling, TypeNameHandling)`

- `Void SerializeConvertable(JsonWriter, JsonConverter, Object, JsonContract, JsonContainerContract, JsonProperty)`

- `Void SerializeList(JsonWriter, IEnumerable, JsonArrayContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void SerializeMultidimensionalArray(JsonWriter, Array, JsonArrayContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void SerializeMultidimensionalArray(JsonWriter, Array, JsonArrayContract, JsonProperty, Int32, Int32[])`

- `Boolean WriteStartArray(JsonWriter, Object, JsonArrayContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void SerializeISerializable(JsonWriter, ISerializable, JsonISerializableContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Boolean ShouldWriteType(TypeNameHandling, JsonContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `Void SerializeDictionary(JsonWriter, IDictionary, JsonDictionaryContract, JsonProperty, JsonContainerContract, JsonProperty)`

- `String GetPropertyName(JsonWriter, Object, JsonContract, out)`

- `Void HandleError(JsonWriter, Int32)`

- `Boolean ShouldSerialize(JsonWriter, JsonProperty, Object)`

- `Boolean IsSpecified(JsonWriter, JsonProperty, Object)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class JsonSerializerInternalWriter : JsonSerializerInternalBase
{
	private Type _rootType; // 0x38
	private Int32 _rootLevel; // 0x40
	private readonly List`1 _serializeStack; // 0x48


	// RVA: 0x6180048 VA: 0x7598798048
	public Void .ctor(JsonSerializer serializer) { }
	// RVA: 0x61800dc VA: 0x75987980dc
	public Void Serialize(JsonWriter jsonWriter, Object value, Type objectType) { }
	// RVA: 0x6180ec0 VA: 0x7598798ec0
	private JsonSerializerProxy GetInternalSerializer() { }
	// RVA: 0x6180380 VA: 0x7598798380
	private JsonContract GetContractSafe(Object value) { }
	// RVA: 0x6180fc8 VA: 0x7598798fc8
	private Void SerializePrimitive(JsonWriter writer, Object value, JsonPrimitiveContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x6180870 VA: 0x7598798870
	private Void SerializeValue(JsonWriter writer, Object value, JsonContract valueContract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x6183820 VA: 0x759879b820
	private Nullable`1 ResolveIsReference(JsonContract contract, JsonProperty property, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x6180454 VA: 0x7598798454
	private Boolean ShouldWriteReference(Object value, JsonProperty property, JsonContract valueContract, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x61838dc VA: 0x759879b8dc
	private Boolean ShouldWriteProperty(Object memberValue, JsonProperty property) { }
	// RVA: 0x61839dc VA: 0x759879b9dc
	private Boolean CheckForCircularReference(JsonWriter writer, Object value, JsonProperty property, JsonContract contract, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x61805ec VA: 0x75987985ec
	private Void WriteReference(JsonWriter writer, Object value) { }
	// RVA: 0x6183f38 VA: 0x759879bf38
	private String GetReference(JsonWriter writer, Object value) { }
	// RVA: 0x6184124 VA: 0x759879c124
	internal static Boolean TryConvertToString(Object value, Type type, out String s) { }
	// RVA: 0x6182a9c VA: 0x759879aa9c
	private Void SerializeString(JsonWriter writer, Object value, JsonStringContract contract) { }
	// RVA: 0x618430c VA: 0x759879c30c
	private Void OnSerializing(JsonWriter writer, JsonContract contract, Object value) { }
	// RVA: 0x6184510 VA: 0x759879c510
	private Void OnSerialized(JsonWriter writer, JsonContract contract, Object value) { }
	// RVA: 0x6181ab0 VA: 0x7598799ab0
	private Void SerializeObject(JsonWriter writer, Object value, JsonObjectContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x6184848 VA: 0x759879c848
	private Boolean CalculatePropertyValues(JsonWriter writer, Object value, JsonContainerContract contract, JsonProperty member, JsonProperty property, out JsonContract memberContract, out Object memberValue) { }
	// RVA: 0x6184714 VA: 0x759879c714
	private Void WriteObjectStart(JsonWriter writer, Object value, JsonContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x61854b0 VA: 0x759879d4b0
	private Void WriteReferenceIdProperty(JsonWriter writer, Type type, Object value) { }
	// RVA: 0x61812f8 VA: 0x75987992f8
	private Void WriteTypeProperty(JsonWriter writer, Type type) { }
	// RVA: 0x61839d0 VA: 0x759879b9d0
	private Boolean HasFlag(DefaultValueHandling value, DefaultValueHandling flag) { }
	// RVA: 0x61838d0 VA: 0x759879b8d0
	private Boolean HasFlag(PreserveReferencesHandling value, PreserveReferencesHandling flag) { }
	// RVA: 0x6185704 VA: 0x759879d704
	private Boolean HasFlag(TypeNameHandling value, TypeNameHandling flag) { }
	// RVA: 0x6181580 VA: 0x7598799580
	private Void SerializeConvertable(JsonWriter writer, JsonConverter converter, Object value, JsonContract contract, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x61821d8 VA: 0x759879a1d8
	private Void SerializeList(JsonWriter writer, IEnumerable values, JsonArrayContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x61828d4 VA: 0x759879a8d4
	private Void SerializeMultidimensionalArray(JsonWriter writer, Array values, JsonArrayContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x61859ac VA: 0x759879d9ac
	private Void SerializeMultidimensionalArray(JsonWriter writer, Array values, JsonArrayContract contract, JsonProperty member, Int32 initialDepth, Int32[] indices) { }
	// RVA: 0x6185710 VA: 0x759879d710
	private Boolean WriteStartArray(JsonWriter writer, Object values, JsonArrayContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x61833b0 VA: 0x759879b3b0
	private Void SerializeISerializable(JsonWriter writer, ISerializable value, JsonISerializableContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x6181130 VA: 0x7598799130
	private Boolean ShouldWriteType(TypeNameHandling typeNameHandlingFlag, JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x6182b20 VA: 0x759879ab20
	private Void SerializeDictionary(JsonWriter writer, IDictionary values, JsonDictionaryContract contract, JsonProperty member, JsonContainerContract collectionContract, JsonProperty containerProperty) { }
	// RVA: 0x6184c70 VA: 0x759879cc70
	private String GetPropertyName(JsonWriter writer, Object name, JsonContract contract, out Boolean escape) { }
	// RVA: 0x6180e4c VA: 0x7598798e4c
	private Void HandleError(JsonWriter writer, Int32 initialDepth) { }
	// RVA: 0x6184fd0 VA: 0x759879cfd0
	private Boolean ShouldSerialize(JsonWriter writer, JsonProperty property, Object target) { }
	// RVA: 0x6185240 VA: 0x759879d240
	private Boolean IsSpecified(JsonWriter writer, JsonProperty property, Object target) { }
}
```