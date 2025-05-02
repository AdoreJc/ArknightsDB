# BooleanQueryExpression

**Namespace:** `Newtonsoft.Json.Linq.JsonPath`


## Fields

- `JValue <Value>k__BackingField`


## Properties

- `JValue Value`


## Methods

- `Void set_Path(List`1)`

- `JValue get_Value()`

- `Void set_Value(JValue)`

- `Boolean EqualsWithStringCoercion(JValue, JValue)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq.JsonPath
internal class BooleanQueryExpression : QueryExpression
{
	private List`1 <Path>k__BackingField; // 0x18
	private JValue <Value>k__BackingField; // 0x20

	public List`1 Path { get; set; }
	public JValue Value { get; set; }

	// RVA: 0x61a4c44 VA: 0x75987bcc44
	public List`1 get_Path() { }
	// RVA: 0x61a4c4c VA: 0x75987bcc4c
	public Void set_Path(List`1 value) { }
	// RVA: 0x61a4c54 VA: 0x75987bcc54
	public JValue get_Value() { }
	// RVA: 0x61a4c5c VA: 0x75987bcc5c
	public Void set_Value(JValue value) { }
	// RVA: 0x61a4c64 VA: 0x75987bcc64
	public override Boolean IsMatch(JToken t) { }
	// RVA: 0x61a50a8 VA: 0x75987bd0a8
	private Boolean EqualsWithStringCoercion(JValue value, JValue queryValue) { }
	// RVA: 0x61a5578 VA: 0x75987bd578
	public Void .ctor() { }
}
```