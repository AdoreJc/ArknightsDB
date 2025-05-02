# DisplayNameAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `String <DisplayNameValue>k__BackingField`


## Properties

- `String DisplayNameValue`


## Methods

- `String get_DisplayNameValue()`

- `Void set_DisplayNameValue(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class DisplayNameAttribute : Attribute
{
	public static readonly DisplayNameAttribute Default; // 0x0
	private String <DisplayNameValue>k__BackingField; // 0x10

	public virtual String DisplayName { get; }
	protected String DisplayNameValue { get; set; }

	// RVA: 0x63b2674 VA: 0x75989ca674
	public Void .ctor() { }
	// RVA: 0x63b26d8 VA: 0x75989ca6d8
	public Void .ctor(String displayName) { }
	// RVA: 0x63b2708 VA: 0x75989ca708
	public virtual String get_DisplayName() { }
	// RVA: 0x63b2710 VA: 0x75989ca710
	protected String get_DisplayNameValue() { }
	// RVA: 0x63b2718 VA: 0x75989ca718
	protected Void set_DisplayNameValue(String value) { }
	// RVA: 0x63b2720 VA: 0x75989ca720
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63b27ec VA: 0x75989ca7ec
	public override Int32 GetHashCode() { }
	// RVA: 0x63b2814 VA: 0x75989ca814
	public override Boolean IsDefaultAttribute() { }
	// RVA: 0x63b287c VA: 0x75989ca87c
	private static Void .cctor() { }
}
```