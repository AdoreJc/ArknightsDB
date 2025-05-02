# TypeEntry

**Namespace:** `System.Runtime.Remoting`


## Fields

- `String assembly_name`

- `String type_name`


## Properties

- `String AssemblyName`

- `String TypeName`


## Methods

- `String get_AssemblyName()`

- `Void set_AssemblyName(String)`

- `String get_TypeName()`

- `Void set_TypeName(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class TypeEntry
{
	private String assembly_name; // 0x10
	private String type_name; // 0x18

	public String AssemblyName { get; set; }
	public String TypeName { get; set; }

	// RVA: 0x5f7ca60 VA: 0x7598594a60
	protected Void .ctor() { }
	// RVA: 0x5f8c0e8 VA: 0x75985a40e8
	public String get_AssemblyName() { }
	// RVA: 0x5f8c0f0 VA: 0x75985a40f0
	public Void set_AssemblyName(String value) { }
	// RVA: 0x5f8c0f8 VA: 0x75985a40f8
	public String get_TypeName() { }
	// RVA: 0x5f8c100 VA: 0x75985a4100
	public Void set_TypeName(String value) { }
}
```