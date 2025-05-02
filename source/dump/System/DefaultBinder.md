# DefaultBinder

**Namespace:** `System`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class DefaultBinder : Binder
{
	private static Primitives[] _primitiveConversions; // 0x0


	// RVA: 0x60e0388 VA: 0x75986f8388
	public override MethodBase BindToMethod(BindingFlags bindingAttr, MethodBase[] match, ref Object[] args, ParameterModifier[] modifiers, CultureInfo cultureInfo, String[] names, out Object state) { }
	// RVA: 0x60e2aa8 VA: 0x75986faaa8
	public override FieldInfo BindToField(BindingFlags bindingAttr, FieldInfo[] match, Object value, CultureInfo cultureInfo) { }
	// RVA: 0x60e3050 VA: 0x75986fb050
	public override PropertyInfo SelectProperty(BindingFlags bindingAttr, PropertyInfo[] match, Type returnType, Type[] indexes, ParameterModifier[] modifiers) { }
	// RVA: 0x60e4560 VA: 0x75986fc560
	public override Object ChangeType(Object value, Type type, CultureInfo cultureInfo) { }
	// RVA: 0x60e45c0 VA: 0x75986fc5c0
	public override Void ReorderArgumentArray(ref Object[] args, Object state) { }
	// RVA: 0x60e48c8 VA: 0x75986fc8c8
	public static MethodBase ExactBinding(MethodBase[] match, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60e4c90 VA: 0x75986fcc90
	public static PropertyInfo ExactPropertyBinding(PropertyInfo[] match, Type returnType, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60e403c VA: 0x75986fc03c
	private static Int32 FindMostSpecific(ParameterInfo[] p1, Int32[] paramOrder1, Type paramArrayType1, ParameterInfo[] p2, Int32[] paramOrder2, Type paramArrayType2, Type[] types, Object[] args) { }
	// RVA: 0x60e3ca4 VA: 0x75986fbca4
	private static Int32 FindMostSpecificType(Type c1, Type c2, Type t) { }
	// RVA: 0x60e2928 VA: 0x75986fa928
	private static Int32 FindMostSpecificMethod(MethodBase m1, Int32[] paramOrder1, Type paramArrayType1, MethodBase m2, Int32[] paramOrder2, Type paramArrayType2, Type[] types, Object[] args) { }
	// RVA: 0x60e2f68 VA: 0x75986faf68
	private static Int32 FindMostSpecificField(FieldInfo cur1, FieldInfo cur2) { }
	// RVA: 0x60e4478 VA: 0x75986fc478
	private static Int32 FindMostSpecificProperty(PropertyInfo cur1, PropertyInfo cur2) { }
	// RVA: 0x60e4f4c VA: 0x75986fcf4c
	internal static Boolean CompareMethodSigAndName(MethodBase m1, MethodBase m2) { }
	// RVA: 0x60e50a8 VA: 0x75986fd0a8
	internal static Int32 GetHierarchyDepth(Type t) { }
	// RVA: 0x60e4b40 VA: 0x75986fcb40
	internal static MethodBase FindMostDerivedNewSlotMeth(MethodBase[] match, Int32 cMatches) { }
	// RVA: 0x60e27a4 VA: 0x75986fa7a4
	private static Void ReorderParams(Int32[] paramOrder, Object[] vars) { }
	// RVA: 0x60e2408 VA: 0x75986fa408
	private static Boolean CreateParamOrder(Int32[] paramOrder, ParameterInfo[] pars, String[] names) { }
	// RVA: 0x60e3a80 VA: 0x75986fba80
	private static Boolean CanConvertPrimitive(RuntimeType source, RuntimeType target) { }
	// RVA: 0x60e2648 VA: 0x75986fa648
	private static Boolean CanConvertPrimitiveObjectToType(Object source, RuntimeType type) { }
	// RVA: 0x60e513c VA: 0x75986fd13c
	internal static Boolean CompareMethodSig(MethodBase m1, MethodBase m2) { }
	// RVA: 0x60e5298 VA: 0x75986fd298
	public sealed override MethodBase SelectMethod(BindingFlags bindingAttr, MethodBase[] match, Type[] types, ParameterModifier[] modifiers) { }
	// RVA: 0x60e59e0 VA: 0x75986fd9e0
	private static Boolean CanChangePrimitive(Type source, Type target) { }
	// RVA: 0x60e5a44 VA: 0x75986fda44
	private static Boolean CanPrimitiveWiden(Type source, Type target) { }
	// RVA: 0x60e5b1c VA: 0x75986fdb1c
	public Void .ctor() { }
	// RVA: 0x60e5b24 VA: 0x75986fdb24
	private static Void .cctor() { }
}
```