# BindingParameter

**Namespace:** ` `


## Fields

- `BindingType binding`

- `Boolean canBeInternal`

- `BindingValueType type`

- `String qualifiedTypeName`

- `Boolean boolValue`

- `Int32 intValue`

- `Single floatValue`

- `String stringValue`

- `Vector2 vector2Value`

- `Vector3 vector3Value`

- `Vector4 vector4Value`

- `Color colorValue`

- `Rect rectValue`

- `Bounds boundsValue`

- `Object referenceValue`

- `GameObject gameObject`

- `Component component`

- `String method`


## Properties

- `Boolean CanBeInternal`

- `Type Type`

- `String BoundType`

- `Object Value`

- `GameObject GameObject`

- `Component Component`

- `MethodInfo Method`


## Methods

- `IList RestrictBinding()`

- `Boolean get_CanBeInternal()`

- `Type get_Type()`

- `Void set_Type(Type)`

- `String get_BoundType()`

- `Object get_Value()`

- `Void set_Value(Object)`

- `GameObject get_GameObject()`

- `Void set_GameObject(GameObject)`

- `Component get_Component()`

- `Void set_Component(Component)`

- `IList GetComponents()`

- `MethodInfo get_Method()`

- `Void set_Method(MethodInfo)`

- `IList GetMethods()`

- `Boolean IsMethodValid(MethodInfo)`

- `MethodInfo GetMethodInfo()`

- `Boolean IsStatic()`

- `Boolean IsExternal()`

- `Type GetRuntimeType()`

- `Object Invoke()`

- `Boolean Copiable(Object)`

- `Object Copy(Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : 
public class BindingParameter : ICopy, ICopiable
{
	public BindingType binding; // 0x10
	private Boolean canBeInternal; // 0x14
	private BindingValueType type; // 0x18
	private String qualifiedTypeName; // 0x20
	private Boolean boolValue; // 0x28
	private Int32 intValue; // 0x2c
	private Single floatValue; // 0x30
	private String stringValue; // 0x38
	private Vector2 vector2Value; // 0x40
	private Vector3 vector3Value; // 0x48
	private Vector4 vector4Value; // 0x54
	private Color colorValue; // 0x64
	private Rect rectValue; // 0x74
	private Bounds boundsValue; // 0x84
	private Object referenceValue; // 0xa0
	private GameObject gameObject; // 0xa8
	private Component component; // 0xb0
	private String method; // 0xb8

	private Boolean CanBeInternal { get; }
	public Type Type { get; set; }
	public String BoundType { get; }
	public Object Value { get; set; }
	public GameObject GameObject { get; set; }
	public Component Component { get; set; }
	public MethodInfo Method { get; set; }

	// RVA: 0x1b1eb08 VA: 0x7594136b08
	private IList RestrictBinding() { }
	// RVA: 0x1b1ed08 VA: 0x7594136d08
	private Boolean get_CanBeInternal() { }
	// RVA: 0x1b1dda4 VA: 0x7594135da4
	public Type get_Type() { }
	// RVA: 0x1b1cd1c VA: 0x7594134d1c
	public Void set_Type(Type value) { }
	// RVA: 0x1b1ed10 VA: 0x7594136d10
	public String get_BoundType() { }
	// RVA: 0x1b1e3e4 VA: 0x75941363e4
	public Object get_Value() { }
	// RVA: 0x1b1eec8 VA: 0x7594136ec8
	public Void set_Value(Object value) { }
	// RVA: 0x1b1f230 VA: 0x7594137230
	public GameObject get_GameObject() { }
	// RVA: 0x1b1f238 VA: 0x7594137238
	public Void set_GameObject(GameObject value) { }
	// RVA: 0x1b1f378 VA: 0x7594137378
	public Component get_Component() { }
	// RVA: 0x1b1f2d8 VA: 0x75941372d8
	public Void set_Component(Component value) { }
	// RVA: 0x1b1f42c VA: 0x759413742c
	private IList GetComponents() { }
	// RVA: 0x1b1f6a8 VA: 0x75941376a8
	public MethodInfo get_Method() { }
	// RVA: 0x1b1f380 VA: 0x7594137380
	public Void set_Method(MethodInfo value) { }
	// RVA: 0x1b1f780 VA: 0x7594137780
	private IList GetMethods() { }
	// RVA: 0x1b1fc50 VA: 0x7594137c50
	private Boolean IsMethodValid(MethodInfo info) { }
	// RVA: 0x1b1f6ac VA: 0x75941376ac
	private MethodInfo GetMethodInfo() { }
	// RVA: 0x1b1fe24 VA: 0x7594137e24
	private Boolean IsStatic() { }
	// RVA: 0x1b1fe34 VA: 0x7594137e34
	private Boolean IsExternal() { }
	// RVA: 0x1b1fe44 VA: 0x7594137e44
	private Type GetRuntimeType() { }
	// RVA: 0x1b1fe48 VA: 0x7594137e48
	public Void .ctor() { }
	// RVA: 0x1b1cb20 VA: 0x7594134b20
	public Void .ctor(Boolean canBeInternal) { }
	// RVA: 0x1b1da2c VA: 0x7594135a2c
	public static Boolean IsValidType(Type type) { }
	// RVA: 0x1b1edc0 VA: 0x7594136dc0
	private Object Invoke() { }
	// RVA: 0x1b20038 VA: 0x7594138038
	public Boolean Copiable(Object destination) { }
	// RVA: 0x1b200e4 VA: 0x75941380e4
	public Object Copy(Object destination) { }
	// RVA: 0x1b20258 VA: 0x7594138258
	public override String ToString() { }
}
```