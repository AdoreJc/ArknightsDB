# RunInstallerAttribute

**Namespace:** `System.ComponentModel`


## Properties

- `Boolean RunInstaller`


## Methods

- `Boolean get_RunInstaller()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class RunInstallerAttribute : Attribute
{
	private readonly Boolean <RunInstaller>k__BackingField; // 0x10
	public static readonly RunInstallerAttribute Yes; // 0x0
	public static readonly RunInstallerAttribute No; // 0x8
	public static readonly RunInstallerAttribute Default; // 0x10

	public Boolean RunInstaller { get; }

	// RVA: 0x63d8288 VA: 0x75989f0288
	public Void .ctor(Boolean runInstaller) { }
	// RVA: 0x63d82b0 VA: 0x75989f02b0
	public Boolean get_RunInstaller() { }
	// RVA: 0x63d82b8 VA: 0x75989f02b8
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63d836c VA: 0x75989f036c
	public override Int32 GetHashCode() { }
	// RVA: 0x63d8374 VA: 0x75989f0374
	public override Boolean IsDefaultAttribute() { }
	// RVA: 0x63d83dc VA: 0x75989f03dc
	private static Void .cctor() { }
}
```