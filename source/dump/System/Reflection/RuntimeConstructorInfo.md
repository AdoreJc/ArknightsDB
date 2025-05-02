# RuntimeConstructorInfo

**Namespace:** `System.Reflection`


## Fields

- `String name`

- `Type reftype`


## Properties

- `RuntimeType ReflectedTypeInternal`


## Methods

- `RuntimeType get_ReflectedTypeInternal()`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Object DoInvoke(Object, BindingFlags, Binder, Object[], CultureInfo)`

- `Object InternalInvoke(Object, Object[], Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeConstructorInfo : ConstructorInfo, ISerializable
{
	internal IntPtr mhandle; // 0x10
	private String name; // 0x18
	private Type reftype; // 0x20

	public override Module Module { get; }
	internal BindingFlags BindingFlags { get; }
	private RuntimeType ReflectedTypeInternal { get; }
	public override RuntimeMethodHandle MethodHandle { get; }
	public override MethodAttributes Attributes { get; }
	public override CallingConventions CallingConvention { get; }
	public override Boolean ContainsGenericParameters { get; }
	public override Type ReflectedType { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override Boolean IsSecurityCritical { get; }
	public override Int32 MetadataToken { get; }

	// RVA: 0x5ff6128 VA: 0x759860e128
	public override Module get_Module() { }
	// RVA: 0x5ff612c VA: 0x759860e12c
	internal RuntimeModule GetRuntimeModule() { }
	// RVA: 0x5ff61b4 VA: 0x759860e1b4
	internal BindingFlags get_BindingFlags() { }
	// RVA: 0x5ff61bc VA: 0x759860e1bc
	private RuntimeType get_ReflectedTypeInternal() { }
	// RVA: 0x5ff6240 VA: 0x759860e240
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fee150 VA: 0x7598606150
	internal String SerializationToString() { }
	// RVA: 0x5ff6318 VA: 0x759860e318
	internal Void SerializationInvoke(Object target, SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff645c VA: 0x759860e45c
	public override MethodImplAttributes GetMethodImplementationFlags() { }
	// RVA: 0x5ff6488 VA: 0x759860e488
	public override ParameterInfo[] GetParameters() { }
	// RVA: 0x5ff6494 VA: 0x759860e494
	internal override ParameterInfo[] GetParametersInternal() { }
	// RVA: 0x5ff64a0 VA: 0x759860e4a0
	internal override Int32 GetParametersCount() { }
	// RVA: 0x5ff64c0 VA: 0x759860e4c0
	internal Object InternalInvoke(Object obj, Object[] parameters, out Exception exc) { }
	// RVA: 0x5ff64c4 VA: 0x759860e4c4
	public override Object Invoke(Object obj, BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
	// RVA: 0x5ff65cc VA: 0x759860e5cc
	private Object DoInvoke(Object obj, BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
	// RVA: 0x5ff67c0 VA: 0x759860e7c0
	public Object InternalInvoke(Object obj, Object[] parameters, Boolean wrapExceptions) { }
	// RVA: 0x5ff691c VA: 0x759860e91c
	public override Object Invoke(BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
	// RVA: 0x5ff6934 VA: 0x759860e934
	public override RuntimeMethodHandle get_MethodHandle() { }
	// RVA: 0x5ff693c VA: 0x759860e93c
	public override MethodAttributes get_Attributes() { }
	// RVA: 0x5ff6944 VA: 0x759860e944
	public override CallingConventions get_CallingConvention() { }
	// RVA: 0x5ff6970 VA: 0x759860e970
	public override Boolean get_ContainsGenericParameters() { }
	// RVA: 0x5ff699c VA: 0x759860e99c
	public override Type get_ReflectedType() { }
	// RVA: 0x5ff69a4 VA: 0x759860e9a4
	public override Type get_DeclaringType() { }
	// RVA: 0x5ff69d0 VA: 0x759860e9d0
	public override String get_Name() { }
	// RVA: 0x5ff69e4 VA: 0x759860e9e4
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff6a54 VA: 0x759860ea54
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff6abc VA: 0x759860eabc
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff6b2c VA: 0x759860eb2c
	public override String ToString() { }
	// RVA: 0x5ff6b94 VA: 0x759860eb94
	private static Int32 get_core_clr_security_level() { }
	// RVA: 0x5ff6b9c VA: 0x759860eb9c
	public override Boolean get_IsSecurityCritical() { }
	// RVA: 0x5ff6ba4 VA: 0x759860eba4
	public override Int32 get_MetadataToken() { }
	// RVA: 0x5ff6ba8 VA: 0x759860eba8
	internal static Int32 get_metadata_token(RuntimeConstructorInfo method) { }
	// RVA: 0x5ff6bac VA: 0x759860ebac
	public Void .ctor() { }
}
```