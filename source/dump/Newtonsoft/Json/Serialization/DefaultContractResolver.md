# DefaultContractResolver

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `BindingFlags <DefaultMembersSearchFlags>k__BackingField`

- `Boolean <SerializeCompilerGeneratedMembers>k__BackingField`

- `Boolean <IgnoreSerializableInterface>k__BackingField`

- `Boolean <IgnoreSerializableAttribute>k__BackingField`


## Properties

- `BindingFlags DefaultMembersSearchFlags`

- `Boolean SerializeCompilerGeneratedMembers`

- `Boolean IgnoreSerializableInterface`

- `Boolean IgnoreSerializableAttribute`


## Methods

- `BindingFlags get_DefaultMembersSearchFlags()`

- `Void set_DefaultMembersSearchFlags(BindingFlags)`

- `Boolean get_SerializeCompilerGeneratedMembers()`

- `Boolean get_IgnoreSerializableInterface()`

- `Boolean get_IgnoreSerializableAttribute()`

- `Void set_IgnoreSerializableAttribute(Boolean)`

- `Boolean ShouldSerializeEntityMember(MemberInfo)`

- `MemberInfo GetExtensionDataMemberForType(Type)`

- `ConstructorInfo GetAttributeConstructor(Type)`

- `ConstructorInfo GetParameterizedConstructor(Type)`

- `Void InitializeContract(JsonContract)`

- `Void ResolveCallbackMethods(JsonContract, Type)`

- `Void GetCallbackMethodsForType(Type, out, out, out, out, out)`

- `Void SetPropertySettingsFromAttributes(JsonProperty, Object, String, Type, MemberSerialization, out)`

- `Void SetIsSpecifiedActions(JsonProperty, MemberInfo, Boolean)`

- `String GetResolvedPropertyName(String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class DefaultContractResolver : IContractResolver
{
	private static readonly IContractResolver _instance; // 0x0
	private static readonly JsonConverter[] BuiltInConverters; // 0x8
	private static readonly Object TypeContractCacheLock; // 0x10
	private static readonly DefaultContractResolverState _sharedState; // 0x18
	private readonly DefaultContractResolverState _instanceState; // 0x10
	private readonly Boolean _sharedCache; // 0x18
	private BindingFlags <DefaultMembersSearchFlags>k__BackingField; // 0x1c
	private Boolean <SerializeCompilerGeneratedMembers>k__BackingField; // 0x20
	private Boolean <IgnoreSerializableInterface>k__BackingField; // 0x21
	private Boolean <IgnoreSerializableAttribute>k__BackingField; // 0x22

	internal static IContractResolver Instance { get; }
	public BindingFlags DefaultMembersSearchFlags { get; set; }
	public Boolean SerializeCompilerGeneratedMembers { get; }
	public Boolean IgnoreSerializableInterface { get; }
	public Boolean IgnoreSerializableAttribute { get; set; }

	// RVA: 0x6167204 VA: 0x759877f204
	internal static IContractResolver get_Instance() { }
	// RVA: 0x616725c VA: 0x759877f25c
	public BindingFlags get_DefaultMembersSearchFlags() { }
	// RVA: 0x6167264 VA: 0x759877f264
	public Void set_DefaultMembersSearchFlags(BindingFlags value) { }
	// RVA: 0x616726c VA: 0x759877f26c
	public Boolean get_SerializeCompilerGeneratedMembers() { }
	// RVA: 0x6167274 VA: 0x759877f274
	public Boolean get_IgnoreSerializableInterface() { }
	// RVA: 0x616727c VA: 0x759877f27c
	public Boolean get_IgnoreSerializableAttribute() { }
	// RVA: 0x6167284 VA: 0x759877f284
	public Void set_IgnoreSerializableAttribute(Boolean value) { }
	// RVA: 0x6167290 VA: 0x759877f290
	public Void .ctor() { }
	// RVA: 0x6167044 VA: 0x759877f044
	public Void .ctor(Boolean shareCache) { }
	// RVA: 0x6167314 VA: 0x759877f314
	internal DefaultContractResolverState GetState() { }
	// RVA: 0x6167384 VA: 0x759877f384
	public virtual JsonContract ResolveContract(Type type) { }
	// RVA: 0x616762c VA: 0x759877f62c
	protected virtual List`1 GetSerializableMembers(Type objectType) { }
	// RVA: 0x6167fd0 VA: 0x759877ffd0
	private Boolean ShouldSerializeEntityMember(MemberInfo memberInfo) { }
	// RVA: 0x61680d8 VA: 0x75987800d8
	protected virtual JsonObjectContract CreateObjectContract(Type objectType) { }
	// RVA: 0x6168bc4 VA: 0x7598780bc4
	private MemberInfo GetExtensionDataMemberForType(Type type) { }
	// RVA: 0x6168d9c VA: 0x7598780d9c
	private static Void SetExtensionDataDelegates(JsonObjectContract contract, MemberInfo member) { }
	// RVA: 0x6168598 VA: 0x7598780598
	private ConstructorInfo GetAttributeConstructor(Type objectType) { }
	// RVA: 0x6168a64 VA: 0x7598780a64
	private ConstructorInfo GetParameterizedConstructor(Type objectType) { }
	// RVA: 0x6169714 VA: 0x7598781714
	protected virtual IList`1 CreateConstructorParameters(ConstructorInfo constructor, JsonPropertyCollection memberProperties) { }
	// RVA: 0x61698a8 VA: 0x75987818a8
	protected virtual JsonProperty CreatePropertyFromConstructorParameter(JsonProperty matchingMemberProperty, ParameterInfo parameterInfo) { }
	// RVA: 0x616a064 VA: 0x7598782064
	protected virtual JsonConverter ResolveContractConverter(Type objectType) { }
	// RVA: 0x616a0bc VA: 0x75987820bc
	private Func`1 GetDefaultCreator(Type createdType) { }
	// RVA: 0x616836c VA: 0x759878036c
	private Void InitializeContract(JsonContract contract) { }
	// RVA: 0x616a168 VA: 0x7598782168
	private Void ResolveCallbackMethods(JsonContract contract, Type t) { }
	// RVA: 0x616a2a8 VA: 0x75987822a8
	private Void GetCallbackMethodsForType(Type type, out List`1 onSerializing, out List`1 onSerialized, out List`1 onDeserializing, out List`1 onDeserialized, out List`1 onError) { }
	// RVA: 0x616acb8 VA: 0x7598782cb8
	private static Boolean ShouldSkipDeserialized(Type t) { }
	// RVA: 0x616acb0 VA: 0x7598782cb0
	private static Boolean ShouldSkipSerializing(Type t) { }
	// RVA: 0x616958c VA: 0x759878158c
	private List`1 GetClassHierarchyForType(Type type) { }
	// RVA: 0x616b2bc VA: 0x75987832bc
	protected virtual JsonDictionaryContract CreateDictionaryContract(Type objectType) { }
	// RVA: 0x616b6d0 VA: 0x75987836d0
	protected virtual JsonArrayContract CreateArrayContract(Type objectType) { }
	// RVA: 0x616b9bc VA: 0x75987839bc
	protected virtual JsonPrimitiveContract CreatePrimitiveContract(Type objectType) { }
	// RVA: 0x616ba34 VA: 0x7598783a34
	protected virtual JsonLinqContract CreateLinqContract(Type objectType) { }
	// RVA: 0x616bab8 VA: 0x7598783ab8
	protected virtual JsonISerializableContract CreateISerializableContract(Type objectType) { }
	// RVA: 0x616bccc VA: 0x7598783ccc
	protected virtual JsonStringContract CreateStringContract(Type objectType) { }
	// RVA: 0x616bd48 VA: 0x7598783d48
	protected virtual JsonContract CreateContract(Type objectType) { }
	// RVA: 0x616c098 VA: 0x7598784098
	internal static Boolean IsJsonPrimitiveType(Type t) { }
	// RVA: 0x616c310 VA: 0x7598784310
	internal static Boolean IsIConvertible(Type t) { }
	// RVA: 0x616c0f8 VA: 0x75987840f8
	internal static Boolean CanConvertToString(Type type) { }
	// RVA: 0x616acc0 VA: 0x7598782cc0
	private static Boolean IsValidCallback(MethodInfo method, ParameterInfo[] parameters, Type attributeType, MethodInfo currentCallback, ref Type prevAttributeType) { }
	// RVA: 0x616c488 VA: 0x7598784488
	internal static String GetClrTypeFullName(Type type) { }
	// RVA: 0x616c634 VA: 0x7598784634
	protected virtual IList`1 CreateProperties(Type type, MemberSerialization memberSerialization) { }
	// RVA: 0x616ca4c VA: 0x7598784a4c
	protected virtual IValueProvider CreateMemberValueProvider(MemberInfo member) { }
	// RVA: 0x616cab0 VA: 0x7598784ab0
	protected virtual JsonProperty CreateProperty(MemberInfo member, MemberSerialization memberSerialization) { }
	// RVA: 0x6169b74 VA: 0x7598781b74
	private Void SetPropertySettingsFromAttributes(JsonProperty property, Object attributeProvider, String name, Type declaringType, MemberSerialization memberSerialization, out Boolean allowNonPublicAccess) { }
	// RVA: 0x616ccc0 VA: 0x7598784cc0
	private Predicate`1 CreateShouldSerializeTest(MemberInfo member) { }
	// RVA: 0x616cf14 VA: 0x7598784f14
	private Void SetIsSpecifiedActions(JsonProperty property, MemberInfo member, Boolean allowNonPublicAccess) { }
	// RVA: 0x616d200 VA: 0x7598785200
	protected virtual String ResolvePropertyName(String propertyName) { }
	// RVA: 0x616d208 VA: 0x7598785208
	protected virtual String ResolveDictionaryKey(String dictionaryKey) { }
	// RVA: 0x616d218 VA: 0x7598785218
	public String GetResolvedPropertyName(String propertyName) { }
	// RVA: 0x616d228 VA: 0x7598785228
	private static Void .cctor() { }
}
```