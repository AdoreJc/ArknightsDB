# JsonArrayContract

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Type <CollectionItemType>k__BackingField`

- `Boolean <IsMultidimensionalArray>k__BackingField`

- `Type _genericWrapperType`

- `Boolean <IsArray>k__BackingField`

- `Boolean <ShouldCreateWrapper>k__BackingField`

- `Boolean <CanDeserialize>k__BackingField`

- `Boolean <HasParameterizedCreator>k__BackingField`


## Properties

- `Type CollectionItemType`

- `Boolean IsMultidimensionalArray`

- `Boolean HasParameterizedCreator`


## Methods

- `Type get_CollectionItemType()`

- `Void set_CollectionItemType(Type)`

- `Boolean get_IsMultidimensionalArray()`

- `Void set_IsMultidimensionalArray(Boolean)`

- `Void set_IsArray(Boolean)`

- `Void set_ShouldCreateWrapper(Boolean)`

- `Void set_CanDeserialize(Boolean)`

- `Void set_OverrideCreator(ObjectConstructor`1)`

- `Boolean get_HasParameterizedCreator()`

- `Void set_HasParameterizedCreator(Boolean)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonArrayContract : JsonContainerContract
{
	private Type <CollectionItemType>k__BackingField; // 0xc0
	private Boolean <IsMultidimensionalArray>k__BackingField; // 0xc8
	private readonly Type _genericCollectionDefinitionType; // 0xd0
	private Type _genericWrapperType; // 0xd8
	private ObjectConstructor`1 _genericWrapperCreator; // 0xe0
	private Func`1 _genericTemporaryCollectionCreator; // 0xe8
	private Boolean <IsArray>k__BackingField; // 0xf0
	private Boolean <ShouldCreateWrapper>k__BackingField; // 0xf1
	private Boolean <CanDeserialize>k__BackingField; // 0xf2
	private readonly ConstructorInfo _parameterizedConstructor; // 0xf8
	private ObjectConstructor`1 _parameterizedCreator; // 0x100
	private ObjectConstructor`1 _overrideCreator; // 0x108
	private Boolean <HasParameterizedCreator>k__BackingField; // 0x110

	public Type CollectionItemType { get; set; }
	public Boolean IsMultidimensionalArray { get; set; }
	internal Boolean IsArray { get; set; }
	internal Boolean ShouldCreateWrapper { get; set; }
	internal Boolean CanDeserialize { get; set; }
	internal ObjectConstructor`1 ParameterizedCreator { get; }
	public ObjectConstructor`1 OverrideCreator { get; set; }
	public Boolean HasParameterizedCreator { get; set; }
	internal Boolean HasParameterizedCreatorInternal { get; }

	// RVA: 0x616f658 VA: 0x7598787658
	public Type get_CollectionItemType() { }
	// RVA: 0x616f660 VA: 0x7598787660
	private Void set_CollectionItemType(Type value) { }
	// RVA: 0x616f668 VA: 0x7598787668
	public Boolean get_IsMultidimensionalArray() { }
	// RVA: 0x616f670 VA: 0x7598787670
	private Void set_IsMultidimensionalArray(Boolean value) { }
	// RVA: 0x616f67c VA: 0x759878767c
	internal Boolean get_IsArray() { }
	// RVA: 0x616f684 VA: 0x7598787684
	private Void set_IsArray(Boolean value) { }
	// RVA: 0x616f690 VA: 0x7598787690
	internal Boolean get_ShouldCreateWrapper() { }
	// RVA: 0x616f698 VA: 0x7598787698
	private Void set_ShouldCreateWrapper(Boolean value) { }
	// RVA: 0x616f6a4 VA: 0x75987876a4
	internal Boolean get_CanDeserialize() { }
	// RVA: 0x616f6ac VA: 0x75987876ac
	private Void set_CanDeserialize(Boolean value) { }
	// RVA: 0x616f6b8 VA: 0x75987876b8
	internal ObjectConstructor`1 get_ParameterizedCreator() { }
	// RVA: 0x616f7cc VA: 0x75987877cc
	public ObjectConstructor`1 get_OverrideCreator() { }
	// RVA: 0x616f7d4 VA: 0x75987877d4
	public Void set_OverrideCreator(ObjectConstructor`1 value) { }
	// RVA: 0x616f7f8 VA: 0x75987877f8
	public Boolean get_HasParameterizedCreator() { }
	// RVA: 0x616f800 VA: 0x7598787800
	public Void set_HasParameterizedCreator(Boolean value) { }
	// RVA: 0x616f80c VA: 0x759878780c
	internal Boolean get_HasParameterizedCreatorInternal() { }
	// RVA: 0x616f834 VA: 0x7598787834
	public Void .ctor(Type underlyingType) { }
	// RVA: 0x61701f4 VA: 0x75987881f4
	internal IWrappedCollection CreateWrapper(Object list) { }
	// RVA: 0x6170600 VA: 0x7598788600
	internal IList CreateTemporaryCollection() { }
}
```