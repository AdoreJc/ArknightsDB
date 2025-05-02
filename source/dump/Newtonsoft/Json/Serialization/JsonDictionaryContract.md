# JsonDictionaryContract

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Type <DictionaryKeyType>k__BackingField`

- `Type <DictionaryValueType>k__BackingField`

- `JsonContract <KeyContract>k__BackingField`

- `Type _genericWrapperType`

- `Boolean <ShouldCreateWrapper>k__BackingField`

- `Boolean <HasParameterizedCreator>k__BackingField`


## Properties

- `Type DictionaryKeyType`

- `Type DictionaryValueType`

- `Boolean HasParameterizedCreator`


## Methods

- `Void set_DictionaryKeyResolver(Func`2)`

- `Type get_DictionaryKeyType()`

- `Void set_DictionaryKeyType(Type)`

- `Type get_DictionaryValueType()`

- `Void set_DictionaryValueType(Type)`

- `Void set_ShouldCreateWrapper(Boolean)`

- `Void set_OverrideCreator(ObjectConstructor`1)`

- `Boolean get_HasParameterizedCreator()`

- `Void set_HasParameterizedCreator(Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonDictionaryContract : JsonContainerContract
{
	private Func`2 <DictionaryKeyResolver>k__BackingField; // 0xc0
	private Type <DictionaryKeyType>k__BackingField; // 0xc8
	private Type <DictionaryValueType>k__BackingField; // 0xd0
	private JsonContract <KeyContract>k__BackingField; // 0xd8
	private readonly Type _genericCollectionDefinitionType; // 0xe0
	private Type _genericWrapperType; // 0xe8
	private ObjectConstructor`1 _genericWrapperCreator; // 0xf0
	private Func`1 _genericTemporaryDictionaryCreator; // 0xf8
	private Boolean <ShouldCreateWrapper>k__BackingField; // 0x100
	private readonly ConstructorInfo _parameterizedConstructor; // 0x108
	private ObjectConstructor`1 _overrideCreator; // 0x110
	private ObjectConstructor`1 _parameterizedCreator; // 0x118
	private Boolean <HasParameterizedCreator>k__BackingField; // 0x120

	public Func`2 DictionaryKeyResolver { get; set; }
	public Type DictionaryKeyType { get; set; }
	public Type DictionaryValueType { get; set; }
	internal JsonContract KeyContract { get; set; }
	internal Boolean ShouldCreateWrapper { get; set; }
	internal ObjectConstructor`1 ParameterizedCreator { get; }
	public ObjectConstructor`1 OverrideCreator { get; set; }
	public Boolean HasParameterizedCreator { get; set; }
	internal Boolean HasParameterizedCreatorInternal { get; }

	// RVA: 0x617234c VA: 0x759878a34c
	public Func`2 get_DictionaryKeyResolver() { }
	// RVA: 0x6172354 VA: 0x759878a354
	public Void set_DictionaryKeyResolver(Func`2 value) { }
	// RVA: 0x617235c VA: 0x759878a35c
	public Type get_DictionaryKeyType() { }
	// RVA: 0x6172364 VA: 0x759878a364
	private Void set_DictionaryKeyType(Type value) { }
	// RVA: 0x617236c VA: 0x759878a36c
	public Type get_DictionaryValueType() { }
	// RVA: 0x6172374 VA: 0x759878a374
	private Void set_DictionaryValueType(Type value) { }
	// RVA: 0x617237c VA: 0x759878a37c
	internal JsonContract get_KeyContract() { }
	// RVA: 0x6172384 VA: 0x759878a384
	internal Void set_KeyContract(JsonContract value) { }
	// RVA: 0x617238c VA: 0x759878a38c
	internal Boolean get_ShouldCreateWrapper() { }
	// RVA: 0x6172394 VA: 0x759878a394
	private Void set_ShouldCreateWrapper(Boolean value) { }
	// RVA: 0x61723a0 VA: 0x759878a3a0
	internal ObjectConstructor`1 get_ParameterizedCreator() { }
	// RVA: 0x617242c VA: 0x759878a42c
	public ObjectConstructor`1 get_OverrideCreator() { }
	// RVA: 0x6172434 VA: 0x759878a434
	public Void set_OverrideCreator(ObjectConstructor`1 value) { }
	// RVA: 0x6172444 VA: 0x759878a444
	public Boolean get_HasParameterizedCreator() { }
	// RVA: 0x617244c VA: 0x759878a44c
	public Void set_HasParameterizedCreator(Boolean value) { }
	// RVA: 0x6172458 VA: 0x759878a458
	internal Boolean get_HasParameterizedCreatorInternal() { }
	// RVA: 0x6172480 VA: 0x759878a480
	public Void .ctor(Type underlyingType) { }
	// RVA: 0x6172a8c VA: 0x759878aa8c
	internal IWrappedDictionary CreateWrapper(Object dictionary) { }
	// RVA: 0x6172d5c VA: 0x759878ad5c
	internal IDictionary CreateTemporaryDictionary() { }
}
```