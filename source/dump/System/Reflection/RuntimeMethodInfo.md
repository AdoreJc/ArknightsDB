# RuntimeMethodInfo

**Namespace:** `System.Reflection`


## Fields

- `String name`

- `Type reftype`


## Properties

- `RuntimeType ReflectedTypeInternal`


## Methods

- `RuntimeType get_ReflectedTypeInternal()`

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `CustomAttributeData GetDllImportAttributeData()`

- `MethodInfo MakeGenericMethod_impl(Type[])`

- `MethodInfo GetGenericMethodDefinition_impl()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeMethodInfo : MethodInfo, ISerializable
{
	internal IntPtr mhandle; // 0x10
	private String name; // 0x18
	private Type reftype; // 0x20

	internal BindingFlags BindingFlags { get; }
	public override Module Module { get; }
	private RuntimeType ReflectedTypeInternal { get; }
	public override ParameterInfo ReturnParameter { get; }
	public override Type ReturnType { get; }
	public override Int32 MetadataToken { get; }
	public override RuntimeMethodHandle MethodHandle { get; }
	public override MethodAttributes Attributes { get; }
	public override CallingConventions CallingConvention { get; }
	public override Type ReflectedType { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override Boolean IsGenericMethodDefinition { get; }
	public override Boolean IsGenericMethod { get; }
	public override Boolean ContainsGenericParameters { get; }
	public override Boolean IsSecurityCritical { get; }

	// RVA: 0x5ff4218 VA: 0x759860c218
	internal BindingFlags get_BindingFlags() { }
	// RVA: 0x5ff4220 VA: 0x759860c220
	public override Module get_Module() { }
	// RVA: 0x5ff42b0 VA: 0x759860c2b0
	private RuntimeType get_ReflectedTypeInternal() { }
	// RVA: 0x5ff4334 VA: 0x759860c334
	internal override String FormatNameAndSig(Boolean serialization) { }
	// RVA: 0x5ff4688 VA: 0x759860c688
	public override Delegate CreateDelegate(Type delegateType) { }
	// RVA: 0x5ff469c VA: 0x759860c69c
	public override Delegate CreateDelegate(Type delegateType, Object target) { }
	// RVA: 0x5ff46b4 VA: 0x759860c6b4
	public override String ToString() { }
	// RVA: 0x5ff4224 VA: 0x759860c224
	internal RuntimeModule GetRuntimeModule() { }
	// RVA: 0x5ff4744 VA: 0x759860c744
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fee164 VA: 0x7598606164
	internal String SerializationToString() { }
	// RVA: 0x5ff4864 VA: 0x759860c864
	internal static MethodBase GetMethodFromHandleNoGenericCheck(RuntimeMethodHandle handle) { }
	// RVA: 0x5ff48c0 VA: 0x759860c8c0
	internal static MethodBase GetMethodFromHandleNoGenericCheck(RuntimeMethodHandle handle, RuntimeTypeHandle reflectedType) { }
	// RVA: 0x5fe7264 VA: 0x75985ff264
	internal static MethodBase GetMethodFromHandleInternalType(IntPtr method_handle, IntPtr type_handle) { }
	// RVA: 0x5ff48b8 VA: 0x759860c8b8
	private static MethodBase GetMethodFromHandleInternalType_native(IntPtr method_handle, IntPtr type_handle, Boolean genericCheck) { }
	// RVA: 0x5ff48c8 VA: 0x759860c8c8
	internal Void .ctor() { }
	// RVA: 0x5ff48d0 VA: 0x759860c8d0
	internal static String get_name(MethodBase method) { }
	// RVA: 0x5ff48d4 VA: 0x759860c8d4
	internal static RuntimeMethodInfo get_base_method(RuntimeMethodInfo method, Boolean definition) { }
	// RVA: 0x5ff48dc VA: 0x759860c8dc
	internal static Int32 get_metadata_token(RuntimeMethodInfo method) { }
	// RVA: 0x5ff48e0 VA: 0x759860c8e0
	public override MethodInfo GetBaseDefinition() { }
	// RVA: 0x5ff48e8 VA: 0x759860c8e8
	internal MethodInfo GetBaseMethod() { }
	// RVA: 0x5ff48f0 VA: 0x759860c8f0
	public override ParameterInfo get_ReturnParameter() { }
	// RVA: 0x5ff48f4 VA: 0x759860c8f4
	public override Type get_ReturnType() { }
	// RVA: 0x5ff4920 VA: 0x759860c920
	public override Int32 get_MetadataToken() { }
	// RVA: 0x5ff4924 VA: 0x759860c924
	public override MethodImplAttributes GetMethodImplementationFlags() { }
	// RVA: 0x5ff4950 VA: 0x759860c950
	public override ParameterInfo[] GetParameters() { }
	// RVA: 0x5ff49e0 VA: 0x759860c9e0
	internal override ParameterInfo[] GetParametersInternal() { }
	// RVA: 0x5ff49ec VA: 0x759860c9ec
	internal override Int32 GetParametersCount() { }
	// RVA: 0x5ff4a10 VA: 0x759860ca10
	internal Object InternalInvoke(Object obj, Object[] parameters, out Exception exc) { }
	// RVA: 0x5ff4a14 VA: 0x759860ca14
	public override Object Invoke(Object obj, BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
	// RVA: 0x5ff4d08 VA: 0x759860cd08
	internal static Void ConvertValues(Binder binder, Object[] args, ParameterInfo[] pinfo, CultureInfo culture, BindingFlags invokeAttr) { }
	// RVA: 0x5ff4fdc VA: 0x759860cfdc
	public override RuntimeMethodHandle get_MethodHandle() { }
	// RVA: 0x5ff4fe4 VA: 0x759860cfe4
	public override MethodAttributes get_Attributes() { }
	// RVA: 0x5ff4fec VA: 0x759860cfec
	public override CallingConventions get_CallingConvention() { }
	// RVA: 0x5ff5018 VA: 0x759860d018
	public override Type get_ReflectedType() { }
	// RVA: 0x5ff5020 VA: 0x759860d020
	public override Type get_DeclaringType() { }
	// RVA: 0x5ff504c VA: 0x759860d04c
	public override String get_Name() { }
	// RVA: 0x5ff5060 VA: 0x759860d060
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff50d0 VA: 0x759860d0d0
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff5138 VA: 0x759860d138
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff51a8 VA: 0x759860d1a8
	internal Void GetPInvoke(out PInvokeAttributes flags, out String entryPoint, out String dllName) { }
	// RVA: 0x5ff51ac VA: 0x759860d1ac
	internal Object[] GetPseudoCustomAttributes() { }
	// RVA: 0x5ff532c VA: 0x759860d32c
	internal CustomAttributeData[] GetPseudoCustomAttributesData() { }
	// RVA: 0x5ff550c VA: 0x759860d50c
	private CustomAttributeData GetDllImportAttributeData() { }
	// RVA: 0x5ff5ca0 VA: 0x759860dca0
	public override MethodInfo MakeGenericMethod(Type[] methodInstantiation) { }
	// RVA: 0x5ff5fec VA: 0x759860dfec
	private MethodInfo MakeGenericMethod_impl(Type[] types) { }
	// RVA: 0x5ff5ff0 VA: 0x759860dff0
	public override Type[] GetGenericArguments() { }
	// RVA: 0x5ff5ff4 VA: 0x759860dff4
	private MethodInfo GetGenericMethodDefinition_impl() { }
	// RVA: 0x5ff5ff8 VA: 0x759860dff8
	public override MethodInfo GetGenericMethodDefinition() { }
	// RVA: 0x5ff6048 VA: 0x759860e048
	public override Boolean get_IsGenericMethodDefinition() { }
	// RVA: 0x5ff604c VA: 0x759860e04c
	public override Boolean get_IsGenericMethod() { }
	// RVA: 0x5ff6050 VA: 0x759860e050
	public override Boolean get_ContainsGenericParameters() { }
	// RVA: 0x5ff6118 VA: 0x759860e118
	private static Int32 get_core_clr_security_level() { }
	// RVA: 0x5ff6120 VA: 0x759860e120
	public override Boolean get_IsSecurityCritical() { }
}
```