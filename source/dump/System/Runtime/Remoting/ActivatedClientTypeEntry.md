# ActivatedClientTypeEntry

**Namespace:** `System.Runtime.Remoting`


## Fields

- `String applicationUrl`

- `Type obj_type`


## Properties

- `String ApplicationUrl`

- `Type ObjectType`


## Methods

- `String get_ApplicationUrl()`

- `Type get_ObjectType()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class ActivatedClientTypeEntry : TypeEntry
{
	private String applicationUrl; // 0x20
	private Type obj_type; // 0x28

	public String ApplicationUrl { get; }
	public IContextAttribute[] ContextAttributes { get; }
	public Type ObjectType { get; }

	// RVA: 0x5f7c8fc VA: 0x75985948fc
	public Void .ctor(String typeName, String assemblyName, String appUrl) { }
	// RVA: 0x5f7ca70 VA: 0x7598594a70
	public String get_ApplicationUrl() { }
	// RVA: 0x5f7ca78 VA: 0x7598594a78
	public IContextAttribute[] get_ContextAttributes() { }
	// RVA: 0x5f7ca80 VA: 0x7598594a80
	public Type get_ObjectType() { }
	// RVA: 0x5f7ca88 VA: 0x7598594a88
	public override String ToString() { }
}
```