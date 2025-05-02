# JsonProperty

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Object _defaultValue`

- `Boolean _hasGeneratedDefaultValue`

- `String _propertyName`

- `Type _propertyType`

- `JsonContract <PropertyContract>k__BackingField`

- `Type <DeclaringType>k__BackingField`

- `String <UnderlyingName>k__BackingField`

- `IValueProvider <ValueProvider>k__BackingField`

- `IAttributeProvider <AttributeProvider>k__BackingField`

- `JsonConverter <Converter>k__BackingField`

- `JsonConverter <MemberConverter>k__BackingField`

- `Boolean <Ignored>k__BackingField`

- `Boolean <Readable>k__BackingField`

- `Boolean <Writable>k__BackingField`

- `Boolean <HasMemberAttribute>k__BackingField`

- `JsonConverter <ItemConverter>k__BackingField`


## Properties

- `String PropertyName`

- `Type DeclaringType`

- `String UnderlyingName`

- `IValueProvider ValueProvider`

- `IAttributeProvider AttributeProvider`

- `Type PropertyType`

- `JsonConverter Converter`

- `JsonConverter MemberConverter`

- `Boolean Ignored`

- `Boolean Readable`

- `Boolean Writable`

- `Boolean HasMemberAttribute`

- `Object DefaultValue`

- `Required Required`

- `JsonConverter ItemConverter`


## Methods

- `String get_PropertyName()`

- `Void set_PropertyName(String)`

- `Type get_DeclaringType()`

- `Void set_DeclaringType(Type)`

- `Void set_Order(Nullable`1)`

- `String get_UnderlyingName()`

- `Void set_UnderlyingName(String)`

- `IValueProvider get_ValueProvider()`

- `Void set_ValueProvider(IValueProvider)`

- `Void set_AttributeProvider(IAttributeProvider)`

- `Type get_PropertyType()`

- `Void set_PropertyType(Type)`

- `JsonConverter get_Converter()`

- `Void set_Converter(JsonConverter)`

- `JsonConverter get_MemberConverter()`

- `Void set_MemberConverter(JsonConverter)`

- `Boolean get_Ignored()`

- `Void set_Ignored(Boolean)`

- `Boolean get_Readable()`

- `Void set_Readable(Boolean)`

- `Boolean get_Writable()`

- `Void set_Writable(Boolean)`

- `Boolean get_HasMemberAttribute()`

- `Void set_HasMemberAttribute(Boolean)`

- `Object get_DefaultValue()`

- `Void set_DefaultValue(Object)`

- `Required get_Required()`

- `Void set_IsReference(Nullable`1)`

- `Void set_NullValueHandling(Nullable`1)`

- `Void set_DefaultValueHandling(Nullable`1)`

- `Void set_ReferenceLoopHandling(Nullable`1)`

- `Void set_ObjectCreationHandling(Nullable`1)`

- `Void set_TypeNameHandling(Nullable`1)`

- `Void set_ShouldSerialize(Predicate`1)`

- `Void set_GetIsSpecified(Predicate`1)`

- `Void set_SetIsSpecified(Action`2)`

- `JsonConverter get_ItemConverter()`

- `Void set_ItemConverter(JsonConverter)`

- `Void set_ItemIsReference(Nullable`1)`

- `Void set_ItemTypeNameHandling(Nullable`1)`

- `Void set_ItemReferenceLoopHandling(Nullable`1)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonProperty
{
	internal Nullable`1 _required; // 0x10
	internal Boolean _hasExplicitDefaultValue; // 0x18
	private Object _defaultValue; // 0x20
	private Boolean _hasGeneratedDefaultValue; // 0x28
	private String _propertyName; // 0x30
	internal Boolean _skipPropertyNameEscape; // 0x38
	private Type _propertyType; // 0x40
	private JsonContract <PropertyContract>k__BackingField; // 0x48
	private Type <DeclaringType>k__BackingField; // 0x50
	private Nullable`1 <Order>k__BackingField; // 0x58
	private String <UnderlyingName>k__BackingField; // 0x60
	private IValueProvider <ValueProvider>k__BackingField; // 0x68
	private IAttributeProvider <AttributeProvider>k__BackingField; // 0x70
	private JsonConverter <Converter>k__BackingField; // 0x78
	private JsonConverter <MemberConverter>k__BackingField; // 0x80
	private Boolean <Ignored>k__BackingField; // 0x88
	private Boolean <Readable>k__BackingField; // 0x89
	private Boolean <Writable>k__BackingField; // 0x8a
	private Boolean <HasMemberAttribute>k__BackingField; // 0x8b
	private Nullable`1 <IsReference>k__BackingField; // 0x8c
	private Nullable`1 <NullValueHandling>k__BackingField; // 0x90
	private Nullable`1 <DefaultValueHandling>k__BackingField; // 0x98
	private Nullable`1 <ReferenceLoopHandling>k__BackingField; // 0xa0
	private Nullable`1 <ObjectCreationHandling>k__BackingField; // 0xa8
	private Nullable`1 <TypeNameHandling>k__BackingField; // 0xb0
	private Predicate`1 <ShouldSerialize>k__BackingField; // 0xb8
	private Predicate`1 <ShouldDeserialize>k__BackingField; // 0xc0
	private Predicate`1 <GetIsSpecified>k__BackingField; // 0xc8
	private Action`2 <SetIsSpecified>k__BackingField; // 0xd0
	private JsonConverter <ItemConverter>k__BackingField; // 0xd8
	private Nullable`1 <ItemIsReference>k__BackingField; // 0xe0
	private Nullable`1 <ItemTypeNameHandling>k__BackingField; // 0xe4
	private Nullable`1 <ItemReferenceLoopHandling>k__BackingField; // 0xec

	internal JsonContract PropertyContract { get; set; }
	public String PropertyName { get; set; }
	public Type DeclaringType { get; set; }
	public Nullable`1 Order { get; set; }
	public String UnderlyingName { get; set; }
	public IValueProvider ValueProvider { get; set; }
	public IAttributeProvider AttributeProvider { set; }
	public Type PropertyType { get; set; }
	public JsonConverter Converter { get; set; }
	public JsonConverter MemberConverter { get; set; }
	public Boolean Ignored { get; set; }
	public Boolean Readable { get; set; }
	public Boolean Writable { get; set; }
	public Boolean HasMemberAttribute { get; set; }
	public Object DefaultValue { get; set; }
	public Required Required { get; }
	public Nullable`1 IsReference { get; set; }
	public Nullable`1 NullValueHandling { get; set; }
	public Nullable`1 DefaultValueHandling { get; set; }
	public Nullable`1 ReferenceLoopHandling { get; set; }
	public Nullable`1 ObjectCreationHandling { get; set; }
	public Nullable`1 TypeNameHandling { get; set; }
	public Predicate`1 ShouldSerialize { get; set; }
	public Predicate`1 ShouldDeserialize { get; }
	public Predicate`1 GetIsSpecified { get; set; }
	public Action`2 SetIsSpecified { get; set; }
	public JsonConverter ItemConverter { get; set; }
	public Nullable`1 ItemIsReference { get; set; }
	public Nullable`1 ItemTypeNameHandling { get; set; }
	public Nullable`1 ItemReferenceLoopHandling { get; set; }

	// RVA: 0x6173008 VA: 0x759878b008
	internal JsonContract get_PropertyContract() { }
	// RVA: 0x6173010 VA: 0x759878b010
	internal Void set_PropertyContract(JsonContract value) { }
	// RVA: 0x6173018 VA: 0x759878b018
	public String get_PropertyName() { }
	// RVA: 0x6173020 VA: 0x759878b020
	public Void set_PropertyName(String value) { }
	// RVA: 0x61730b8 VA: 0x759878b0b8
	public Type get_DeclaringType() { }
	// RVA: 0x61730c0 VA: 0x759878b0c0
	public Void set_DeclaringType(Type value) { }
	// RVA: 0x61730c8 VA: 0x759878b0c8
	public Nullable`1 get_Order() { }
	// RVA: 0x61730d0 VA: 0x759878b0d0
	public Void set_Order(Nullable`1 value) { }
	// RVA: 0x61730d8 VA: 0x759878b0d8
	public String get_UnderlyingName() { }
	// RVA: 0x61730e0 VA: 0x759878b0e0
	public Void set_UnderlyingName(String value) { }
	// RVA: 0x61730e8 VA: 0x759878b0e8
	public IValueProvider get_ValueProvider() { }
	// RVA: 0x61730f0 VA: 0x759878b0f0
	public Void set_ValueProvider(IValueProvider value) { }
	// RVA: 0x61730f8 VA: 0x759878b0f8
	public Void set_AttributeProvider(IAttributeProvider value) { }
	// RVA: 0x6173100 VA: 0x759878b100
	public Type get_PropertyType() { }
	// RVA: 0x6173108 VA: 0x759878b108
	public Void set_PropertyType(Type value) { }
	// RVA: 0x6173130 VA: 0x759878b130
	public JsonConverter get_Converter() { }
	// RVA: 0x6173138 VA: 0x759878b138
	public Void set_Converter(JsonConverter value) { }
	// RVA: 0x6173140 VA: 0x759878b140
	public JsonConverter get_MemberConverter() { }
	// RVA: 0x6173148 VA: 0x759878b148
	public Void set_MemberConverter(JsonConverter value) { }
	// RVA: 0x6173150 VA: 0x759878b150
	public Boolean get_Ignored() { }
	// RVA: 0x6173158 VA: 0x759878b158
	public Void set_Ignored(Boolean value) { }
	// RVA: 0x6173164 VA: 0x759878b164
	public Boolean get_Readable() { }
	// RVA: 0x617316c VA: 0x759878b16c
	public Void set_Readable(Boolean value) { }
	// RVA: 0x6173178 VA: 0x759878b178
	public Boolean get_Writable() { }
	// RVA: 0x6173180 VA: 0x759878b180
	public Void set_Writable(Boolean value) { }
	// RVA: 0x617318c VA: 0x759878b18c
	public Boolean get_HasMemberAttribute() { }
	// RVA: 0x6173194 VA: 0x759878b194
	public Void set_HasMemberAttribute(Boolean value) { }
	// RVA: 0x61731a0 VA: 0x759878b1a0
	public Object get_DefaultValue() { }
	// RVA: 0x61731b8 VA: 0x759878b1b8
	public Void set_DefaultValue(Object value) { }
	// RVA: 0x61731c8 VA: 0x759878b1c8
	internal Object GetResolvedDefaultValue() { }
	// RVA: 0x6173264 VA: 0x759878b264
	public Required get_Required() { }
	// RVA: 0x61732b4 VA: 0x759878b2b4
	public Nullable`1 get_IsReference() { }
	// RVA: 0x61732bc VA: 0x759878b2bc
	public Void set_IsReference(Nullable`1 value) { }
	// RVA: 0x61732c4 VA: 0x759878b2c4
	public Nullable`1 get_NullValueHandling() { }
	// RVA: 0x61732cc VA: 0x759878b2cc
	public Void set_NullValueHandling(Nullable`1 value) { }
	// RVA: 0x61732d4 VA: 0x759878b2d4
	public Nullable`1 get_DefaultValueHandling() { }
	// RVA: 0x61732dc VA: 0x759878b2dc
	public Void set_DefaultValueHandling(Nullable`1 value) { }
	// RVA: 0x61732e4 VA: 0x759878b2e4
	public Nullable`1 get_ReferenceLoopHandling() { }
	// RVA: 0x61732ec VA: 0x759878b2ec
	public Void set_ReferenceLoopHandling(Nullable`1 value) { }
	// RVA: 0x61732f4 VA: 0x759878b2f4
	public Nullable`1 get_ObjectCreationHandling() { }
	// RVA: 0x61732fc VA: 0x759878b2fc
	public Void set_ObjectCreationHandling(Nullable`1 value) { }
	// RVA: 0x6173304 VA: 0x759878b304
	public Nullable`1 get_TypeNameHandling() { }
	// RVA: 0x617330c VA: 0x759878b30c
	public Void set_TypeNameHandling(Nullable`1 value) { }
	// RVA: 0x6173314 VA: 0x759878b314
	public Predicate`1 get_ShouldSerialize() { }
	// RVA: 0x617331c VA: 0x759878b31c
	public Void set_ShouldSerialize(Predicate`1 value) { }
	// RVA: 0x6173324 VA: 0x759878b324
	public Predicate`1 get_ShouldDeserialize() { }
	// RVA: 0x617332c VA: 0x759878b32c
	public Predicate`1 get_GetIsSpecified() { }
	// RVA: 0x6173334 VA: 0x759878b334
	public Void set_GetIsSpecified(Predicate`1 value) { }
	// RVA: 0x617333c VA: 0x759878b33c
	public Action`2 get_SetIsSpecified() { }
	// RVA: 0x6173344 VA: 0x759878b344
	public Void set_SetIsSpecified(Action`2 value) { }
	// RVA: 0x617334c VA: 0x759878b34c
	public override String ToString() { }
	// RVA: 0x6173354 VA: 0x759878b354
	public JsonConverter get_ItemConverter() { }
	// RVA: 0x617335c VA: 0x759878b35c
	public Void set_ItemConverter(JsonConverter value) { }
	// RVA: 0x6173364 VA: 0x759878b364
	public Nullable`1 get_ItemIsReference() { }
	// RVA: 0x617336c VA: 0x759878b36c
	public Void set_ItemIsReference(Nullable`1 value) { }
	// RVA: 0x6173374 VA: 0x759878b374
	public Nullable`1 get_ItemTypeNameHandling() { }
	// RVA: 0x617337c VA: 0x759878b37c
	public Void set_ItemTypeNameHandling(Nullable`1 value) { }
	// RVA: 0x6173384 VA: 0x759878b384
	public Nullable`1 get_ItemReferenceLoopHandling() { }
	// RVA: 0x617338c VA: 0x759878b38c
	public Void set_ItemReferenceLoopHandling(Nullable`1 value) { }
	// RVA: 0x6173394 VA: 0x759878b394
	internal Void WritePropertyName(JsonWriter writer) { }
	// RVA: 0x61733e0 VA: 0x759878b3e0
	public Void .ctor() { }
}
```