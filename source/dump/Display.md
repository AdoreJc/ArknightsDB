# Display

**Namespace:** ` `


## Fields

- `String displayName`

- `String internal_name`


## Properties

- `String InternalName`


## Methods

- `String get_InternalName()`

- `String GetInternalName()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class Display : ATypeName, TypeIdentifier, TypeName, IEquatable`1
{
	private String displayName; // 0x10
	private String internal_name; // 0x18

	public override String DisplayName { get; }
	public String InternalName { get; }

	// RVA: 0x610d468 VA: 0x7598725468
	internal Void .ctor(String displayName) { }
	// RVA: 0x610d4a8 VA: 0x75987254a8
	public override String get_DisplayName() { }
	// RVA: 0x610d4b0 VA: 0x75987254b0
	public String get_InternalName() { }
	// RVA: 0x610d4f0 VA: 0x75987254f0
	private String GetInternalName() { }
}
```