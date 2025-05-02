# fsMetaType

**Namespace:** `FullSerializer`


## Fields

- `Type ReflectedType`

- `Boolean _hasEmittedAotData`

- `Boolean _isDefaultConstructorPublic`


## Properties

- `Boolean HasDefaultConstructor`


## Methods

- `Boolean EmitAotData()`

- `Void set_Properties(fsMetaProperty[])`

- `Boolean get_HasDefaultConstructor()`

- `Object CreateInstance()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer
public class fsMetaType
{
	private static Dictionary`2 _configMetaTypes; // 0x0
	public Type ReflectedType; // 0x10
	private Boolean _hasEmittedAotData; // 0x18
	private fsMetaProperty[] <Properties>k__BackingField; // 0x20
	private Nullable`1 _hasDefaultConstructorCache; // 0x28
	private Boolean _isDefaultConstructorPublic; // 0x2a

	public fsMetaProperty[] Properties { get; set; }
	public Boolean HasDefaultConstructor { get; }

	// RVA: 0x34b9df8 VA: 0x7595ad1df8
	public static fsMetaType Get(fsConfig config, Type type) { }
	// RVA: 0x34ba0b8 VA: 0x7595ad20b8
	public static Void ClearCache() { }
	// RVA: 0x34b9fb4 VA: 0x7595ad1fb4
	private Void .ctor(fsConfig config, Type reflectedType) { }
	// RVA: 0x34ba160 VA: 0x7595ad2160
	private static Void CollectProperties(fsConfig config, List`1 properties, Type reflectedType) { }
	// RVA: 0x34baeb4 VA: 0x7595ad2eb4
	private static Boolean IsAutoProperty(PropertyInfo property, MemberInfo[] members) { }
	// RVA: 0x34ba798 VA: 0x7595ad2798
	private static Boolean CanSerializeProperty(fsConfig config, PropertyInfo property, MemberInfo[] members, Boolean annotationFreeValue) { }
	// RVA: 0x34babe8 VA: 0x7595ad2be8
	private static Boolean CanSerializeField(fsConfig config, FieldInfo field, Boolean annotationFreeValue) { }
	// RVA: 0x34bafec VA: 0x7595ad2fec
	public Boolean EmitAotData() { }
	// RVA: 0x34bb2c0 VA: 0x7595ad32c0
	public fsMetaProperty[] get_Properties() { }
	// RVA: 0x34bb2c8 VA: 0x7595ad32c8
	private Void set_Properties(fsMetaProperty[] value) { }
	// RVA: 0x34bb0d0 VA: 0x7595ad30d0
	public Boolean get_HasDefaultConstructor() { }
	// RVA: 0x34bb44c VA: 0x7595ad344c
	public Object CreateInstance() { }
	// RVA: 0x34bb914 VA: 0x7595ad3914
	private static Void .cctor() { }
}
```