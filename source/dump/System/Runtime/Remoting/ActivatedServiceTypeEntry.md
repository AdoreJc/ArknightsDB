# ActivatedServiceTypeEntry

**Namespace:** `System.Runtime.Remoting`


## Fields

- `Type obj_type`


## Properties

- `Type ObjectType`


## Methods

- `Type get_ObjectType()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class ActivatedServiceTypeEntry : TypeEntry
{
	private Type obj_type; // 0x20

	public Type ObjectType { get; }

	// RVA: 0x5f7ca9c VA: 0x7598594a9c
	public Void .ctor(String typeName, String assemblyName) { }
	// RVA: 0x5f7cbec VA: 0x7598594bec
	public Type get_ObjectType() { }
	// RVA: 0x5f7cbf4 VA: 0x7598594bf4
	public override String ToString() { }
}
```