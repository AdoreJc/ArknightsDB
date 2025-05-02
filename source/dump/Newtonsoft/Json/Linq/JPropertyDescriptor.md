# JPropertyDescriptor

**Namespace:** `Newtonsoft.Json.Linq`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JPropertyDescriptor : PropertyDescriptor
{

	public override Type ComponentType { get; }
	public override Boolean IsReadOnly { get; }
	public override Type PropertyType { get; }
	protected override Int32 NameHashCode { get; }

	// RVA: 0x61876cc VA: 0x759879f6cc
	public Void .ctor(String name) { }
	// RVA: 0x61876d8 VA: 0x759879f6d8
	private static JObject CastInstance(Object instance) { }
	// RVA: 0x6187754 VA: 0x759879f754
	public override Boolean CanResetValue(Object component) { }
	// RVA: 0x618775c VA: 0x759879f75c
	public override Object GetValue(Object component) { }
	// RVA: 0x61877a4 VA: 0x759879f7a4
	public override Void ResetValue(Object component) { }
	// RVA: 0x61877a8 VA: 0x759879f7a8
	public override Void SetValue(Object component, Object value) { }
	// RVA: 0x6187894 VA: 0x759879f894
	public override Boolean ShouldSerializeValue(Object component) { }
	// RVA: 0x618789c VA: 0x759879f89c
	public override Type get_ComponentType() { }
	// RVA: 0x6187908 VA: 0x759879f908
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x6187910 VA: 0x759879f910
	public override Type get_PropertyType() { }
	// RVA: 0x618797c VA: 0x759879f97c
	protected override Int32 get_NameHashCode() { }
}
```