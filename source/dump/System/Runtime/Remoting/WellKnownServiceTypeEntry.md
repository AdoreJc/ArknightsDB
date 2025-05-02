# WellKnownServiceTypeEntry

**Namespace:** `System.Runtime.Remoting`


## Fields

- `Type obj_type`

- `String obj_uri`

- `WellKnownObjectMode obj_mode`


## Properties

- `WellKnownObjectMode Mode`

- `Type ObjectType`

- `String ObjectUri`


## Methods

- `WellKnownObjectMode get_Mode()`

- `Type get_ObjectType()`

- `String get_ObjectUri()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class WellKnownServiceTypeEntry : TypeEntry
{
	private Type obj_type; // 0x20
	private String obj_uri; // 0x28
	private WellKnownObjectMode obj_mode; // 0x30

	public WellKnownObjectMode Mode { get; }
	public Type ObjectType { get; }
	public String ObjectUri { get; }

	// RVA: 0x5f8d518 VA: 0x75985a5518
	public Void .ctor(String typeName, String assemblyName, String objectUri, WellKnownObjectMode mode) { }
	// RVA: 0x5f8d694 VA: 0x75985a5694
	public WellKnownObjectMode get_Mode() { }
	// RVA: 0x5f8d69c VA: 0x75985a569c
	public Type get_ObjectType() { }
	// RVA: 0x5f8d6a4 VA: 0x75985a56a4
	public String get_ObjectUri() { }
	// RVA: 0x5f8d6ac VA: 0x75985a56ac
	public override String ToString() { }
}
```