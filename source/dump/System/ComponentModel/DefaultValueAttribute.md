# DefaultValueAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `Object _value`


## Methods

- `Void SetValue(Object)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DefaultValueAttribute : Attribute
{
	private Object _value; // 0x10
	private static Object s_convertFromInvariantString; // 0x0

	public virtual Object Value { get; }

	// RVA: 0x63af4e0 VA: 0x75989c74e0
	public Void .ctor(Type type, String value) { }
	// RVA: 0x63af9ec VA: 0x75989c79ec
	public Void .ctor(Char value) { }
	// RVA: 0x63afa64 VA: 0x75989c7a64
	public Void .ctor(Byte value) { }
	// RVA: 0x63afadc VA: 0x75989c7adc
	public Void .ctor(Int16 value) { }
	// RVA: 0x63afb54 VA: 0x75989c7b54
	public Void .ctor(Int32 value) { }
	// RVA: 0x63afbcc VA: 0x75989c7bcc
	public Void .ctor(Int64 value) { }
	// RVA: 0x63afc44 VA: 0x75989c7c44
	public Void .ctor(Single value) { }
	// RVA: 0x63afcbc VA: 0x75989c7cbc
	public Void .ctor(Double value) { }
	// RVA: 0x63afd34 VA: 0x75989c7d34
	public Void .ctor(Boolean value) { }
	// RVA: 0x63afdac VA: 0x75989c7dac
	public Void .ctor(String value) { }
	// RVA: 0x63afddc VA: 0x75989c7ddc
	public Void .ctor(Object value) { }
	// RVA: 0x63afe0c VA: 0x75989c7e0c
	public Void .ctor(SByte value) { }
	// RVA: 0x63afe84 VA: 0x75989c7e84
	public Void .ctor(UInt16 value) { }
	// RVA: 0x63afefc VA: 0x75989c7efc
	public Void .ctor(UInt32 value) { }
	// RVA: 0x63aff74 VA: 0x75989c7f74
	public Void .ctor(UInt64 value) { }
	// RVA: 0x63affec VA: 0x75989c7fec
	public virtual Object get_Value() { }
	// RVA: 0x63afff4 VA: 0x75989c7ff4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63b0100 VA: 0x75989c8100
	public override Int32 GetHashCode() { }
	// RVA: 0x63b0108 VA: 0x75989c8108
	protected Void SetValue(Object value) { }
	// RVA: 0x63af7d8 VA: 0x75989c77d8
	internal static Boolean <.ctor>g__TryConvertFromInvariantString|2_0(Type typeToConvert, String stringValue, out Object conversionResult) { }
}
```