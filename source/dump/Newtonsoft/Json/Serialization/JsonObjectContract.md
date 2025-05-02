# JsonObjectContract

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `MemberSerialization <MemberSerialization>k__BackingField`

- `JsonPropertyCollection <Properties>k__BackingField`

- `ExtensionDataSetter <ExtensionDataSetter>k__BackingField`

- `ExtensionDataGetter <ExtensionDataGetter>k__BackingField`

- `ConstructorInfo _parametrizedConstructor`

- `ConstructorInfo _overrideConstructor`

- `JsonPropertyCollection _creatorParameters`

- `Type _extensionDataValueType`


## Properties

- `MemberSerialization MemberSerialization`

- `JsonPropertyCollection Properties`

- `JsonPropertyCollection CreatorParameters`

- `ConstructorInfo OverrideConstructor`

- `ConstructorInfo ParametrizedConstructor`

- `ExtensionDataSetter ExtensionDataSetter`

- `ExtensionDataGetter ExtensionDataGetter`

- `Type ExtensionDataValueType`


## Methods

- `MemberSerialization get_MemberSerialization()`

- `Void set_MemberSerialization(MemberSerialization)`

- `Void set_ItemRequired(Nullable`1)`

- `JsonPropertyCollection get_Properties()`

- `Void set_Properties(JsonPropertyCollection)`

- `JsonPropertyCollection get_CreatorParameters()`

- `Void set_OverrideConstructor(ConstructorInfo)`

- `Void set_ParametrizedConstructor(ConstructorInfo)`

- `ExtensionDataSetter get_ExtensionDataSetter()`

- `Void set_ExtensionDataSetter(ExtensionDataSetter)`

- `ExtensionDataGetter get_ExtensionDataGetter()`

- `Void set_ExtensionDataGetter(ExtensionDataGetter)`

- `Void set_ExtensionDataValueType(Type)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonObjectContract : JsonContainerContract
{
	private MemberSerialization <MemberSerialization>k__BackingField; // 0xbc
	private Nullable`1 <ItemRequired>k__BackingField; // 0xc0
	private JsonPropertyCollection <Properties>k__BackingField; // 0xc8
	private ExtensionDataSetter <ExtensionDataSetter>k__BackingField; // 0xd0
	private ExtensionDataGetter <ExtensionDataGetter>k__BackingField; // 0xd8
	internal Boolean ExtensionDataIsJToken; // 0xe0
	private Nullable`1 _hasRequiredOrDefaultValueProperties; // 0xe1
	private ConstructorInfo _parametrizedConstructor; // 0xe8
	private ConstructorInfo _overrideConstructor; // 0xf0
	private ObjectConstructor`1 _overrideCreator; // 0xf8
	private ObjectConstructor`1 _parameterizedCreator; // 0x100
	private JsonPropertyCollection _creatorParameters; // 0x108
	private Type _extensionDataValueType; // 0x110

	public MemberSerialization MemberSerialization { get; set; }
	public Nullable`1 ItemRequired { get; set; }
	public JsonPropertyCollection Properties { get; set; }
	public JsonPropertyCollection CreatorParameters { get; }
	public ConstructorInfo OverrideConstructor { set; }
	public ConstructorInfo ParametrizedConstructor { set; }
	public ObjectConstructor`1 OverrideCreator { get; }
	internal ObjectConstructor`1 ParameterizedCreator { get; }
	public ExtensionDataSetter ExtensionDataSetter { get; set; }
	public ExtensionDataGetter ExtensionDataGetter { get; set; }
	public Type ExtensionDataValueType { set; }
	internal Boolean HasRequiredOrDefaultValueProperties { get; }

	// RVA: 0x61739c4 VA: 0x759878b9c4
	public MemberSerialization get_MemberSerialization() { }
	// RVA: 0x61739cc VA: 0x759878b9cc
	public Void set_MemberSerialization(MemberSerialization value) { }
	// RVA: 0x61739d4 VA: 0x759878b9d4
	public Nullable`1 get_ItemRequired() { }
	// RVA: 0x61739dc VA: 0x759878b9dc
	public Void set_ItemRequired(Nullable`1 value) { }
	// RVA: 0x61739e4 VA: 0x759878b9e4
	public JsonPropertyCollection get_Properties() { }
	// RVA: 0x61739ec VA: 0x759878b9ec
	private Void set_Properties(JsonPropertyCollection value) { }
	// RVA: 0x61739f4 VA: 0x759878b9f4
	public JsonPropertyCollection get_CreatorParameters() { }
	// RVA: 0x6173a74 VA: 0x759878ba74
	public Void set_OverrideConstructor(ConstructorInfo value) { }
	// RVA: 0x6173b0c VA: 0x759878bb0c
	public Void set_ParametrizedConstructor(ConstructorInfo value) { }
	// RVA: 0x6173ba4 VA: 0x759878bba4
	public ObjectConstructor`1 get_OverrideCreator() { }
	// RVA: 0x6173bac VA: 0x759878bbac
	internal ObjectConstructor`1 get_ParameterizedCreator() { }
	// RVA: 0x6173bb4 VA: 0x759878bbb4
	public ExtensionDataSetter get_ExtensionDataSetter() { }
	// RVA: 0x6173bbc VA: 0x759878bbbc
	public Void set_ExtensionDataSetter(ExtensionDataSetter value) { }
	// RVA: 0x6173bc4 VA: 0x759878bbc4
	public ExtensionDataGetter get_ExtensionDataGetter() { }
	// RVA: 0x6173bcc VA: 0x759878bbcc
	public Void set_ExtensionDataGetter(ExtensionDataGetter value) { }
	// RVA: 0x6173bd4 VA: 0x759878bbd4
	public Void set_ExtensionDataValueType(Type value) { }
	// RVA: 0x6173c8c VA: 0x759878bc8c
	internal Boolean get_HasRequiredOrDefaultValueProperties() { }
	// RVA: 0x6174080 VA: 0x759878c080
	public Void .ctor(Type underlyingType) { }
	// RVA: 0x6174110 VA: 0x759878c110
	internal Object GetUninitializedObject() { }
}
```