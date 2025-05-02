# ReflectionMember

**Namespace:** `Newtonsoft.Json.Utilities`


## Fields

- `Type <MemberType>k__BackingField`


## Properties

- `Type MemberType`


## Methods

- `Type get_MemberType()`

- `Void set_MemberType(Type)`

- `Void set_Getter(Func`2)`

- `Void set_Setter(Action`2)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class ReflectionMember
{
	private Type <MemberType>k__BackingField; // 0x10
	private Func`2 <Getter>k__BackingField; // 0x18
	private Action`2 <Setter>k__BackingField; // 0x20

	public Type MemberType { get; set; }
	public Func`2 Getter { get; set; }
	public Action`2 Setter { set; }

	// RVA: 0x6153d54 VA: 0x759876bd54
	public Type get_MemberType() { }
	// RVA: 0x6153d5c VA: 0x759876bd5c
	public Void set_MemberType(Type value) { }
	// RVA: 0x6153d64 VA: 0x759876bd64
	public Func`2 get_Getter() { }
	// RVA: 0x6153d6c VA: 0x759876bd6c
	public Void set_Getter(Func`2 value) { }
	// RVA: 0x6153d74 VA: 0x759876bd74
	public Void set_Setter(Action`2 value) { }
	// RVA: 0x6153d7c VA: 0x759876bd7c
	public Void .ctor() { }
}
```