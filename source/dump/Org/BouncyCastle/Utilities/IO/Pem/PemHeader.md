# PemHeader

**Namespace:** `Org.BouncyCastle.Utilities.IO.Pem`


## Fields

- `String name`

- `String val`


## Methods

- `Int32 GetHashCode(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO.Pem
public class PemHeader
{
	private String name; // 0x10
	private String val; // 0x18

	public virtual String Name { get; }
	public virtual String Value { get; }

	// RVA: 0x66f7950 VA: 0x7598d0f950
	public Void .ctor(String name, String val) { }
	// RVA: 0x66f7994 VA: 0x7598d0f994
	public virtual String get_Name() { }
	// RVA: 0x66f799c VA: 0x7598d0f99c
	public virtual String get_Value() { }
	// RVA: 0x66f79a4 VA: 0x7598d0f9a4
	public override Int32 GetHashCode() { }
	// RVA: 0x66f7a24 VA: 0x7598d0fa24
	public override Boolean Equals(Object obj) { }
	// RVA: 0x66f7a04 VA: 0x7598d0fa04
	private Int32 GetHashCode(String s) { }
}
```