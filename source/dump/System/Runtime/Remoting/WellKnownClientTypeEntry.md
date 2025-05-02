# WellKnownClientTypeEntry

**Namespace:** `System.Runtime.Remoting`


## Fields

- `Type obj_type`

- `String obj_url`

- `String app_url`


## Properties

- `String ApplicationUrl`

- `Type ObjectType`

- `String ObjectUrl`


## Methods

- `String get_ApplicationUrl()`

- `Type get_ObjectType()`

- `String get_ObjectUrl()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class WellKnownClientTypeEntry : TypeEntry
{
	private Type obj_type; // 0x20
	private String obj_url; // 0x28
	private String app_url; // 0x30

	public String ApplicationUrl { get; }
	public Type ObjectType { get; }
	public String ObjectUrl { get; }

	// RVA: 0x5f8d37c VA: 0x75985a537c
	public Void .ctor(String typeName, String assemblyName, String objectUrl) { }
	// RVA: 0x5f8d4e4 VA: 0x75985a54e4
	public String get_ApplicationUrl() { }
	// RVA: 0x5f8d4ec VA: 0x75985a54ec
	public Type get_ObjectType() { }
	// RVA: 0x5f8d4f4 VA: 0x75985a54f4
	public String get_ObjectUrl() { }
	// RVA: 0x5f8d4fc VA: 0x75985a54fc
	public override String ToString() { }
}
```