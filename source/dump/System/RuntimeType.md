# RuntimeType

**Namespace:** `System`


## Fields

- `MonoTypeInfo type_info`

- `RuntimeConstructorInfo m_serializationCtor`


## Methods

- `RuntimeType GetBaseType()`

- `Object Clone()`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Void CreateInstanceCheckThis()`

- `String GetDefaultMemberName()`

- `Object CreateInstanceMono(Boolean, Boolean)`

- `Object TryConvertToType(Object, ref)`

- `String GetCachedName(TypeNameKind)`

- `Type make_array_type(Int32)`

- `Type make_byref_type()`

- `IntPtr GetPropertiesByName_native(IntPtr, BindingFlags, MemberListType)`

- `IntPtr GetConstructors_native(BindingFlags)`

- `Boolean IsGenericCOMObjectImpl()`

- `GenericParameterAttributes GetGenericParameterAttributes()`

- `Int32 GetGenericParameterPosition()`

- `IntPtr GetEvents_native(IntPtr, MemberListType)`

- `IntPtr GetFields_native(IntPtr, BindingFlags, MemberListType)`

- `IntPtr GetNestedTypes_native(IntPtr, BindingFlags, MemberListType)`

- `MethodInfo GetMethodImplCommon(String, Int32, BindingFlags, Binder, CallingConventions, Type[], ParameterModifier[])`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class RuntimeType : TypeInfo, ISerializable, ICloneable
{
	internal static readonly RuntimeType ValueType; // 0x0
	internal static readonly RuntimeType EnumType; // 0x8
	private static readonly RuntimeType ObjectType; // 0x10
	private static readonly RuntimeType StringType; // 0x18
	private static readonly RuntimeType DelegateType; // 0x20
	private static Type[] s_SICtorParamTypes; // 0x28
	internal static Func`3 MakeTypeBuilderInstantiation; // 0x30
	private const BindingFlags MemberBindingMask; // 0x0
	private const BindingFlags InvocationMask; // 0x0
	private const BindingFlags BinderNonCreateInstance; // 0x0
	private const BindingFlags BinderGetSetProperty; // 0x0
	private const BindingFlags BinderSetInvokeProperty; // 0x0
	private const BindingFlags BinderGetSetField; // 0x0
	private const BindingFlags BinderSetInvokeField; // 0x0
	private const BindingFlags BinderNonFieldGetSet; // 0x0
	private const BindingFlags ClassicBindingMask; // 0x0
	private static RuntimeType s_typedRef; // 0x38
	private MonoTypeInfo type_info; // 0x18
	internal Object GenericCache; // 0x20
	private RuntimeConstructorInfo m_serializationCtor; // 0x28
	private const Int32 GenericParameterCountAny; // 0x0

	public override Module Module { get; }
	public override Assembly Assembly { get; }
	public override RuntimeTypeHandle TypeHandle { get; }
	public override Type BaseType { get; }
	public override Type UnderlyingSystemType { get; }
	public override Boolean IsEnum { get; }
	public override GenericParameterAttributes GenericParameterAttributes { get; }
	internal override Boolean IsSzArray { get; }
	public override Boolean IsGenericTypeDefinition { get; }
	public override Boolean IsGenericParameter { get; }
	public override Int32 GenericParameterPosition { get; }
	public override Boolean IsGenericType { get; }
	public override Boolean IsConstructedGenericType { get; }
	public override MemberTypes MemberType { get; }
	public override Type ReflectedType { get; }
	public override Int32 MetadataToken { get; }
	public override Boolean ContainsGenericParameters { get; }
	public override MethodBase DeclaringMethod { get; }
	public override String AssemblyQualifiedName { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override String Namespace { get; }
	public override String FullName { get; }
	public override Boolean IsSZArray { get; }

	// RVA: 0x60ec3d0 VA: 0x75987043d0
	internal static RuntimeType GetType(String typeName, Boolean throwOnError, Boolean ignoreCase, Boolean reflectionOnly, ref StackCrawlMark stackMark) { }
	// RVA: 0x60ec43c VA: 0x759870443c
	private static Void ThrowIfTypeNeverValidGenericArgument(RuntimeType type) { }
	// RVA: 0x60ec5a0 VA: 0x75987045a0
	internal static Void SanityCheckGenericArguments(RuntimeType[] genericArguments, RuntimeType[] genericParamters) { }
	// RVA: 0x60ec7c4 VA: 0x75987047c4
	private static Void SplitName(String fullname, out String name, out String ns) { }
	// RVA: 0x60ec8fc VA: 0x75987048fc
	internal static BindingFlags FilterPreCalculate(Boolean isPublic, Boolean isInherited, Boolean isStatic) { }
	// RVA: 0x60ec938 VA: 0x7598704938
	private static Void FilterHelper(BindingFlags bindingFlags, ref String name, Boolean allowPrefixLookup, out Boolean prefixLookup, out Boolean ignoreCase, out MemberListType listType) { }
	// RVA: 0x60eca70 VA: 0x7598704a70
	private static Void FilterHelper(BindingFlags bindingFlags, ref String name, out Boolean ignoreCase, out MemberListType listType) { }
	// RVA: 0x60ecafc VA: 0x7598704afc
	private static Boolean FilterApplyPrefixLookup(MemberInfo memberInfo, String name, Boolean ignoreCase) { }
	// RVA: 0x60ecb5c VA: 0x7598704b5c
	private static Boolean FilterApplyBase(MemberInfo memberInfo, BindingFlags bindingFlags, Boolean isPublic, Boolean isNonProtectedInternal, Boolean isStatic, String name, Boolean prefixLookup) { }
	// RVA: 0x60ecd38 VA: 0x7598704d38
	private static Boolean FilterApplyType(Type type, BindingFlags bindingFlags, String name, Boolean prefixLookup, String ns) { }
	// RVA: 0x60ece50 VA: 0x7598704e50
	private static Boolean FilterApplyMethodInfo(RuntimeMethodInfo method, BindingFlags bindingFlags, CallingConventions callConv, Type[] argumentTypes) { }
	// RVA: 0x60ed130 VA: 0x7598705130
	private static Boolean FilterApplyConstructorInfo(RuntimeConstructorInfo constructor, BindingFlags bindingFlags, CallingConventions callConv, Type[] argumentTypes) { }
	// RVA: 0x60eced8 VA: 0x7598704ed8
	private static Boolean FilterApplyMethodBase(MethodBase methodBase, BindingFlags methodFlags, BindingFlags bindingFlags, CallingConventions callConv, Type[] argumentTypes) { }
	// RVA: 0x60ed1b8 VA: 0x75987051b8
	internal Void .ctor() { }
	// RVA: 0x60ed200 VA: 0x7598705200
	private ListBuilder`1 GetMethodCandidates(String name, BindingFlags bindingAttr, CallingConventions callConv, Type[] types, Int32 genericParamCount, Boolean allowPrefixLookup) { }
	// RVA: 0x60ed758 VA: 0x7598705758
	private ListBuilder`1 GetConstructorCandidates(String name, BindingFlags bindingAttr, CallingConventions callConv, Type[] types, Boolean allowPrefixLookup) { }
	// RVA: 0x60edc28 VA: 0x7598705c28
	private ListBuilder`1 GetPropertyCandidates(String name, BindingFlags bindingAttr, Type[] types, Boolean allowPrefixLookup) { }
	// RVA: 0x60ee12c VA: 0x759870612c
	private ListBuilder`1 GetEventCandidates(String name, BindingFlags bindingAttr, Boolean allowPrefixLookup) { }
	// RVA: 0x60ee5b8 VA: 0x75987065b8
	private ListBuilder`1 GetFieldCandidates(String name, BindingFlags bindingAttr, Boolean allowPrefixLookup) { }
	// RVA: 0x60eea88 VA: 0x7598706a88
	private ListBuilder`1 GetNestedTypeCandidates(String fullname, BindingFlags bindingAttr, Boolean allowPrefixLookup) { }
	// RVA: 0x60eefe4 VA: 0x7598706fe4
	public override MethodInfo[] GetMethods(BindingFlags bindingAttr) { }
	// RVA: 0x60ef070 VA: 0x7598707070
	public override ConstructorInfo[] GetConstructors(BindingFlags bindingAttr) { }
	// RVA: 0x60ef108 VA: 0x7598707108
	public override PropertyInfo[] GetProperties(BindingFlags bindingAttr) { }
	// RVA: 0x60ef18c VA: 0x759870718c
	public override EventInfo[] GetEvents(BindingFlags bindingAttr) { }
	// RVA: 0x60ef20c VA: 0x759870720c
	public override FieldInfo[] GetFields(BindingFlags bindingAttr) { }
	// RVA: 0x60ef28c VA: 0x759870728c
	public override Type[] GetNestedTypes(BindingFlags bindingAttr) { }
	// RVA: 0x60ef30c VA: 0x759870730c
	public override MemberInfo[] GetMembers(BindingFlags bindingAttr) { }
	// RVA: 0x60ef5e8 VA: 0x75987075e8
	protected override ConstructorInfo GetConstructorImpl(BindingFlags bindingAttr, Binder binder, CallingConventions callConvention, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60ef80c VA: 0x759870780c
	protected override PropertyInfo GetPropertyImpl(String name, BindingFlags bindingAttr, Binder binder, Type returnType, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60efaa8 VA: 0x7598707aa8
	public override EventInfo GetEvent(String name, BindingFlags bindingAttr) { }
	// RVA: 0x60efc78 VA: 0x7598707c78
	public override FieldInfo GetField(String name, BindingFlags bindingAttr) { }
	// RVA: 0x60eff6c VA: 0x7598707f6c
	public override Type GetInterface(String fullname, Boolean ignoreCase) { }
	// RVA: 0x60f030c VA: 0x759870830c
	public override Type GetNestedType(String fullname, BindingFlags bindingAttr) { }
	// RVA: 0x60f0508 VA: 0x7598708508
	public override MemberInfo[] GetMember(String name, MemberTypes type, BindingFlags bindingAttr) { }
	// RVA: 0x60f09f8 VA: 0x75987089f8
	public override Module get_Module() { }
	// RVA: 0x60f0a00 VA: 0x7598708a00
	internal RuntimeModule GetRuntimeModule() { }
	// RVA: 0x60f0a08 VA: 0x7598708a08
	public override Assembly get_Assembly() { }
	// RVA: 0x60f0a10 VA: 0x7598708a10
	internal RuntimeAssembly GetRuntimeAssembly() { }
	// RVA: 0x60f0a18 VA: 0x7598708a18
	public override RuntimeTypeHandle get_TypeHandle() { }
	// RVA: 0x60f0a3c VA: 0x7598708a3c
	public override Boolean IsInstanceOfType(Object o) { }
	// RVA: 0x60f0a44 VA: 0x7598708a44
	public override Boolean IsAssignableFrom(Type c) { }
	// RVA: 0x60f0b1c VA: 0x7598708b1c
	public override Boolean IsEquivalentTo(Type other) { }
	// RVA: 0x60f0bcc VA: 0x7598708bcc
	public override Type get_BaseType() { }
	// RVA: 0x60f0bd0 VA: 0x7598708bd0
	private RuntimeType GetBaseType() { }
	// RVA: 0x60f0db0 VA: 0x7598708db0
	public override Type get_UnderlyingSystemType() { }
	// RVA: 0x60f0db4 VA: 0x7598708db4
	protected override TypeAttributes GetAttributeFlagsImpl() { }
	// RVA: 0x60f0dbc VA: 0x7598708dbc
	protected override Boolean IsContextfulImpl() { }
	// RVA: 0x60f0dc4 VA: 0x7598708dc4
	protected override Boolean IsByRefImpl() { }
	// RVA: 0x60f0dcc VA: 0x7598708dcc
	protected override Boolean IsPrimitiveImpl() { }
	// RVA: 0x60f0dd4 VA: 0x7598708dd4
	protected override Boolean IsPointerImpl() { }
	// RVA: 0x60f0ddc VA: 0x7598708ddc
	protected override Boolean IsCOMObjectImpl() { }
	// RVA: 0x60f0de8 VA: 0x7598708de8
	protected override Boolean IsValueTypeImpl() { }
	// RVA: 0x60f0f08 VA: 0x7598708f08
	public override Boolean get_IsEnum() { }
	// RVA: 0x60f0f7c VA: 0x7598708f7c
	protected override Boolean HasElementTypeImpl() { }
	// RVA: 0x60f0f84 VA: 0x7598708f84
	public override GenericParameterAttributes get_GenericParameterAttributes() { }
	// RVA: 0x60f1050 VA: 0x7598709050
	internal override Boolean get_IsSzArray() { }
	// RVA: 0x60f1058 VA: 0x7598709058
	protected override Boolean IsArrayImpl() { }
	// RVA: 0x60f1060 VA: 0x7598709060
	public override Int32 GetArrayRank() { }
	// RVA: 0x60f10ec VA: 0x75987090ec
	public override Type GetElementType() { }
	// RVA: 0x60f10f4 VA: 0x75987090f4
	public override String[] GetEnumNames() { }
	// RVA: 0x60f1214 VA: 0x7598709214
	public override Array GetEnumValues() { }
	// RVA: 0x60f138c VA: 0x759870938c
	public override Type GetEnumUnderlyingType() { }
	// RVA: 0x60f1460 VA: 0x7598709460
	public override Boolean IsEnumDefined(Object value) { }
	// RVA: 0x60f198c VA: 0x759870998c
	public override String GetEnumName(Object value) { }
	// RVA: 0x60f1b7c VA: 0x7598709b7c
	internal RuntimeType[] GetGenericArgumentsInternal() { }
	// RVA: 0x60f1bf4 VA: 0x7598709bf4
	public override Type[] GetGenericArguments() { }
	// RVA: 0x60f1c84 VA: 0x7598709c84
	public override Type MakeGenericType(Type[] instantiation) { }
	// RVA: 0x60f21b0 VA: 0x759870a1b0
	public override Boolean get_IsGenericTypeDefinition() { }
	// RVA: 0x60f21b8 VA: 0x759870a1b8
	public override Boolean get_IsGenericParameter() { }
	// RVA: 0x60f21c0 VA: 0x759870a1c0
	public override Int32 get_GenericParameterPosition() { }
	// RVA: 0x60f224c VA: 0x759870a24c
	public override Type GetGenericTypeDefinition() { }
	// RVA: 0x60f22d8 VA: 0x759870a2d8
	public override Boolean get_IsGenericType() { }
	// RVA: 0x60f22e0 VA: 0x759870a2e0
	public override Boolean get_IsConstructedGenericType() { }
	// RVA: 0x60f2328 VA: 0x759870a328
	public override Object InvokeMember(String name, BindingFlags bindingFlags, Binder binder, Object target, Object[] providedArgs, ParameterModifier[] modifiers, CultureInfo culture, String[] namedParams) { }
	// RVA: 0x60f360c VA: 0x759870b60c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x60dcd88 VA: 0x75986f4d88
	public static Boolean op_Equality(RuntimeType left, RuntimeType right) { }
	// RVA: 0x60df980 VA: 0x75986f7980
	public static Boolean op_Inequality(RuntimeType left, RuntimeType right) { }
	// RVA: 0x60f3618 VA: 0x759870b618
	public Object Clone() { }
	// RVA: 0x60f361c VA: 0x759870b61c
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60f3684 VA: 0x759870b684
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x60f3724 VA: 0x759870b724
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x60f38c0 VA: 0x759870b8c0
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x60f3a5c VA: 0x759870ba5c
	internal override String FormatTypeName(Boolean serialization) { }
	// RVA: 0x60f3c40 VA: 0x759870bc40
	public override MemberTypes get_MemberType() { }
	// RVA: 0x60f3c84 VA: 0x759870bc84
	public override Type get_ReflectedType() { }
	// RVA: 0x60f3c90 VA: 0x759870bc90
	public override Int32 get_MetadataToken() { }
	// RVA: 0x60f3c98 VA: 0x759870bc98
	private Void CreateInstanceCheckThis() { }
	// RVA: 0x60dcd94 VA: 0x75986f4d94
	internal Object CreateInstanceImpl(BindingFlags bindingAttr, Binder binder, Object[] args, CultureInfo culture, Object[] activationAttributes, ref StackCrawlMark stackMark) { }
	// RVA: 0x60dd914 VA: 0x75986f5914
	internal Object CreateInstanceDefaultCtor(Boolean publicOnly, Boolean skipCheckThis, Boolean fillCache, Boolean wrapExceptions, ref StackCrawlMark stackMark) { }
	// RVA: 0x60f3efc VA: 0x759870befc
	internal RuntimeConstructorInfo GetDefaultConstructor() { }
	// RVA: 0x60f3520 VA: 0x759870b520
	private String GetDefaultMemberName() { }
	// RVA: 0x60f40ac VA: 0x759870c0ac
	internal RuntimeConstructorInfo GetSerializationCtor() { }
	// RVA: 0x60f3ec0 VA: 0x759870bec0
	internal Object CreateInstanceSlow(Boolean publicOnly, Boolean wrapExceptions, Boolean skipCheckThis, Boolean fillCache) { }
	// RVA: 0x60f42e8 VA: 0x759870c2e8
	private Object CreateInstanceMono(Boolean nonPublic, Boolean wrapExceptions) { }
	// RVA: 0x60f45cc VA: 0x759870c5cc
	internal Object CheckValue(Object value, Binder binder, CultureInfo culture, BindingFlags invokeAttr) { }
	// RVA: 0x60f4730 VA: 0x759870c730
	private Object TryConvertToType(Object value, ref Boolean failed) { }
	// RVA: 0x60f498c VA: 0x759870c98c
	private static Object IsConvertibleToPrimitiveType(Object value, Type targetType) { }
	// RVA: 0x60f3be8 VA: 0x759870bbe8
	private String GetCachedName(TypeNameKind kind) { }
	// RVA: 0x60f5320 VA: 0x759870d320
	private Type make_array_type(Int32 rank) { }
	// RVA: 0x60f5324 VA: 0x759870d324
	public override Type MakeArrayType() { }
	// RVA: 0x60f532c VA: 0x759870d32c
	public override Type MakeArrayType(Int32 rank) { }
	// RVA: 0x60f537c VA: 0x759870d37c
	private Type make_byref_type() { }
	// RVA: 0x60f5380 VA: 0x759870d380
	public override Type MakeByRefType() { }
	// RVA: 0x60f53ec VA: 0x759870d3ec
	private static Type MakePointerType(Type type) { }
	// RVA: 0x60f53f0 VA: 0x759870d3f0
	public override Type MakePointerType() { }
	// RVA: 0x60f54dc VA: 0x759870d4dc
	public override Boolean get_ContainsGenericParameters() { }
	// RVA: 0x60f55d8 VA: 0x759870d5d8
	public override Type[] GetGenericParameterConstraints() { }
	// RVA: 0x60f56d4 VA: 0x759870d6d4
	internal static Object CreateInstanceForAnotherGenericParameter(Type genericType, RuntimeType genericArgument) { }
	// RVA: 0x60f21ac VA: 0x759870a1ac
	private static Type MakeGenericType(Type gt, Type[] types) { }
	// RVA: 0x60f57f4 VA: 0x759870d7f4
	internal IntPtr GetMethodsByName_native(IntPtr namePtr, BindingFlags bindingAttr, MemberListType listType) { }
	// RVA: 0x60ed458 VA: 0x7598705458
	internal RuntimeMethodInfo[] GetMethodsByName(String name, BindingFlags bindingAttr, MemberListType listType, RuntimeType reflectedType) { }
	// RVA: 0x60f57f8 VA: 0x759870d7f8
	private IntPtr GetPropertiesByName_native(IntPtr name, BindingFlags bindingAttr, MemberListType listType) { }
	// RVA: 0x60f57fc VA: 0x759870d7fc
	private IntPtr GetConstructors_native(BindingFlags bindingAttr) { }
	// RVA: 0x60ed9dc VA: 0x75987059dc
	private RuntimeConstructorInfo[] GetConstructors_internal(BindingFlags bindingAttr, RuntimeType reflectedType) { }
	// RVA: 0x60ede2c VA: 0x7598705e2c
	private RuntimePropertyInfo[] GetPropertiesByName(String name, BindingFlags bindingAttr, MemberListType listType, RuntimeType reflectedType) { }
	// RVA: 0x60f5800 VA: 0x759870d800
	protected override TypeCode GetTypeCodeImpl() { }
	// RVA: 0x60f5854 VA: 0x759870d854
	private static TypeCode GetTypeCodeImplInternal(Type type) { }
	// RVA: 0x60f5858 VA: 0x759870d858
	public override String ToString() { }
	// RVA: 0x60f3eb8 VA: 0x759870beb8
	private Boolean IsGenericCOMObjectImpl() { }
	// RVA: 0x60f45c8 VA: 0x759870c5c8
	private static Object CreateInstanceInternal(Type type) { }
	// RVA: 0x60f5870 VA: 0x759870d870
	public override MethodBase get_DeclaringMethod() { }
	// RVA: 0x60f5864 VA: 0x759870d864
	internal String getFullName(Boolean full_name, Boolean assembly_qualified) { }
	// RVA: 0x60f1bec VA: 0x7598709bec
	private Type[] GetGenericArgumentsInternal(Boolean runtimeArray) { }
	// RVA: 0x60f100c VA: 0x759870900c
	private GenericParameterAttributes GetGenericParameterAttributes() { }
	// RVA: 0x60f2248 VA: 0x759870a248
	private Int32 GetGenericParameterPosition() { }
	// RVA: 0x60f5874 VA: 0x759870d874
	private IntPtr GetEvents_native(IntPtr name, MemberListType listType) { }
	// RVA: 0x60f5878 VA: 0x759870d878
	private IntPtr GetFields_native(IntPtr name, BindingFlags bindingAttr, MemberListType listType) { }
	// RVA: 0x60ee788 VA: 0x7598706788
	private RuntimeFieldInfo[] GetFields_internal(String name, BindingFlags bindingAttr, MemberListType listType, RuntimeType reflectedType) { }
	// RVA: 0x60ee2f8 VA: 0x75987062f8
	private RuntimeEventInfo[] GetEvents_internal(String name, BindingFlags bindingAttr, MemberListType listType, RuntimeType reflectedType) { }
	// RVA: 0x60f587c VA: 0x759870d87c
	public override Type[] GetInterfaces() { }
	// RVA: 0x60f5880 VA: 0x759870d880
	private IntPtr GetNestedTypes_native(IntPtr name, BindingFlags bindingAttr, MemberListType listType) { }
	// RVA: 0x60eec40 VA: 0x7598706c40
	private RuntimeType[] GetNestedTypes_internal(String displayName, BindingFlags bindingAttr, MemberListType listType) { }
	// RVA: 0x60f5884 VA: 0x759870d884
	public override String get_AssemblyQualifiedName() { }
	// RVA: 0x60f5890 VA: 0x759870d890
	public override Type get_DeclaringType() { }
	// RVA: 0x60f5894 VA: 0x759870d894
	public override String get_Name() { }
	// RVA: 0x60f5898 VA: 0x759870d898
	public override String get_Namespace() { }
	// RVA: 0x60f589c VA: 0x759870d89c
	public override Int32 GetHashCode() { }
	// RVA: 0x60f5968 VA: 0x759870d968
	public override String get_FullName() { }
	// RVA: 0x60f5a5c VA: 0x759870da5c
	public override Boolean get_IsSZArray() { }
	// RVA: 0x60f5ab4 VA: 0x759870dab4
	public override Boolean IsSubclassOf(Type type) { }
	// RVA: 0x60f5bac VA: 0x759870dbac
	protected override MethodInfo GetMethodImpl(String name, BindingFlags bindingAttr, Binder binder, CallingConventions callConv, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60f5bdc VA: 0x759870dbdc
	private MethodInfo GetMethodImplCommon(String name, Int32 genericParameterCount, BindingFlags bindingAttr, Binder binder, CallingConventions callConv, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60f5e94 VA: 0x759870de94
	private ListBuilder`1 GetMethodCandidates(String name, Int32 genericParameterCount, BindingFlags bindingAttr, CallingConventions callConv, Type[] types, Boolean allowPrefixLookup) { }
	// RVA: 0x60f60a0 VA: 0x759870e0a0
	private static Void .cctor() { }
}
```