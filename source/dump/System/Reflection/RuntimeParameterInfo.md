# RuntimeParameterInfo

**Namespace:** `System.Reflection`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeParameterInfo : ParameterInfo
{
	internal MarshalAsAttribute marshalAs; // 0x40

	public override Object DefaultValue { get; }

	// RVA: 0x5ff6f68 VA: 0x759860ef68
	internal Void .ctor(String name, Type type, Int32 position, Int32 attrs, Object defaultValue, MemberInfo member, MarshalAsAttribute marshalAs) { }
	// RVA: 0x5ff4494 VA: 0x759860c494
	internal static Void FormatParameters(StringBuilder sb, ParameterInfo[] p, CallingConventions callingConvention, Boolean serialization) { }
	// RVA: 0x5ff7010 VA: 0x759860f010
	internal Void .ctor(ParameterInfo pinfo, MemberInfo member) { }
	// RVA: 0x5ff7190 VA: 0x759860f190
	internal Void .ctor(Type type, MemberInfo member, MarshalAsAttribute marshalAs) { }
	// RVA: 0x5ff7210 VA: 0x759860f210
	public override Object get_DefaultValue() { }
	// RVA: 0x5ff7524 VA: 0x759860f524
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff7580 VA: 0x759860f580
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff70cc VA: 0x759860f0cc
	internal Object GetDefaultValueImpl(ParameterInfo pinfo) { }
	// RVA: 0x5ff75ec VA: 0x759860f5ec
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff765c VA: 0x759860f65c
	internal Object[] GetPseudoCustomAttributes() { }
	// RVA: 0x5ff78e8 VA: 0x759860f8e8
	internal CustomAttributeData[] GetPseudoCustomAttributesData() { }
	// RVA: 0x5ff7e28 VA: 0x759860fe28
	internal static ParameterInfo New(ParameterInfo pinfo, MemberInfo member) { }
	// RVA: 0x5ff41a0 VA: 0x759860c1a0
	internal static ParameterInfo New(Type type, MemberInfo member, MarshalAsAttribute marshalAs) { }
}
```