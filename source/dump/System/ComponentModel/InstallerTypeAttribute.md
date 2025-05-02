# InstallerTypeAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `String _typeName`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class InstallerTypeAttribute : Attribute
{
	private String _typeName; // 0x10

	public virtual Type InstallerType { get; }

	// RVA: 0x63c4684 VA: 0x75989dc684
	public Void .ctor(Type installerType) { }
	// RVA: 0x63c46d0 VA: 0x75989dc6d0
	public Void .ctor(String typeName) { }
	// RVA: 0x63c4700 VA: 0x75989dc700
	public virtual Type get_InstallerType() { }
	// RVA: 0x63c4788 VA: 0x75989dc788
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63c4834 VA: 0x75989dc834
	public override Int32 GetHashCode() { }
}
```