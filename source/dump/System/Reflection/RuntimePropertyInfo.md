# RuntimePropertyInfo

**Namespace:** `System.Reflection`


## Fields

- `MonoPropertyInfo info`

- `PInfo cached`

- `GetterAdapter cached_getter`


## Properties

- `RuntimeType ReflectedTypeInternal`


## Methods

- `RuntimeType get_ReflectedTypeInternal()`

- `String FormatNameAndSig(Boolean)`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Void CachePropertyInfo(PInfo)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimePropertyInfo : PropertyInfo, ISerializable
{
	internal IntPtr klass; // 0x10
	internal IntPtr prop; // 0x18
	private MonoPropertyInfo info; // 0x20
	private PInfo cached; // 0x50
	private GetterAdapter cached_getter; // 0x58

	internal BindingFlags BindingFlags { get; }
	public override Module Module { get; }
	private RuntimeType ReflectedTypeInternal { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanWrite { get; }
	public override Type PropertyType { get; }
	public override Type ReflectedType { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override Int32 MetadataToken { get; }

	// RVA: 0x5ff7e98 VA: 0x759860fe98
	internal static Void get_property_info(RuntimePropertyInfo prop, ref MonoPropertyInfo info, PInfo req_info) { }
	// RVA: 0x5ff7e9c VA: 0x759860fe9c
	internal BindingFlags get_BindingFlags() { }
	// RVA: 0x5ff7ea4 VA: 0x759860fea4
	public override Module get_Module() { }
	// RVA: 0x5ff7ec4 VA: 0x759860fec4
	internal RuntimeType GetDeclaringTypeInternal() { }
	// RVA: 0x5ff7f48 VA: 0x759860ff48
	private RuntimeType get_ReflectedTypeInternal() { }
	// RVA: 0x5ff7ea8 VA: 0x759860fea8
	internal RuntimeModule GetRuntimeModule() { }
	// RVA: 0x5ff7fcc VA: 0x759860ffcc
	public override String ToString() { }
	// RVA: 0x5ff7fd4 VA: 0x759860ffd4
	private String FormatNameAndSig(Boolean serialization) { }
	// RVA: 0x5ff8148 VA: 0x7598610148
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff8218 VA: 0x7598610218
	internal String SerializationToString() { }
	// RVA: 0x5ff8220 VA: 0x7598610220
	private Void CachePropertyInfo(PInfo flags) { }
	// RVA: 0x5ff8260 VA: 0x7598610260
	public override Boolean get_CanRead() { }
	// RVA: 0x5ff82a0 VA: 0x75986102a0
	public override Boolean get_CanWrite() { }
	// RVA: 0x5ff82e0 VA: 0x75986102e0
	public override Type get_PropertyType() { }
	// RVA: 0x5ff8390 VA: 0x7598610390
	public override Type get_ReflectedType() { }
	// RVA: 0x5ff83c8 VA: 0x75986103c8
	public override Type get_DeclaringType() { }
	// RVA: 0x5ff8400 VA: 0x7598610400
	public override String get_Name() { }
	// RVA: 0x5ff8438 VA: 0x7598610438
	public override MethodInfo GetGetMethod(Boolean nonPublic) { }
	// RVA: 0x5ff84bc VA: 0x75986104bc
	public override ParameterInfo[] GetIndexParameters() { }
	// RVA: 0x5ff8698 VA: 0x7598610698
	public override MethodInfo GetSetMethod(Boolean nonPublic) { }
	// RVA: 0x5ff871c VA: 0x759861071c
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff8788 VA: 0x7598610788
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff87e4 VA: 0x75986107e4
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x VA: 0x0
	private static Object GetterAdapterFrame(Getter`2 getter, Object obj) { }
	// RVA: 0x VA: 0x0
	private static Object StaticGetterAdapterFrame(StaticGetter`1 getter, Object obj) { }
	// RVA: 0x5ff8850 VA: 0x7598610850
	public override Object GetValue(Object obj, Object[] index) { }
	// RVA: 0x5ff8870 VA: 0x7598610870
	public override Object GetValue(Object obj, BindingFlags invokeAttr, Binder binder, Object[] index, CultureInfo culture) { }
	// RVA: 0x5ff8a74 VA: 0x7598610a74
	public override Void SetValue(Object obj, Object value, BindingFlags invokeAttr, Binder binder, Object[] index, CultureInfo culture) { }
	// RVA: 0x5ff8c7c VA: 0x7598610c7c
	public override Int32 get_MetadataToken() { }
	// RVA: 0x5ff8c80 VA: 0x7598610c80
	internal static Int32 get_metadata_token(RuntimePropertyInfo monoProperty) { }
	// RVA: 0x5ff8c84 VA: 0x7598610c84
	private static PropertyInfo internal_from_handle_type(IntPtr event_handle, IntPtr type_handle) { }
	// RVA: 0x5ff8c88 VA: 0x7598610c88
	internal static PropertyInfo GetPropertyFromHandle(RuntimePropertyHandle handle, RuntimeTypeHandle reflectedType) { }
	// RVA: 0x5ff8d84 VA: 0x7598610d84
	public Void .ctor() { }
}
```