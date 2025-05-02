# TypeDelegator

**Namespace:** `System.Reflection`


## Fields

- `Type typeImpl`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class TypeDelegator : TypeInfo
{
	protected Type typeImpl; // 0x18

	public override Int32 MetadataToken { get; }
	public override Module Module { get; }
	public override Assembly Assembly { get; }
	public override RuntimeTypeHandle TypeHandle { get; }
	public override String Name { get; }
	public override String FullName { get; }
	public override String Namespace { get; }
	public override String AssemblyQualifiedName { get; }
	public override Type BaseType { get; }
	public override Boolean IsSZArray { get; }
	public override Boolean IsGenericMethodParameter { get; }
	public override Boolean IsConstructedGenericType { get; }
	public override Boolean IsCollectible { get; }
	public override Type UnderlyingSystemType { get; }

	// RVA: 0x5fe5f50 VA: 0x75985fdf50
	public Void .ctor(Type delegatingType) { }
	// RVA: 0x5feb418 VA: 0x7598603418
	public override Int32 get_MetadataToken() { }
	// RVA: 0x5feb43c VA: 0x759860343c
	public override Object InvokeMember(String name, BindingFlags invokeAttr, Binder binder, Object target, Object[] args, ParameterModifier[] modifiers, CultureInfo culture, String[] namedParameters) { }
	// RVA: 0x5feb468 VA: 0x7598603468
	public override Module get_Module() { }
	// RVA: 0x5feb48c VA: 0x759860348c
	public override Assembly get_Assembly() { }
	// RVA: 0x5feb4b0 VA: 0x75986034b0
	public override RuntimeTypeHandle get_TypeHandle() { }
	// RVA: 0x5feb4d4 VA: 0x75986034d4
	public override String get_Name() { }
	// RVA: 0x5feb4f4 VA: 0x75986034f4
	public override String get_FullName() { }
	// RVA: 0x5feb518 VA: 0x7598603518
	public override String get_Namespace() { }
	// RVA: 0x5feb53c VA: 0x759860353c
	public override String get_AssemblyQualifiedName() { }
	// RVA: 0x5feb560 VA: 0x7598603560
	public override Type get_BaseType() { }
	// RVA: 0x5feb584 VA: 0x7598603584
	protected override ConstructorInfo GetConstructorImpl(BindingFlags bindingAttr, Binder binder, CallingConventions callConvention, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x5feb5a0 VA: 0x75986035a0
	public override ConstructorInfo[] GetConstructors(BindingFlags bindingAttr) { }
	// RVA: 0x5feb5c4 VA: 0x75986035c4
	protected override MethodInfo GetMethodImpl(String name, BindingFlags bindingAttr, Binder binder, CallingConventions callConvention, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x5feb5f0 VA: 0x75986035f0
	public override MethodInfo[] GetMethods(BindingFlags bindingAttr) { }
	// RVA: 0x5feb614 VA: 0x7598603614
	public override FieldInfo GetField(String name, BindingFlags bindingAttr) { }
	// RVA: 0x5feb638 VA: 0x7598603638
	public override FieldInfo[] GetFields(BindingFlags bindingAttr) { }
	// RVA: 0x5feb65c VA: 0x759860365c
	public override Type GetInterface(String name, Boolean ignoreCase) { }
	// RVA: 0x5feb684 VA: 0x7598603684
	public override Type[] GetInterfaces() { }
	// RVA: 0x5feb6a8 VA: 0x75986036a8
	public override EventInfo GetEvent(String name, BindingFlags bindingAttr) { }
	// RVA: 0x5feb6cc VA: 0x75986036cc
	protected override PropertyInfo GetPropertyImpl(String name, BindingFlags bindingAttr, Binder binder, Type returnType, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x5feb7bc VA: 0x75986037bc
	public override PropertyInfo[] GetProperties(BindingFlags bindingAttr) { }
	// RVA: 0x5feb7e0 VA: 0x75986037e0
	public override EventInfo[] GetEvents(BindingFlags bindingAttr) { }
	// RVA: 0x5feb804 VA: 0x7598603804
	public override Type[] GetNestedTypes(BindingFlags bindingAttr) { }
	// RVA: 0x5feb828 VA: 0x7598603828
	public override Type GetNestedType(String name, BindingFlags bindingAttr) { }
	// RVA: 0x5feb84c VA: 0x759860384c
	public override MemberInfo[] GetMember(String name, MemberTypes type, BindingFlags bindingAttr) { }
	// RVA: 0x5feb870 VA: 0x7598603870
	public override MemberInfo[] GetMembers(BindingFlags bindingAttr) { }
	// RVA: 0x5feb894 VA: 0x7598603894
	protected override TypeAttributes GetAttributeFlagsImpl() { }
	// RVA: 0x5feb8b0 VA: 0x75986038b0
	public override Boolean get_IsSZArray() { }
	// RVA: 0x5feb8d4 VA: 0x75986038d4
	protected override Boolean IsArrayImpl() { }
	// RVA: 0x5feb8f0 VA: 0x75986038f0
	protected override Boolean IsPrimitiveImpl() { }
	// RVA: 0x5feb90c VA: 0x759860390c
	protected override Boolean IsByRefImpl() { }
	// RVA: 0x5feb928 VA: 0x7598603928
	public override Boolean get_IsGenericMethodParameter() { }
	// RVA: 0x5feb94c VA: 0x759860394c
	protected override Boolean IsPointerImpl() { }
	// RVA: 0x5feb968 VA: 0x7598603968
	protected override Boolean IsValueTypeImpl() { }
	// RVA: 0x5feb984 VA: 0x7598603984
	protected override Boolean IsCOMObjectImpl() { }
	// RVA: 0x5feb9a0 VA: 0x75986039a0
	public override Boolean get_IsConstructedGenericType() { }
	// RVA: 0x5feb9c4 VA: 0x75986039c4
	public override Boolean get_IsCollectible() { }
	// RVA: 0x5feb9e8 VA: 0x75986039e8
	public override Type GetElementType() { }
	// RVA: 0x5feba0c VA: 0x7598603a0c
	protected override Boolean HasElementTypeImpl() { }
	// RVA: 0x5feba28 VA: 0x7598603a28
	public override Type get_UnderlyingSystemType() { }
	// RVA: 0x5feba4c VA: 0x7598603a4c
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5feba74 VA: 0x7598603a74
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5feba9c VA: 0x7598603a9c
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
}
```