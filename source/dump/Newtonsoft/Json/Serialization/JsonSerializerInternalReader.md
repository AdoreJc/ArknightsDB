# JsonSerializerInternalReader

**Namespace:** `Newtonsoft.Json.Serialization`


## Methods

- `Void Populate(JsonReader, Object)`

- `JsonContract GetContractSafe(Type)`

- `Object Deserialize(JsonReader, Type, Boolean)`

- `JsonSerializerProxy GetInternalSerializer()`

- `JToken CreateJToken(JsonReader, JsonContract)`

- `JToken CreateJObject(JsonReader)`

- `Object CreateValueInternal(JsonReader, Type, JsonContract, JsonProperty, JsonContainerContract, JsonProperty, Object)`

- `JsonConverter GetConverter(JsonContract, JsonConverter, JsonContainerContract, JsonProperty)`

- `Object CreateObject(JsonReader, Type, JsonContract, JsonProperty, JsonContainerContract, JsonProperty, Object)`

- `Boolean ReadMetadataPropertiesToken(JTokenReader, ref, ref, JsonProperty, JsonContainerContract, JsonProperty, Object, out, out)`

- `Boolean ReadMetadataProperties(JsonReader, ref, ref, JsonProperty, JsonContainerContract, JsonProperty, Object, out, out)`

- `Void ResolveTypeName(JsonReader, ref, ref, JsonProperty, JsonContainerContract, JsonProperty, String)`

- `JsonArrayContract EnsureArrayContract(JsonReader, Type, JsonContract)`

- `Object CreateList(JsonReader, Type, JsonContract, JsonProperty, Object, String)`

- `Boolean HasNoDefinedType(JsonContract)`

- `Object EnsureType(JsonReader, Object, CultureInfo, JsonContract, Type)`

- `Boolean SetPropertyValue(JsonProperty, JsonConverter, JsonContainerContract, JsonProperty, JsonReader, Object)`

- `Boolean CalculatePropertyDetails(JsonProperty, ref, JsonContainerContract, JsonProperty, JsonReader, Object, out, out, out, out)`

- `Void AddReference(JsonReader, String, Object)`

- `Boolean HasFlag(DefaultValueHandling, DefaultValueHandling)`

- `Boolean ShouldSetPropertyValue(JsonProperty, Object)`

- `IList CreateNewList(JsonReader, JsonArrayContract, out)`

- `IDictionary CreateNewDictionary(JsonReader, JsonDictionaryContract, out)`

- `Void OnDeserializing(JsonReader, JsonContract, Object)`

- `Void OnDeserialized(JsonReader, JsonContract, Object)`

- `Object PopulateDictionary(IDictionary, JsonReader, JsonDictionaryContract, JsonProperty, String)`

- `Object PopulateMultidimensionalArray(IList, JsonReader, JsonArrayContract, JsonProperty, String)`

- `Void ThrowUnexpectedEndException(JsonReader, JsonContract, Object, String)`

- `Object PopulateList(IList, JsonReader, JsonArrayContract, JsonProperty, String)`

- `Object CreateISerializable(JsonReader, JsonISerializableContract, JsonProperty, String)`

- `Object CreateObjectUsingCreatorWithParameters(JsonReader, JsonObjectContract, JsonProperty, ObjectConstructor`1, String)`

- `Object DeserializeConvertable(JsonConverter, JsonReader, Type, Object)`

- `Boolean ReadForType(JsonReader, JsonContract, Boolean)`

- `Object CreateNewObject(JsonReader, JsonObjectContract, JsonProperty, JsonProperty, String, out)`

- `Object PopulateObject(Object, JsonReader, JsonObjectContract, JsonProperty, String)`

- `Boolean ShouldDeserialize(JsonReader, JsonProperty, Object)`

- `Boolean CheckPropertyName(JsonReader, String)`

- `Void SetExtensionData(JsonObjectContract, JsonProperty, JsonReader, String, Object)`

- `Object ReadExtensionDataValue(JsonObjectContract, JsonProperty, JsonReader)`

- `Void EndProcessProperty(Object, JsonReader, JsonObjectContract, Int32, JsonProperty, PropertyPresence, Boolean)`

- `Void SetPropertyPresence(JsonReader, JsonProperty, Dictionary`2)`

- `Void HandleError(JsonReader, Boolean, Int32)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class JsonSerializerInternalReader : JsonSerializerInternalBase
{


	// RVA: 0x6174ae0 VA: 0x759878cae0
	public Void .ctor(JsonSerializer serializer) { }
	// RVA: 0x6174ae4 VA: 0x759878cae4
	public Void Populate(JsonReader reader, Object target) { }
	// RVA: 0x6176860 VA: 0x759878e860
	private JsonContract GetContractSafe(Type type) { }
	// RVA: 0x6176924 VA: 0x759878e924
	public Object Deserialize(JsonReader reader, Type objectType, Boolean checkAdditionalContent) { }
	// RVA: 0x61777a0 VA: 0x759878f7a0
	private JsonSerializerProxy GetInternalSerializer() { }
	// RVA: 0x61778a8 VA: 0x759878f8a8
	private JToken CreateJToken(JsonReader reader, JsonContract contract) { }
	// RVA: 0x6177b88 VA: 0x759878fb88
	private JToken CreateJObject(JsonReader reader) { }
	// RVA: 0x61772a0 VA: 0x759878f2a0
	private Object CreateValueInternal(JsonReader reader, Type objectType, JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerMember, Object existingValue) { }
	// RVA: 0x61794d4 VA: 0x75987914d4
	private static Boolean CoerceEmptyStringToNull(Type objectType, JsonContract contract, String s) { }
	// RVA: 0x61795d8 VA: 0x75987915d8
	internal String GetExpectedDescription(JsonContract contract) { }
	// RVA: 0x6176c6c VA: 0x759878ec6c
	private JsonConverter GetConverter(JsonContract contract, JsonConverter memberConverter, JsonContainerContract containerContract, JsonProperty containerProperty) { }
	// RVA: 0x6177fe4 VA: 0x759878ffe4
	private Object CreateObject(JsonReader reader, Type objectType, JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerMember, Object existingValue) { }
	// RVA: 0x61796a4 VA: 0x75987916a4
	private Boolean ReadMetadataPropertiesToken(JTokenReader reader, ref Type objectType, ref JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerMember, Object existingValue, out Object newValue, out String id) { }
	// RVA: 0x6179dfc VA: 0x7598791dfc
	private Boolean ReadMetadataProperties(JsonReader reader, ref Type objectType, ref JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerMember, Object existingValue, out Object newValue, out String id) { }
	// RVA: 0x617af7c VA: 0x7598792f7c
	private Void ResolveTypeName(JsonReader reader, ref Type objectType, ref JsonContract contract, JsonProperty member, JsonContainerContract containerContract, JsonProperty containerMember, String qualifiedTypeName) { }
	// RVA: 0x617b494 VA: 0x7598793494
	private JsonArrayContract EnsureArrayContract(JsonReader reader, Type objectType, JsonContract contract) { }
	// RVA: 0x6178aa4 VA: 0x7598790aa4
	private Object CreateList(JsonReader reader, Type objectType, JsonContract contract, JsonProperty member, Object existingValue, String id) { }
	// RVA: 0x617a4b8 VA: 0x75987924b8
	private Boolean HasNoDefinedType(JsonContract contract) { }
	// RVA: 0x6179140 VA: 0x7598791140
	private Object EnsureType(JsonReader reader, Object value, CultureInfo culture, JsonContract contract, Type targetType) { }
	// RVA: 0x617bf20 VA: 0x7598793f20
	private Boolean SetPropertyValue(JsonProperty property, JsonConverter propertyConverter, JsonContainerContract containerContract, JsonProperty containerProperty, JsonReader reader, Object target) { }
	// RVA: 0x617c394 VA: 0x7598794394
	private Boolean CalculatePropertyDetails(JsonProperty property, ref JsonConverter propertyConverter, JsonContainerContract containerContract, JsonProperty containerProperty, JsonReader reader, Object target, out Boolean useExistingValue, out Object currentValue, out JsonContract propertyContract, out Boolean gottenCurrentValue) { }
	// RVA: 0x617c868 VA: 0x7598794868
	private Void AddReference(JsonReader reader, String id, Object value) { }
	// RVA: 0x617c85c VA: 0x759879485c
	private Boolean HasFlag(DefaultValueHandling value, DefaultValueHandling flag) { }
	// RVA: 0x617c73c VA: 0x759879473c
	private Boolean ShouldSetPropertyValue(JsonProperty property, Object value) { }
	// RVA: 0x617b614 VA: 0x7598793614
	private IList CreateNewList(JsonReader reader, JsonArrayContract contract, out Boolean createdFromNonDefaultCreator) { }
	// RVA: 0x617a738 VA: 0x7598792738
	private IDictionary CreateNewDictionary(JsonReader reader, JsonDictionaryContract contract, out Boolean createdFromNonDefaultCreator) { }
	// RVA: 0x617cc2c VA: 0x7598794c2c
	private Void OnDeserializing(JsonReader reader, JsonContract contract, Object value) { }
	// RVA: 0x617ce58 VA: 0x7598794e58
	private Void OnDeserialized(JsonReader reader, JsonContract contract, Object value) { }
	// RVA: 0x6175534 VA: 0x759878d534
	private Object PopulateDictionary(IDictionary dictionary, JsonReader reader, JsonDictionaryContract contract, JsonProperty containerProperty, String id) { }
	// RVA: 0x617b87c VA: 0x759879387c
	private Object PopulateMultidimensionalArray(IList list, JsonReader reader, JsonArrayContract contract, JsonProperty containerProperty, String id) { }
	// RVA: 0x617d084 VA: 0x7598795084
	private Void ThrowUnexpectedEndException(JsonReader reader, JsonContract contract, Object currentObject, String message) { }
	// RVA: 0x617501c VA: 0x759878d01c
	private Object PopulateList(IList list, JsonReader reader, JsonArrayContract contract, JsonProperty containerProperty, String id) { }
	// RVA: 0x617a930 VA: 0x7598792930
	private Object CreateISerializable(JsonReader reader, JsonISerializableContract contract, JsonProperty member, String id) { }
	// RVA: 0x617d1b8 VA: 0x75987951b8
	internal Object CreateISerializableItem(JToken token, Type type, JsonISerializableContract contract, JsonProperty member) { }
	// RVA: 0x617d2ac VA: 0x75987952ac
	private Object CreateObjectUsingCreatorWithParameters(JsonReader reader, JsonObjectContract contract, JsonProperty containerProperty, ObjectConstructor`1 creator, String id) { }
	// RVA: 0x6176e8c VA: 0x759878ee8c
	private Object DeserializeConvertable(JsonConverter converter, JsonReader reader, Type objectType, Object existingValue) { }
	// RVA: 0x617ee9c VA: 0x7598796e9c
	private List`1 ResolvePropertyAndCreatorValues(JsonObjectContract contract, JsonProperty containerProperty, JsonReader reader, Type objectType) { }
	// RVA: 0x6176cd8 VA: 0x759878ecd8
	private Boolean ReadForType(JsonReader reader, JsonContract contract, Boolean hasConverter) { }
	// RVA: 0x617a550 VA: 0x7598792550
	public Object CreateNewObject(JsonReader reader, JsonObjectContract objectContract, JsonProperty containerMember, JsonProperty containerProperty, String id, out Boolean createdFromNonDefaultCreator) { }
	// RVA: 0x6175e0c VA: 0x759878de0c
	private Object PopulateObject(Object newObject, JsonReader reader, JsonObjectContract contract, JsonProperty member, String id) { }
	// RVA: 0x617fbe8 VA: 0x7598797be8
	private Boolean ShouldDeserialize(JsonReader reader, JsonProperty property, Object target) { }
	// RVA: 0x6177ec8 VA: 0x759878fec8
	private Boolean CheckPropertyName(JsonReader reader, String memberName) { }
	// RVA: 0x617fa74 VA: 0x7598797a74
	private Void SetExtensionData(JsonObjectContract contract, JsonProperty member, JsonReader reader, String memberName, Object o) { }
	// RVA: 0x617f9b8 VA: 0x75987979b8
	private Object ReadExtensionDataValue(JsonObjectContract contract, JsonProperty member, JsonReader reader) { }
	// RVA: 0x617f508 VA: 0x7598797508
	private Void EndProcessProperty(Object newObject, JsonReader reader, JsonObjectContract contract, Int32 initialDepth, JsonProperty property, PropertyPresence presence, Boolean setDefaultValue) { }
	// RVA: 0x617fe5c VA: 0x7598797e5c
	private Void SetPropertyPresence(JsonReader reader, JsonProperty property, Dictionary`2 requiredProperties) { }
	// RVA: 0x6177734 VA: 0x759878f734
	private Void HandleError(JsonReader reader, Boolean readPastError, Int32 initialDepth) { }
}
```