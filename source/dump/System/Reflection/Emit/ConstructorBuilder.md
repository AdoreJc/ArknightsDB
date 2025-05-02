# ConstructorBuilder

**Namespace:** `System.Reflection.Emit`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection.Emit
public class ConstructorBuilder : ConstructorInfo
{

	public override MethodAttributes Attributes { get; }
	public override Type DeclaringType { get; }
	public override String Name { get; }
	public override RuntimeMethodHandle MethodHandle { get; }
	public override Type ReflectedType { get; }

	// RVA: 0x5ff9258 VA: 0x7598611258
	public override MethodAttributes get_Attributes() { }
	// RVA: 0x5ff9298 VA: 0x7598611298
	public override Type get_DeclaringType() { }
	// RVA: 0x5ff92d8 VA: 0x75986112d8
	public override String get_Name() { }
	// RVA: 0x5ff9318 VA: 0x7598611318
	public override ParameterInfo[] GetParameters() { }
	// RVA: 0x5ff9358 VA: 0x7598611358
	public override MethodImplAttributes GetMethodImplementationFlags() { }
	// RVA: 0x5ff9398 VA: 0x7598611398
	public override RuntimeMethodHandle get_MethodHandle() { }
	// RVA: 0x5ff93d8 VA: 0x75986113d8
	public override Object Invoke(BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
	// RVA: 0x5ff9418 VA: 0x7598611418
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff9458 VA: 0x7598611458
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff9498 VA: 0x7598611498
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff94d8 VA: 0x75986114d8
	public override Type get_ReflectedType() { }
	// RVA: 0x5ff9518 VA: 0x7598611518
	public override Object Invoke(Object obj, BindingFlags invokeAttr, Binder binder, Object[] parameters, CultureInfo culture) { }
}
```