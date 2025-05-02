# ParameterInfo

**Namespace:** `System.Reflection`


## Fields

- `ParameterAttributes AttrsImpl`

- `Type ClassImpl`

- `Object DefaultValueImpl`

- `MemberInfo MemberImpl`

- `String NameImpl`

- `Int32 PositionImpl`


## Properties

- `Boolean IsIn`

- `Boolean IsOptional`

- `Boolean IsOut`


## Methods

- `Boolean get_IsIn()`

- `Boolean get_IsOptional()`

- `Boolean get_IsOut()`

- `Object GetRealObject(StreamingContext)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class ParameterInfo : ICustomAttributeProvider, IObjectReference, _ParameterInfo
{
	protected ParameterAttributes AttrsImpl; // 0x10
	protected Type ClassImpl; // 0x18
	protected Object DefaultValueImpl; // 0x20
	protected MemberInfo MemberImpl; // 0x28
	protected String NameImpl; // 0x30
	protected Int32 PositionImpl; // 0x38
	private const Int32 MetadataToken_ParamDef; // 0x0

	public virtual ParameterAttributes Attributes { get; }
	public virtual MemberInfo Member { get; }
	public virtual String Name { get; }
	public virtual Type ParameterType { get; }
	public virtual Int32 Position { get; }
	public Boolean IsIn { get; }
	public Boolean IsOptional { get; }
	public Boolean IsOut { get; }
	public virtual Object DefaultValue { get; }

	// RVA: 0x5fe7bfc VA: 0x75985ffbfc
	protected Void .ctor() { }
	// RVA: 0x5fe7c04 VA: 0x75985ffc04
	public virtual ParameterAttributes get_Attributes() { }
	// RVA: 0x5fe7c0c VA: 0x75985ffc0c
	public virtual MemberInfo get_Member() { }
	// RVA: 0x5fe7c14 VA: 0x75985ffc14
	public virtual String get_Name() { }
	// RVA: 0x5fe7c1c VA: 0x75985ffc1c
	public virtual Type get_ParameterType() { }
	// RVA: 0x5fe7c24 VA: 0x75985ffc24
	public virtual Int32 get_Position() { }
	// RVA: 0x5fe7c2c VA: 0x75985ffc2c
	public Boolean get_IsIn() { }
	// RVA: 0x5fe7c48 VA: 0x75985ffc48
	public Boolean get_IsOptional() { }
	// RVA: 0x5fe7c64 VA: 0x75985ffc64
	public Boolean get_IsOut() { }
	// RVA: 0x5fe7c80 VA: 0x75985ffc80
	public virtual Object get_DefaultValue() { }
	// RVA: 0x5fe7ca8 VA: 0x75985ffca8
	public virtual Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5fe7d5c VA: 0x75985ffd5c
	public virtual Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5fe7dd8 VA: 0x75985ffdd8
	public virtual Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5fe7edc VA: 0x75985ffedc
	public Object GetRealObject(StreamingContext context) { }
	// RVA: 0x5fe81bc VA: 0x75986001bc
	public override String ToString() { }
}
```