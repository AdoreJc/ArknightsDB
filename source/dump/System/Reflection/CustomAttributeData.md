# CustomAttributeData

**Namespace:** `System.Reflection`


## Fields

- `ConstructorInfo ctorInfo`

- `LazyCAttrData lazyData`


## Properties

- `Type AttributeType`


## Methods

- `Void ResolveArguments()`

- `Type get_AttributeType()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class CustomAttributeData
{
	private ConstructorInfo ctorInfo; // 0x10
	private IList`1 ctorArgs; // 0x18
	private IList`1 namedArgs; // 0x20
	private LazyCAttrData lazyData; // 0x28

	public virtual ConstructorInfo Constructor { get; }
	public virtual IList`1 ConstructorArguments { get; }
	public virtual IList`1 NamedArguments { get; }
	public Type AttributeType { get; }

	// RVA: 0x5ff0788 VA: 0x7598608788
	protected Void .ctor() { }
	// RVA: 0x5ff0790 VA: 0x7598608790
	internal Void .ctor(ConstructorInfo ctorInfo, Assembly assembly, IntPtr data, UInt32 data_length) { }
	// RVA: 0x5fe5998 VA: 0x75985fd998
	internal Void .ctor(ConstructorInfo ctorInfo) { }
	// RVA: 0x5fe5d84 VA: 0x75985fdd84
	internal Void .ctor(ConstructorInfo ctorInfo, IList`1 ctorArgs, IList`1 namedArgs) { }
	// RVA: 0x5ff0864 VA: 0x7598608864
	private static Void ResolveArgumentsInternal(ConstructorInfo ctor, Assembly assembly, IntPtr data, UInt32 data_length, out Object[] ctorArgs, out Object[] namedArgs) { }
	// RVA: 0x5ff0868 VA: 0x7598608868
	private Void ResolveArguments() { }
	// RVA: 0x5ff0a30 VA: 0x7598608a30
	public virtual ConstructorInfo get_Constructor() { }
	// RVA: 0x5ff0a38 VA: 0x7598608a38
	public virtual IList`1 get_ConstructorArguments() { }
	// RVA: 0x5ff0a50 VA: 0x7598608a50
	public virtual IList`1 get_NamedArguments() { }
	// RVA: 0x5ff0a68 VA: 0x7598608a68
	public static IList`1 GetCustomAttributes(Assembly target) { }
	// RVA: 0x5ff0ac4 VA: 0x7598608ac4
	public static IList`1 GetCustomAttributes(MemberInfo target) { }
	// RVA: 0x5ff0b20 VA: 0x7598608b20
	internal static IList`1 GetCustomAttributesInternal(RuntimeType target) { }
	// RVA: 0x5ff0b7c VA: 0x7598608b7c
	public static IList`1 GetCustomAttributes(Module target) { }
	// RVA: 0x5ff0bd8 VA: 0x7598608bd8
	public static IList`1 GetCustomAttributes(ParameterInfo target) { }
	// RVA: 0x5ff0c34 VA: 0x7598608c34
	public Type get_AttributeType() { }
	// RVA: 0x5ff0c54 VA: 0x7598608c54
	public override String ToString() { }
	// RVA: 0x VA: 0x0
	private static T[] UnboxValues(Object[] values) { }
	// RVA: 0x5ff11c4 VA: 0x75986091c4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x5ff1844 VA: 0x7598609844
	public override Int32 GetHashCode() { }
}
```