# ReflectionObject

**Namespace:** `Newtonsoft.Json.Utilities`


## Methods

- `Void set_Creator(ObjectConstructor`1)`

- `Void set_Members(IDictionary`2)`

- `Object GetValue(Object, String)`

- `Type GetType(String)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class ReflectionObject
{
	private ObjectConstructor`1 <Creator>k__BackingField; // 0x10
	private IDictionary`2 <Members>k__BackingField; // 0x18

	public ObjectConstructor`1 Creator { get; set; }
	public IDictionary`2 Members { get; set; }

	// RVA: 0x6153d84 VA: 0x759876bd84
	public ObjectConstructor`1 get_Creator() { }
	// RVA: 0x6153d8c VA: 0x759876bd8c
	private Void set_Creator(ObjectConstructor`1 value) { }
	// RVA: 0x6153d94 VA: 0x759876bd94
	public IDictionary`2 get_Members() { }
	// RVA: 0x6153d9c VA: 0x759876bd9c
	private Void set_Members(IDictionary`2 value) { }
	// RVA: 0x6153da4 VA: 0x759876bda4
	public Void .ctor() { }
	// RVA: 0x6153e2c VA: 0x759876be2c
	public Object GetValue(Object target, String member) { }
	// RVA: 0x6153f00 VA: 0x759876bf00
	public Type GetType(String member) { }
	// RVA: 0x6153fb4 VA: 0x759876bfb4
	public static ReflectionObject Create(Type t, String[] memberNames) { }
	// RVA: 0x6153fc0 VA: 0x759876bfc0
	public static ReflectionObject Create(Type t, MethodBase creator, String[] memberNames) { }
}
```