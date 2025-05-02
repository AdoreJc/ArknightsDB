# RuntimeFieldInfo

**Namespace:** `System.Reflection`


## Fields

- `String name`

- `Type type`

- `FieldAttributes attrs`


## Properties

- `RuntimeType ReflectedTypeInternal`


## Methods

- `RuntimeType get_ReflectedTypeInternal()`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Type ResolveType()`

- `Type GetParentType(Boolean)`

- `Object GetValueInternal(Object)`

- `Void CheckGeneric()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeFieldInfo : RtFieldInfo, ISerializable
{
	internal IntPtr klass; // 0x10
	internal RuntimeFieldHandle fhandle; // 0x18
	private String name; // 0x20
	private Type type; // 0x28
	private FieldAttributes attrs; // 0x30

	internal BindingFlags BindingFlags { get; }
	public override Module Module { get; }
	private RuntimeType ReflectedTypeInternal { get; }
	public override FieldAttributes Attributes { get; }
	public override RuntimeFieldHandle FieldHandle { get; }
	public override Type FieldType { get; }
	public override Type ReflectedType { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override Int32 MetadataToken { get; }

	// RVA: 0x5ff33b0 VA: 0x759860b3b0
	internal BindingFlags get_BindingFlags() { }
	// RVA: 0x5ff33b8 VA: 0x759860b3b8
	public override Module get_Module() { }
	// RVA: 0x5ff33d8 VA: 0x759860b3d8
	internal RuntimeType GetDeclaringTypeInternal() { }
	// RVA: 0x5ff345c VA: 0x759860b45c
	private RuntimeType get_ReflectedTypeInternal() { }
	// RVA: 0x5ff33bc VA: 0x759860b3bc
	internal RuntimeModule GetRuntimeModule() { }
	// RVA: 0x5ff34e0 VA: 0x759860b4e0
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff359c VA: 0x759860b59c
	internal override Object UnsafeGetValue(Object obj) { }
	// RVA: 0x5ff35a0 VA: 0x759860b5a0
	internal override Void CheckConsistency(Object target) { }
	// RVA: 0x5ff3720 VA: 0x759860b720
	internal override Void UnsafeSetValue(Object obj, Object value, BindingFlags invokeAttr, Binder binder, CultureInfo culture) { }
	// RVA: 0x5ff3784 VA: 0x759860b784
	public override Void SetValueDirect(TypedReference obj, Object value) { }
	// RVA: 0x5ff38e8 VA: 0x759860b8e8
	public override FieldAttributes get_Attributes() { }
	// RVA: 0x5ff38f0 VA: 0x759860b8f0
	public override RuntimeFieldHandle get_FieldHandle() { }
	// RVA: 0x5ff38f8 VA: 0x759860b8f8
	private Type ResolveType() { }
	// RVA: 0x5ff38fc VA: 0x759860b8fc
	public override Type get_FieldType() { }
	// RVA: 0x5ff398c VA: 0x759860b98c
	private Type GetParentType(Boolean declaring) { }
	// RVA: 0x5ff3994 VA: 0x759860b994
	public override Type get_ReflectedType() { }
	// RVA: 0x5ff399c VA: 0x759860b99c
	public override Type get_DeclaringType() { }
	// RVA: 0x5ff39a4 VA: 0x759860b9a4
	public override String get_Name() { }
	// RVA: 0x5ff39ac VA: 0x759860b9ac
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff3a1c VA: 0x759860ba1c
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff3a84 VA: 0x759860ba84
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff3af4 VA: 0x759860baf4
	internal override Int32 GetFieldOffset() { }
	// RVA: 0x5ff3af8 VA: 0x759860baf8
	private Object GetValueInternal(Object obj) { }
	// RVA: 0x5ff3afc VA: 0x759860bafc
	public override Object GetValue(Object obj) { }
	// RVA: 0x5ff3d1c VA: 0x759860bd1c
	public override String ToString() { }
	// RVA: 0x5ff3d84 VA: 0x759860bd84
	private static Void SetValueInternal(FieldInfo fi, Object obj, Object value) { }
	// RVA: 0x5ff3d88 VA: 0x759860bd88
	public override Void SetValue(Object obj, Object val, BindingFlags invokeAttr, Binder binder, CultureInfo culture) { }
	// RVA: 0x5ff404c VA: 0x759860c04c
	public override Object GetRawConstantValue() { }
	// RVA: 0x5ff3c9c VA: 0x759860bc9c
	private Void CheckGeneric() { }
	// RVA: 0x5ff4050 VA: 0x759860c050
	public override Int32 get_MetadataToken() { }
	// RVA: 0x5ff4054 VA: 0x759860c054
	internal static Int32 get_metadata_token(RuntimeFieldInfo monoField) { }
	// RVA: 0x5ff4058 VA: 0x759860c058
	public Void .ctor() { }
}
```