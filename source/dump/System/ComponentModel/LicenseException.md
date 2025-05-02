# LicenseException

**Namespace:** `System.ComponentModel`


## Fields

- `Type type`

- `Object instance`


## Properties

- `Type LicensedType`


## Methods

- `Type get_LicensedType()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class LicenseException : SystemException
{
	private Type type; // 0x90
	private Object instance; // 0x98

	public Type LicensedType { get; }

	// RVA: 0x63e2130 VA: 0x75989fa130
	public Void .ctor(Type type) { }
	// RVA: 0x63e227c VA: 0x75989fa27c
	public Void .ctor(Type type, Object instance) { }
	// RVA: 0x63e2224 VA: 0x75989fa224
	public Void .ctor(Type type, Object instance, String message) { }
	// RVA: 0x63e23d0 VA: 0x75989fa3d0
	public Void .ctor(Type type, Object instance, String message, Exception innerException) { }
	// RVA: 0x63e242c VA: 0x75989fa42c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x63e25cc VA: 0x75989fa5cc
	public Type get_LicensedType() { }
	// RVA: 0x63e25d4 VA: 0x75989fa5d4
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
}
```